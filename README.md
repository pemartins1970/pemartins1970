## Hi there 👋

Thanks for making it this far.

My name is Paulo. Pê Martins is a nickname I got from an old and dear friend, Bruno Parodi, almost thirty years ago. I'm an entrepreneur from the first generation of the Brazilian internet — back in 1996 — and no, not from the group that got filthy rich. Far from it.

I was the founder of NOMAD Media, one of the first digital marketing ventures in Brazil, and co-founder of Lemon ([lemon.com.br](http://lemon.com.br)), the first portal specialized in downloads in the country — though there's an annoying competitor that would beg to differ. I worked on projects for AOL Brasil and Starmedia, among various other groups and startups. I co-developed, in partnership with Buyonet, the first software purchasing website using the ESD model in South America. I've worked as a consultant across dozens of projects and served as an executive and manager across many different industries and verticals.

I am not a programmer. I am not a designer. I am not a systems engineer. But I do whatever it takes to bring the things I build to life.

---

I had been following the AI market closely for a while, though still resistant to adopting it at scale — especially for myself, now a "graybeard" at 56, father of a wonderful 28-year-old woman and a bright 14-year-old kid. I'd look at tools like ChatGPT and the others and think exactly what every aging young man thinks: *"Oh, if only this had come along when I was young and still had time to wait..."*

Then the market's hyper-acceleration caught me off guard. Sometime in the second half of 2023, after hearing endless praise about a handful of agentic IDE products that were supposedly "miraculous," I decided to give one a try. Being no developer and having sky-high expectations, I thought it was all rubbish. But having searched for agentic IDE products, the advertising machine wouldn't leave me alone. Annoyed, I shut my old laptop — the same one I'm writing this on — and didn't open it again until early October 2025, living on my phone for everything in between.

It took me a few days to get the old machine running again. The moment I finally had it back up, updates done, I was bombarded with ads once more. You lose track of how much your perspective shifts when you step away from a computer for that long.

Then one day, browsing Reddit and reading posts from developer friends, I stumbled into a long discussion about a product. The criticism leveled at it — which I won't name, because I actually love it even if the developers can be insufferable — was precisely what piqued my interest, IDE or not. I downloaded it. Free tier. I set myself the challenge of rebuilding the Lemon layout (which was eventually delivered, though my partner still hasn't put it live to this day). I spent a week or two frustrated with the process. Then I got it done. And I was genuinely thrilled. I hadn't typed a single line of code, and the agent had done what I'd always dreamed of having someone do for me. Fast. Absurdly fast.

That got me wondering: could I use the same tool to implement every improvement I'd been wanting to make to the portal? I decided to try. By the end of the first half of November, I had something concrete, complete, and functional. Still full of bugs — but I had gotten there.

I thought: *now that I've gotten this far and made so many mistakes, maybe I can reproduce the whole thing from scratch.* The original site was in ColdFusion, and I wanted to experiment with other languages. I set out to rewrite it in Python, in a process considerably more refined than the previous attempt, aiming to launch a new version by the year's end. Everything was ready, but my partner was swamped, and I was thousands of kilometers away from the company — I thought: *it's not going to happen.*

But I had built it.

From January 1st through the 6th, I generated an almost unbelievable 11 versions of the same portal. I made a lot of mistakes experimenting. I learned to fail faster, stopping at each critical error and changing course — especially because my free tier was running out and I was genuinely having fun with the process.

My computer is still an old Core i5, originally with 4 GB of RAM that I bumped to 8 GB, and a 1 TB factory hard drive that's nearly full to this day. A warrior. But there is no decree in the universe that would make it run a local LLM. These models weren't architected with that in mind. And that frustrated me deeply. I'm not buying a bigger machine just for that. I come from a generation that fought hard against lazy software manufacturers who, with each new version, bloated their products with unnecessary features and rendered them unusable on older hardware.

I have friends on the African continent who can barely get their hands on a decent device to study. And it's not much better here in Brazil. *"How is this generation supposed to get ahead from that position?"* I used to think. And heaven help anyone who comes to me with talk of effort and meritocracy.

---

Anyway. Through all of this maker-style exercise of building projects in partnership with AIs and agents, I was slowly becoming literate in their workings. Understanding nuances, capabilities, where one excels over another and where it falls short. I decided to commit to the path. For the first time in my life, I paid for access to software I don't own — something other than a Windows license. I subscribed to the Pro tier of a tool and decided to go all in.

There's a lot of people out there building extraordinary things. That's not what I'm doing. I decided to dig up old projects — well-documented ones, ideas for products I'd been dreaming about for ten, fifteen years. Things with a beginning, a middle, and an end. I thought: *I'll build them and release everything open on the internet. Put it on GitHub and hope it's useful to someone.*

But given the number of projects and their complexity, doing everything locally would have taken me forever — not because of the IDE, but because of the sheer volume. Practically retired, no team to share the workload. I looked at the screen and decided to strip out everything that wasn't absolutely essential for the task. Left only the basics on the system: a document viewer for Word and PDFs, IrfanView — the one program I will never part with — and the IDE I'd subscribed to. I opened the browser and, already familiar with most of the limitations and capabilities of available tools, spent the bulk of my time working with an AI in each tab, handling different stages of the work. I started operating in genuine partnership with them, and they with me. They would analyze an obscene volume of project documentation at brutal speed, and I would set the direction. At other times, they'd set the direction for me. I'd spend hours prototyping ideas in AI Studio — whatever worked and felt right, I used. I'd collect the outputs (lord, I've never had so many Markdown files in my life) while my local IDE ran 24 hours a day with rare interruptions. I built memory improvements for it, learned where it got bottlenecked, raised the stakes, and started using browser-based AIs to review the generated code as well — a continuous improvement loop that genuinely surprised me.

