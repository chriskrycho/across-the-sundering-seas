Hello again, readers-of-newsletters! This week is more the “traditional” format: lots of good links from things I read this week!

1.  [<b>A Regulatory Framework for the Internet</b>][1] – first up is Ben Thompson’s weekly article: probably the best take on *how* to actually regulate the internet in a way that isn’t ultimately just awful for everyone. Because it turns out that swaths of the internet *are* in fact in need of some degree of regulation… but most of the regulatory approaches that have been on offer to date have seemed (or proven!) likelier to end up affecting the wrong players in the market, to cement the existing dominance of the worst companies, and to be tools of abuse for bad actors. That goes, in many ways, for everything from [DMCA] a decade ago through last year’s [GDPR] and this year’s [early proposals by Elizabeth Warren][warren]. Thompson makes a clear case for differentiating between different segments of the market based on specific attributes of those segments—in ways that would keep Facebook from abusing its position and force its hand on consumer protection, while still allowing ISPs to operate in reasonable ways, for example. Perhaps most importantly, for those skeptical of regulation as needful here (or anywhere), he traces out *why* regulation is appropriate:

    > This is, in its own way, a market failure, albeit not, to be clear, in an economic sense: the allocation of goods and services by a Super-Aggregator is not only efficient, but also generates significant consumer surpluses. The failure, rather, comes from videos like that of the Christchurch massacre, or problematic YouTube content. It is not good for society that terrorists be able to freely broadcast their videos, or that [child-exploitation videos spread on YouTube](https://www.buzzfeednews.com/article/charliewarzel/youtube-will-add-more-human-moderators-to-stop-its-child#.xtm3KJv1GP).
    >
    > The problem is that there is no way to check this behavior: the vast majority of Facebook and YouTube users self-select away from this content, and while advertisers raise a fuss if they find out their ads are alongside this content, they have no incentive to leave the platforms entirely. That leaves Facebook and YouTube themselves, but while they would surely like to avoid PR black eyes, what they like even more is the limitless supply of attention and content that comes from making it easier for anyone anywhere to upload and view content of any type.

    The “market” as such is succeeding *perfectly* in strictly economic terms here! …and that’s the problem. [The whole thing is worth your time.][1]

2.  [<b>Nadia Eghbal</b>][2]: yes, here I’m simply linking a writer, because I think her work is of sufficient interest that, if you’re the kind of person who reads *my* newsletter, you should almost certainly keep an eye on the variety of *very* interesting things she’s doing. Eghbal first came across my radar through [a talk] she gave in 2017 on open source software sustainability—a wide-ranging and extremely interesting *and* approachable talk—using the metaphor of city infrastructure to show how open source software has become the infrastructure of our digital ecosystems. This week I enjoyed both [the latest issue] of [her newsletter] and a [blog post on patronage]. Her <b>[Research]</b> page is chock full of interesting things she’s dug into over the last few years; in the course of writing this blurb I read [“An alternate ending to the tragedy of the commons”][commons]—and immediately shared it with my [Winning Slowly][ws] cohost [Stephen Carradini][sc] as of interest for our work this season (as well just being interesting in general):

    > Ostrom believes that given the right conditions, actors can work together to sustainably manage the commons. That means not leaning on government, foundations, or businesses to solve the problem, but rather recognizing (and trusting!) the community’s ability to regulate itself, so long as individuals have **high mutual trust** and a **low discount rate** (i.e., long-term interest in the community). Managing at scale doesn’t mean stuffing more and more people into the same community, but acknowledging boundaries and working together to govern at multiple levels.

    Not only did she put Ostrom on my radar, but she gave me more helpful (sharper, better!) tools for making the kinds of arguments I’ve been trying to make already—something I deeply appreciate.
    
    She’s also interested in making independent scholarship viable (and working as an independent scholar herself!), and as someone who dreams of *being* an independent scholar someday… well, I’m a fan!

3.  [<b>Whatever Happened to the Semantic Web?</b>][3] (Sinclair Target/Two-Bit History)—a fascinating deep dive (and long read, therefore!) into some ideas that *could* have but ultimately did not shape the history of the web since roughly 2000. Those ideas have ended up both mostly obviated—and also, insofar as they were technically useful, absorbed—by Google’s and Facebook’s dominance of the web: The little bits of the “semantic web” that made it through in practice are Google’s “knowledge” cards and Facebook’s [OpenGraph] tools to make fancy previews of your blog post or video or whatever else show up in the News Feed. The hope was for something much richer. Why didn’t we get it? [“Whatever Happened to the Semantic Web?][3] makes an excellent effort at tracing out the history of people and tech that left us where we are today. One of the points raised even in the early history of the idea:

    > Even if users were universally diligent and well-intentioned, in order for the metadata to be robust and reliable, users would all have to agree on a single representation for each important concept. Doctorow argued that in some cases a single representation might not be appropriate, desirable, or fair to all users.

    This basic challenge remains. It is one I have run into repeatedly in programming tasks. The world simply is too complex a place—*especially* when humans are involved—to be easily or accurately reduced to a set of XML tags, no matter how carefully designed. That does not mean there is no future for these ideas; I might just be drawing on a few of them myself in a project I’m working on. But it means that if we *do* use them, we have to do so deeply aware of their limitations, with built-in “escape hatches” to deal with those.

---

A final, short and (not-so?) sweet note here from [Alan Jacobs][ayjay], responding to [Jeffrey Zeldman] asking if the [“indie web”] can scale:

> I think that’s the wrong question. _Of course_ the indie web cannot scale. But that’s a feature, not a bug. Scale — as-big-as-possible, universal-not-local, something-for-everyone scale — is the enemy. It’s the biggest enemy that community and fellowship and friendship can possibly have. If it scales, I want no part of it. 

Although yes, this is indeed tracking along lines related to the points I made [last week][issue-10], I’m not at quite the same point as Jacobs here. I still use (and indeed [*work on*][li]) some platforms which do indeed scale. But I share his view that “does it scale?” is *wholly* the wrong question. Scale *may* be manageable under certain specific circumstances. But it is by no means anything like a [categorical imperative] for tech… and indeed, it may be the opposite.

[1]: https://stratechery.com/2019/a-regulatory-framework-for-the-internet/
[DMCA]: https://en.wikipedia.org/wiki/Digital_Millennium_Copyright_Act
[GDPR]: https://en.wikipedia.org/wiki/General_Data_Protection_Regulation
[warren]: https://www.bloomberg.com/news/articles/2019-03-08/warren-has-plan-to-split-tech-cos-like-amazon-n-y-times-says
[2]: https://nadiaeghbal.com
[a talk]: https://m.youtube.com/watch?v=VS6IpvTWwkQ
[the latest issue]: https://tinyletter.com/nayafia/letters/things-that-happened-in-march
[her newsletter]: https://tinyletter.com/nayafia
[blog post on patronage]: https://nadiaeghbal.com/perks
[Research]: https://nadiaeghbal.com/research/
[commons]: https://nadiaeghbal.com/tragedy-of-the-commons
[ws]: https://winningslowly.org/
[sc]: https://stephencarradini.com/
[3]: https://twobithistory.org/2018/05/27/semantic-web.html
[OpenGraph]: http://ogp.me
[ayjay]: https://blog.ayjay.org/scale-is-the-enemy/
[Jeffrey Zeldman]: https://alistapart.com/article/nothing-fails-like-success/
[“indie web”]: https://indieweb.org
[issue-10]: https://buttondown.email/chriskrycho/archive/2f8a7099-e483-40b9-94e6-0f6e488cdfae
[li]: https://www.chriskrycho.com/2019/a-new-job.html
[categorical imperative]: https://plato.stanford.edu/entries/kant-moral/#CatHypImp