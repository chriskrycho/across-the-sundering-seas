Hello, readers! We’ve nearly made it to the end of the longest April in living memory, and that after the longest *March* in living memory. I hope, very earnestly, that you are all well physically and as well emotionally as you can be in the midst of this upheaval. Things are bumpy out there. They’re bumpy here, too. But we all keep trucking onward.

---

Your weekly refresher, because these virus times are really something: I’m [Chris Krycho], this is [Across the Sundering Seas], and here I think out loud in public about the things I’m reading and studying and learning, hoping that they benefit you to some degree and in some way. You can [unsubscribe]({{unsubscribe_url}}) at any time without hurting my feelings one bit.

[Chris Krycho]: https://v5.chriskrycho.com
[Across the Sundering Seas]: https://buttondown.email/chriskrycho

---

This week I want to share some in-progress thoughts that are part of an in-progress essay I’m working on about software and *state*. State is both “how things are in the program right now” and “how things change over time in the program.” If nothing changes in the state of the program, it’s not (usually) a useful program. And if nothing changes in the state of the world as a result of your program, it’s *really* not a useful program. But of course, defining “change” here is tricky.

The whole world is a great stateful place, for one thing. From the quantum foam that is the universe’s background steady state! to the galaxy clusters spinning around each other as the whole cosmos rushes apart, 14 some-odd billion years and going strong, things *are* and things are *changing*. Everything we do is part of that. Even the most “useless” program is inextricably, unavoidably a part of that: if all it does is sit there and run an infinite loop, it is still changing the world: drawing electricity, converting it into heat that fans have to dissipate, thereby shifting the building in which it’s running, in some small way thereby altering the owner’s finances and the global economy and the global ecology alike. *Everything* is like that, computer programs not exempted.

But the kind of statefulness, and the kinds of changes-in-state, that I have in mind are, if not more *significant* than that (how exactly would you measure the significance of those kinds of things anyway?) then at least more interesting-to-most-working-developers than that. (I was going to stop with “more interesting,” but I for one find the above considerations endlessly fascinating.) Managing all the state of a program and how it maps to the state of the rest of the world is one of the fundamental challenges of doing software well. The kinds of weaknesses I discussed back in issue [2020 #06: Structural Exploitability][2020-06] were all related in various ways to the challenge of state, because *everything in programming* is related to it.

I’d go further and say (as I’m going to say in this essay if I ever get it sorted out) that every significant advance in programming paradigms and techniques has been related to managing state more effectively. That may not have been the *only* thing those shifts were doing—for some of them it was a secondary effect noticed only well after the fact—but it connects. The creation of [compilers]; [Go To Statement Considered Harmful] and [structured programming] more generally; object-oriented programming, functional programming, logic programming, and likely other paradigms I’ve never even encountered; front-end frameworks like [React] and ideas like [auto-tracking] and entire programming languages like [Rust]: all of these are tied up to varying degrees and in various ways with *managing state effectively*.

It’s no surprise, then, that a lot of the biggest arguments in software development as a practice come down to questions about how *best* to handle state.

- Do dynamic types or static types work better?
- Should we have state bundled up locally with the functions (methods) which operate on it _a la_ object-oriented programming languages?—or should data and transformation be separated in various ways _a la_ functional programming languages?
- Should any given piece of data be immutable, as in purely-functional idioms?—or should data be freely mutable anywhere, as in traditional imperative idioms?—or can we somehow get the best of both, as in Rust’s approach?

We could multiply those questions… and for this essay that’s exactly what I’m doing.
One challenge is simply finding the right words! I started out thinking in terms of “essential” and “inessential” state, but as a good friend pointed out when I started talking this through with him, in some sense *all* state is essential to a program. When you’re filling out a form, if your browser reloads and your entries are gone, there’s nothing *inessential* about the time you wasted and have to spend again: that state may have been *ephemeral* until saved in some way (“persisted” in software-speech), but it wasn’t therefore any less *important*.

Likewise, there’s some value in thinking in terms of “root” and “derived” state—but even there, much of what constitutes “root” vs. “derived” is a matter of context. Root state in a web user interface might be derived from a payload that came across the wire which was itself derived from the root state that is in a database. And the relationship between different roots for state, and the inherent dynamicism of useful programs—state changing because you and I *do things with the programs*, that being the whole reason for their existence!—means that we need ways to model relationships between roots, or to control access to root states in various ways, and then to flush that back out into all the derivations in the rest of the program… and even that doesn’t exhaust the ways of talking and thinking about state.

I don’t have a lot of great language for these concepts; one of the reasons I’m working on this essay (and thinking-out-loud at all of you in this newsletter) is to try to nail it down in my own mind better! So: if you know of good existing materials on this subject—whether essays, talks, papers, books, or what-have-you—I’d love to hear about them!

Stay well, and happy learning this week!

[2020-06]: https://buttondown.email/chriskrycho/archive/b42e61a1-dcd4-4938-865a-adf0621028cd
[compilers]: https://history-computer.com/ModernComputer/Software/FirstCompiler.html
[Go To Statement Considered Harmful]: https://dl.acm.org/doi/10.1145/362929.362947
[structured programming]: https://en.wikipedia.org/wiki/Structured_programming
[React]: https://reactjs.org
[auto-tracking]: https://www.pzuraq.com/what-is-reactivity/
[Rust]: https://www.rust-lang.org