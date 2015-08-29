<!-- 
.. title: Interviews with FLOSS developers: Elena Grandi
.. slug: interviews-with-floss-developers-elena-grandi
.. date: 2015-08-29 16:23:44 UTC+02:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

One of fresh additions to Debian family, and thus wider FLOSS family is Elena Grandi. She is from realms of Valhalla and is setting her footprint into the community. A hacker mindset, a Free software lover and a 3D printing maker. Elena has big dedication to make the world free and better place for all. She tries to push limits on personal level with much care and love, and FLOSS community will benefit from her work and way of life in future. So what has the Viking lady to say about FLOSS? Meet Elena "of Valhalla" Grandi.

<!-- TEASER_END -->

![elena](../images/elena.jpg)

###Who are you?

I am somebody who likes to create things and who happens to be in the middle of her thirties.

###What parts of FLOSS community are you engaged?

I've been involved with the local LUGs for 15ish years, and in the last few years also with the Debian project, up to now just as a contributor.

###You had been also involved in openembedded?

Yes, back when I started using Single Board and other low power computers I used OpenEmbedded on them and wrote/maintained a few recipes for a few programs I needed. I wasn't really involved with the community, however, and I left when a (much needed) restructuring of the OpenEmbedded workflow/repositories meant I would have had to re-learn how to use it, and the growth of storage media meant that there was no longer a pressing reason not to use Debian even on low power boards.

###How did you start programming?

It sort of happened.
I've had some exposure while I was growing: one experimental lesson of logo (and a great one of logo with the child as the turtle) at elementary school, then some copying of Basic programs on my parents' computer and later a bit of Pascal at early high school.  Then I started using the computer more, and I wanted it to do stuff the way I wanted, which led me to writing shell scripts, and then python scripts, and then more complex python scripts, I've then read a couple of books on more theoretical parts and one day I realized I could program.  The fact that I was studying mathematics probably helped a lot with having the bit of theoretical background needed in the latter stage.

###How would you now advise others to start programming?

I'm not sure that my own experience is easily replicable, so I don't think I have an answer, but I have a consideration for parents: just as children who live in an environment where adults routinely read for fun have a higher chance of growing up as readers, to educate children to become programming literates try to give the example as an active computer user and not a passive consumer of media.

###Setup of your development machine?

I'm using mostly an old PC that I got from a relative who wanted to buy a new one to be able to run Windows Vista, back when it was released.  I'm considering upgrading to a liberated thinkpad with coreboot (mostly because of the freedom side), but I'm having an hard time decide to stop using something that basically still works.  When traveling, I'm sharing an efika smartbook with my SO, who is also a long time Debian user: it's an ARM based laptop with lots of battery life that was sold with Ubuntu preinstalled (and of course runs debian quite well), but can't be upgraded anymore, since the System on Chip is not supported in mainline Linux, and the producer stopped releasing updates.  I'm trying to replace it by assembling some sort of laptop/tablet hybrid out an OSHW (Open Source HardWare) board which is supported in mainline Linux and in Debian but the case part (some of which is made in paper mache) is taking some time.

###What is your preferable language? Why? How do you compare it to other languages?

My main language is Python: part of it is probably because that's what I started writing real programs in, but there are a few reasons why I enjoy it. On the techical side there are the ability to start writing things with little overhead and boilerplate, but also the fact that even if it has its own quirks, the overall feeling is of something that has been designed with a plan in mind, not thrown together from whatever looked like a good idea at the time.  I'm not really active in the python community, but from the semi-outside I also like very much the fact that it presents itself as friendly to beginners and other outsiders.  As for other languages, I'm not really interested in learning other languages that I percieve as covering more or less the same ecosystem (such as ruby or perl), but I wouln't mind having time to learn something different, maybe lisp or haskell.

###Describe your current most memorable situation as software developer/hacker?

One of the things I remember fondly is one of the first time somebody decided that something I had written was useful enough to improve on.

It was just a quick graphical front-end to gpsbabel written in bash using kdialog/zenity as a one-off thing to help using a specific GPS logging device, but seeing it grow from "one off script" into "tiny project, with a maintainer and a Debian package" was a great experience.

###Some memorable moments from Debian conferences?

I've only been to one Debian conference, the Women MiniDebconf in Barcelona, and I remember it as a succession of memorable situations, all merging together.

###What are your future plans in Debian, what would you like to work on?

I've started contributing by finding something small that I needed and was missing/wrong, and adding/fixing it, and basically that's what I plan to continue doing; currently this is mostly in packaging, but if a chance happens I wouldn't mind doing some programming, or something else entirely.  I like working on small things, the ones that won't give everlasting fame, but are useful as part of somethin bigger.

###Why should developers and users join Debian community? What makes Debian a great and happy place?

We have cookies! They are a fundamental corruption device for any self-respectful Evil Organization bent on World Domination, like Debian is, and people should join us to be on the winning side when we succeed.

Actually, one of the strenghts of Debian is that it involves many different form of contributions beyond the classics packaging / coding, and that work is being done to recognise them properly, so yes, if you want to come in Debian and bake cookies, you're welcome!

###Is there something you would change in FLOSS ecosystem?

If I had a magic wand I would probably be tempted to change a number of things, but then I suspect I would need to use the wand again to revert the change because it's not working out as I expected (hopefully it would come with full version control support!).  On the whole, the FLOSS ecosystem is already changing with time, and I believe that more than half of the changes are in a good direction, which is a good situation.

