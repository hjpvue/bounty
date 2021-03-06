
☐ Project/Request automation  
→ ☐ GitHub component: create issue  
→ ☐ Telegram: post to https://t.me/bounty_aga  
→ ☐ bountysource: post bounty  
→ ☐ Freelancer: post Project  
→ → ☐ unified interface to bids and conversations  
→ → ☐ option to start a bid chat with a question that wasn't answered in the bid  
→ ☐ Fiverr: post Request  
→ ☐ peopleperhour: post project  
→ ☐ track communication, “passing the ball”  
→ ☐ send reminders and/or suggest a change of tactics when the ball is stuck  
→ ☐ QI questions, tags, notes  
→ ☐ close issue, stop projects, reclaim bounty

☐ Write a couple of components and see how can we plug them together  
→ ☐ a tool for freelancers to monitor [Freelancer](https://developers.freelancer.com/)  
→ → ☐ Fiverr  
→ → ☐ Upwork  
→ → ☐ peopleperhour  
→ → ☐ bountysource  
→ ☐ VSCode autocompletion  
→ ☐ AI Dungeon  
→ ☐ ObservableHQ interface  
→ ☐ klines server  
→ ☐ random IMDb  
→ ☐ steam  
→ ☐ dice length graphics, DP  
→ ☐ kindle

☐ Experiment with gathering notes and folksonomies  
→ ☐ Long tail  
→ ☐ City map

☐ Mobile notes  
→ ☐ NodeJS on Termux  
→ → ☑ Import to Agenda  
→ ☒ amynet home screen widget

## ideas around the “my net” toolbox

* Offline-first. The code (application, toolbox) should help me with networks (clients, developers, providers, products) even without the internet. The information I enter should be useful first and foremost to myself. That way, if I decide to share it, the information will be truthful and hence also the information I'm getting from others.  
(Compatible with [Syntropy](https://youtu.be/gSPNRu4ZPvE), the argoforestry metaphor?)

(Folksonomies are immediately useful as a way to retain information, to counter and/or detect eventual Transference, to guide simplifications. This might not be obvious).

* Reuse. The code should add what's missing. If something is already implemented (job and bounty sites, markets, social networks) we should plug into the existing system, provide an added Value for them. For example, Upwork and GitHub already track the open source and private engagements, we can add combined statistics and graphics for them.  
🧧 One application of offline-first and reuse is to be able to export the information into an archive and post it as a conventional forum attachment, or send with email, etc.

* Anonymous. If we share our notes or folksonomies, they should conflict not with our long-term engagements. [Outing a Munchausen can be a career ending move](https://youtu.be/UkMC_pz0eaM), for example. The code should allow us to share such information without such risks. On the other hand, there should be limits on spam and slander.  
Let's enumerate some possible conflicts.  
a) Truth versus reciprocity, biased towards positive.  
b) Truth versus scarcity, biased towards negative. J: “Say that a given company hires you and in fact they are really very satisfied with your work, price and personality. If the that company has a very competitive management, perhaps they would think giving you anonymous low rates would prevent you from being hired by a competitor or anyone else, therefore making you more readily available, perhaps even more affordable, to that company. Or the opposite, a developer finds a client so good that they would like to keep to themselves by anonymously trashing the client's image on the network.”  
c) Truth versus [Transference](https://en.wikipedia.org/wiki/Transference), [Game](https://en.wikipedia.org/wiki/Games_People_Play_(book)), biased at random. Something can [trigger](https://en.wikipedia.org/wiki/Trauma_trigger) a particularly subjective reaction.  
d) Truth versus culture, [biased towards negative](https://twitter.com/Artemciy/status/1331351201401737219).

* Multi-faced. Similar but not equal to anonymity, the idea here is for some traits to be discoverable only when looked for. For instance, developers would often optimize their profile and/or CV to match well a single and narrow specialization, cutting away at anything that doesn't match it. While helpful on the outset, it might prevent us from discovering new and interesting synergies. Maybe the toolset should allow for a gradual discovery of certain folksonomies.

* Pluggable. There should be a container and/or a glue for the plugins. The plugins can be, in turn, small, simple, DSL/DDD-readable, free of unnecessary boilerplate.  
Proxy plugins can help with invoking internet plugins, which might in turn be hosted on repl.it, runkit.com, colab/kaggle, or in an observablehq cell.  
GitHub plugins can share progress updates and GIFs.  
VSCode/platform/Discord-status plugins might be helpful with homing on a good time.  
A plugin might get a structured access to the Steam games and then another plugin might find the writer's name in the description of the Choice of Games titles.  
The user interfaces are pluggable as well. Some might be tinkered with on ObservableHQ

* Literate. The tools should bear descriptions and use case examples in the code. The databases should be readable (such as JSON with comments).

* Graphical. Generating shiny things and benchmarks. Maps.

* Automating. Computers are good at repeating things. At keeping a pace.  
Examples of things to automate `(Telegram-DE 2021-02-10)`:  
🪕 Asking a freelancer about an ongoing project. Or else, reminding a client that they can catch up with a freelancer and suggesting some useful questions for that.  
🪀 Maintaining a list of projects, their “vision” and “next step”, how much they are currently in a focus.  
🪁 Informing the known (and tagged) developers about a task, providing them with the fast “interested” / “other tasks” / “snooze” options. Respecting time preferences. Pacing to avoid overlaps. Taking notes of responsiveness and interest. Filing GitHub issues and placing bounties on them. Offloading a task to freelancing platforms. Reaching out to prospective freelancers through [search](https://www.upwork.com/ab/profiles/search/?q=MUSL).  
🏀 Organizing task-based competitions between teams.  
🔮 Keeping network notes. Suggesting QI questions to ask.