Five of my documented projects got done. The interfaces still need a lot of work — that's not my strong suit — but they were there. And together, I could see they formed a pretty solid service infrastructure, one I'd never managed to build in an integrated way before. Hours before publishing, I showed one of them to a friend who couldn't believe it was actually finished. He mentioned a problem he was having with AI integrations. I'm no programmer, but I recognized in his struggle something I'd recently gone through myself. We hung up. I put together a quick prototype in AI Studio — rough, but it delivered what he needed and then some, with decent system management and control structure. Sent it to him. Problem solved.

I took that project and, as casually as one would pitch an idea at a bar table, I shared it with the AIs I use. Then I went to get a coffee. On the way, I saw a message from another friend on LinkedIn, complaining about the lack of ColdFusion tools for working with agents, and about how hard the learning curve was — he was thinking about doing a postgraduate course just to get up to speed.

When I came back and read the AIs' responses, I paid close attention to the criticisms (yes, I handle them well — despite what my therapist says. I've been married for decades. You learn. Trust me.) and gave less weight to the praise. But they all pointed in the same direction: I could have used an MCP for that. I remember replying: sure, but why use an MCP for something repetitive that a set of scripts handles continuously, more cheaply, and for that specific purpose — arguably better? And then, in a flash, my friend's LinkedIn complaint came back to me. *Something can be done about this.*

I proposed the idea to the AIs in a quick brief. In less than an hour, a software prototype was born. Initially, an agent with MCP. Which I then decided to supercharge by adding a MoE and access to a local LLM. From the available documentation and materials we put together, we built a native bridge between ColdFusion and the AI universe, now published here on GitHub. It was named **B.E.N.**, in honor of Ben Forta — one of the people I most admire in the ColdFusion community, going back to the Allaire days. Yes, ColdFusion was originally an Allaire product, later acquired by Macromedia, and then by Adobe.

The reception has been disproportionate. I've been receiving private messages from many people who loved the project, even though only one person is actually using it so far. And even so — I loved the experience of building it.

---

The process of learning and relearning, at my age, as someone carrying all the baggage that dyslexia and more than a decade of severe depression leave behind, is hard to put into words. But if everything that's happened since October shows me anything, it's that even in the middle of a pretty rough overall picture, there's a viable path forward. You can start making things again. And I am.

**Above all, I am passionate about product and project engineering, and I’ve found AI to be a means to build the things that interest me, at my own pace.**

**B.E.N.** launched on March 2nd. Today, March 10th — like a Gremlin that fell in water and had a full meal — it has spawned offspring. Several, actually. May my health hold out. I still have a lot left to do. And I want to do it.

If you made it to the end of this monologue: congratulations. Maybe we're more alike than you'd care to admit. All I can do is say thank you.


💡 *"Do nothing that you cannot tell."*