###Your thoughts and compare Cloud, IaaS, PaaS, SaaSS? To what should the FLOSS world pay more attention and energy?

Cloud in itself isn't evil, nobody is able to do everything and buying the services of somebody else to help is a necessity: none of us is self-sufficient to the point where they grow everything they need to eat. This doesn't mean that Cloud is a magic word that makes everything work, and there are a number of specific dangers to be wary of, which are usually worse on the SaaS end of the scale.  One of the big dangers is being stuck with a single provider, either because of lack of alternatives or usually because of more subtle reasons such as data being stuck on the provider or network effect.  Here the FLOSS world can help by developing platforms based on interoperability and federation, which can then be either self-hosted or provided as a service by a number of competing companies.

The various *aaS tend to be listed in the direction of increasing danger, which means that more care should be taken when considering whether the risks overweight the advantages,

###Your thoughts on open hardware and why is it important?

Once upon a time, buying a piece of hardware meant that you were able to thinker with it: often you even had some schematics and detailed manuals that went way beyond what was needed for day to day use, and you could learn about it, repair it yourself (or have it repaired by some local technician) and in some cases even modify it to better fit your needs.

Nowadays hardware is sold as a sealed box: you are not expected to look too closely at what it is doing, and in many cases you are explicitely prevented from doing so, legally, phisycally or both.  Even worse, there have been cases where not only you didn't control the hardware, but it was designed to be more useful to its producers than to the people who had bought it.

Open hardware is the main way to resist this trend, with devices that can be studied, adapted, improved, and allows the growth of an ecosystem of people who know about the hardware they are using, and, as with free software, can help each other with improvements, but also by checking for misdeeds.

Unluckily, hardware is way more expensive than software to develop, so the situation with open hardware is quite primitive as compared with the Free Software one, but using and helping the existing projects is the only way to try and improve the situation.

###Why are distributed social networks and self hosting an important part of the entire society?

By using centralized proprietary services to host our data and our communications we grant their owner an huge power on ourself and our society. If communication happens in a single private venue it is subject to the arbitrary policies and censorship rules of that venue, even if the people involved live in a country where freedom of speech is a right granted by the laws / constitution.

For example in the case of political activism, social networks are a great resource to communicate with people both in some area and all around the world, but depending on a company for it has significant dangers: accounts can be closed or otherwise silenced with no need for an explanation and basically no recourse.

It is also important to use distributed social networks to share pictures of kittens: a social network where you can only meet like minded extremists isn't that useful, and in some cases it can even be dangerous, as it makes you an easy target for surveillance.

Here self-hosting is as an important part as being distributed/federated: e-mail is fully federated, but if everybody are using a couple of big providers they are able to set the rules as if they were just a single entity, expecially since big web-based tech companies tend to have similar ideas on what kind of content isn't appreciated by their customers, the advertizers.

###Why does privacy matter to you?

Being under constant observation from something who has the power to ruin your life or at least cause significant difficulties means you have to keep constant guard in what you do, in order not to attract its attenction, and isn't exactly the best way to live a stress-free life.

One fun aneddote on the topic: the human mind is trained to spot dangers from tiny hints, and tends to be prone to false positives because jumping at a bush moved by the wind that reminded a tiger is much safer than ignoring a real hungry tiger coming at you.  One day I was walking through a wood and spotted a rectangular shape fixed on a tree just above head height: the first thought in my mind was "camera? what? what is a camera doing here?".  Then I looked at it, because my instincts are still somewhat better at surviving tigers than surveillance, and realized it was just a way marker, but I believe this is indicative of something.

###You use Firefox on phone - how would you compare it to Android and other popular mobiles OSes?

I'm not a big smartphone user: I'd rather interact with a device with a real keyboard and a full GNU/Linux OS, even if it is small and low-powered; my phone is used to tether an internet connection, emergency internet searchs and offline wikipedia browsing.

With this limited task set I'm quite happy with FirefoxOS: it manages to work well even of very low-powered (and cheap) devices; on the other hand I've never had an Android phone (nor of course one of those other walled garden ones), and from what I've heard there are still a number of tasks for which FirefoxOS is not really ready.

Even with my limited usage, there are two things I don't like: one is the lack of percepible distinctions between online and offline, which I've heard is common on all other platforms, the other is the lack of license information on the market, which makes it harder to only install Free Software, and here Android + F-Droid would work much better.

On the other hand, developing web apps for FirefoxOS is much nicer than developing for android and while my attempts to only use Free Software to do the latter failed badly, doing for FirefoxOS it can be done with just an editor and a copy of iceweasel straight out of the Debian repository.

###You have an interest in 3D printing - why does it attract you and care to share a picture of your work?

As a DIYer, I've often felt the need for a way to build customized bits of plastic to certain projects, and 3D printing solves that need: one-off production that can however be repeated more or less precisely, allowing for further controlled improvements as needed.

The fact that the printers are also Free Hardware makes them also interesting in themselves: the ability to thinker with your tools and share the results has an obvious appeal.

As for my work, I can share more than pictures, I can share source code  I don't have an account on thingiverse because I don't like their ToS, and I haven't setup my mediagoblin instance yet (because I'm lazy), but most of it is on a git repository listed on http://git.home.trueelena.org/gitweb/?a=project_list&s=3d%2F&btnS=Search