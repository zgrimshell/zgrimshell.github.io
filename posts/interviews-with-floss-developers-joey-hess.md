<!-- 
.. title: Interviews with FLOSS developers: Joey Hess
.. slug: interviews-with-floss-developers-joey-hess
.. date: 2015-02-28 21:27:17 UTC+02:00
.. tags: joeyh, debian, floss, hacker, interviews
.. link: 
.. description: 
.. type: text
-->

_Edit: Now translated to [Chinese](http://www.labazhou.net/2015/03/interviews-
with-floss-developers-joey-hess/). Thanks zhang wei!_

There is really hardly a better way to open a series of interviewing with
developers behind Free Libre Open Source Software project, then with
incredible mind such as Joey Hess. To write his contributions to Free software
ecosystem, especially in Debian, would be a book by itself. His impact exceeds
even his projects - people literally follow his blog posts to see what he is
doing and how is he living. A hacker from cabin. If you really need to have a
picture of true hacker, then Joey is the one. As this isn't a book I will just
mention few projects that he has been behind - git-annex, ikiwiki, etckeeper,
debian installer, parts of dpkg, debhelper, devscripts, taskel. So without
further waiting here it is.

<!-- TEASER_END -->

![Picture of Joey Hess](../images/joeyh.jpg)

**me**: _Who are you?_

**joeyh**: I'm Joey -- <https://joeyh.name/>

**me**: _How did you start programming?_

**joeyh**: Atari 130XE which came with BASIC and a boring word processor and not much else. No other friends had one, so the only way to get software was to type in demo programs from manual and then begin to change and write my own. So, the easy way to learn. Also some Logo in school.

**me**: _How would you now advise others to start programming?_

**joeyh**: Difficult question, it seems much harder to get an intimate understanding of things than when I started, and much harder to be motivated to program when there's so much stuff easily available. Maybe simple bare-metal systems like Arduino coupled with real-world interaction are the answer.

I've recently been mentoring my nephew who is learning python and [Python the
Hard Way](http://learnpythonthehardway.org/) has gotten him far impressively
fast.

**me**: _Setup of your development machine?_

**joeyh**: Lenovo laptop de-spywared with Debian unstable, xmonad, xfce, vim.

**me**: _Your thoughts on Purism (the open hardware laptop initiative that got recently funded on CrowdSupply)?_

**joeyh**: I don't know much about that one, but it seems that consumer level hardware has gotten so low quality, and so closed and untrustworthy that it makes sense to either build alternatives that are open, or pick out, as a community, the stuff we can adapt to our needs and concentrate on it. Several projects are trying, I hope they succeed.

**me**: _How do you see future of Debian development?_

**joeyh**: Well, I've mostly stopped worrying about it. If you look back at my presentations at the past 2 or 3 DebConfs, you'll find my best thoughts on the matter.

**me**: _You retired as Debian developer - do you intend sometime soon to come back and/or do you plan to join some other communities?_

**joeyh**: It would be glorious to come back, wouldn't it? But I don't think I will. Can't step in the same river twice, and all.

Instead, Debian will probably have to put up with me as an annoying upstream
author who doesn't ship tarballs, but does ship debian/ directories, and as a
bug reporter who enjoys reporting amusing bugs like [-0
NaN](http://bugs.debian.org/778800).

I seem to have more time to spend in other online communities since I left
Debian, but in a more diffuse way. Maybe that's just what it's like, to be
involved in Free Software but not in the embrace of a big project like Debian.

**me**: _Some memorable moments from Debian conferences?_

**joeyh**: There are so many! Picnicing on berries and tamales at the Portland farmer's market right outside the venue; rainbows and bonfire in Switzerland after crazy busy days; impromptu pipe organ repair in a weird night venue in Edinburgh; walking through Porto Alegre at night with Ian Murdock and how humble he was about what he'd started; hacking all night in Spain; failing to sleep through midnight sun and incessent partying Finland; hanging out in the hotel lobby in Atlanta where we designed Build-Depends.

**me**: _Are you a gamer? Valve Steam games are offered for free to Debian Developers - do you use steam and play Valve games?_

**joeyh**: I've played through Half Life and Portal, but nethack has claimed more of my time. I mostly enjoy short, indie games, or games that tell us something new about the medium of games, A recent favorite was [A Dark Room](http://adarkroom.doublespeakgames.com/).

But really, I have more pure fun playing real world Tabletop games with
friends, like Carcassanne Discovery and Hive.

In March, I am going to try to write a roguelike game in one week, in Haskell,
for the [Seven Day Roguelike Challenge](http://7drl.org/) and I'll be blogging
about my progress daily.

**me**: _You are nowdays a Haskell hacker (git-annex) - what would you like to say about this language and how does it compare to Python, C, JavaScript, Ruby and Perl?_

**joeyh**: Not just git-annex; all my current projects are written in Haskell.

I think it's amazing how much we expect programmers to keep in their heads
while writing code. Is that buffer going to overflow? Is changing the value of
that global variable going to break some other part of the code? Is that input
sanitized yet? Did that interface change? Haskell solves some of these
outright, but more, it makes you start noticing this kind of pervasive issue,
and it provides ways to completely eliminate a class of problems from your
code.

For example <http://joeyh.name/blog/entry/making_propellor_safer_with_GADTs_an
d_type_families/>. The class of bugs I avoided there had never affected my
code even once, but it was still worth preventing that whole class of bugs, so
I don't have to worry about them ever again.

**me**: _Would you suggest Haskell as first language to learn especially for those that have an itch for mathematics?_

**joeyh**: I think that can work well. Or it can go other the way -- I had an affinity to mathematics when I was young, but it got knocked out of me in the way that happens to many people, and languages like perl and C don't do much to make you want to learn more about higher-order math. I've been picking up a bit more here and there via Haskell.

**me**: _How do you compare your productivity in Haskell compared to your Perl days?_

**joeyh**: It's very different; I'm a very different programmer now. I probably would bang out quick hacks more quickly when I was writing Perl. But, they tended to stay quick hacks. Now, I might take a little longer to get there, but the code seems a lot more solid, while also being more malleable to turn into larger or different programs.

I'm also a lot more drawn toward writing software libraries.

**me**: _Can you describe your philosophy of life (you live in cabin, in forest, using a lot of solar power - many people are intrigued (including myself) what drives you towards that kind of life and how does it impact your overall quality of life and happiness. Looking the todays modern predator capitalistic society, in which you could easily earn more then $10.000 a month, you seem to be an anarchist and very humble human)?_

**joeyh**: I want to build worthwhile things that might last. Which is super hard in the world of software, both because it's hard to think far ahead at all, and because most jobs don't emphasize that kind of real value. I've been lucky and bootstrapped up to a point where I've been able to work full time on free software for years, and I'm willing to forgo a lot to continue that.

Living in the woods without modern conveniences is great, because it's quiet
and you can think as much as you like; the internet is just as close as it is
anywhere else (maybe a bit slower); and when you've spent too much time
quietly thinking you'll need to go chop wood, or haul water, or jump in the
river to cool off, depending on the season.

(Humble? Like most programmers, I am internally a flaming tower of ego...)
