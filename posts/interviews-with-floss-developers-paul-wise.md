<!-- 
.. title: Interviews with FLOSS developers: Paul Wise
.. slug: interviews-with-floss-developers-paul-wise
.. date: 2015-03-04 00:37:55 UTC+02:00
.. tags: pabs, debian, floss, interviews
.. link: 
.. description: 
.. type: text
-->

After starting with [Joey Hess](https://zgrimshell.github.io/interviews-with-
floss-developers-joey-hess/), we continue with Paul Wise. What makes his star
to shine are many things such as being a DSA (Debian System Administrator), a
helpful hand on mailings list, encouraging people to join Debian teams but
most of all - he has encyclopedia knowledge on Debian as a whole which he
gladly shares with anyone who asks (very fast response on IRC channels). It is
almost impossible for any single person to count all Debian teams, work and
places - to know most of those things, you can image the vast knowledge which
Paul has. The legend says that his brain has better and faster search engine
algorithm on Debian related queries than all other engines combined. So lets
see what he has to share with world.

<!-- TEASER_END -->

**me**: _Who are you?_

**pabs**: Paul Wise ([pabs](http://bonedaddy.net/pabs3/)) and I have to say that I'm no-where near as knowledgeable as your intro suggests.

**me**: _How did you start programming?_

**pabs**: Messing around with fractals and graphics things in MS BASIC.

**me**: _How would you now advise others to start programming?_

**pabs**: Pick an issue in a tool you use, investigate how the tool works and how you can change it, fix that and contribute the change back to the project that created that tool. In the process you will learn skills, interact with the community and contribute to the project.

**me**: _Setup of your development machine?_

**pabs**: Lenovo Thinkpad with external monitor, Debian testing and some [tweaks](http://bonedaddy.net/pabs3/log/2012/10/29/thoughts-on-debian-testing/)

**me** _What is your preferable language (for hacking)? Why? How do you compare it to other languages?_

**pabs**: I currently prefer Python for its readability. It still has some rough edges though the documentation covers them fairly well. I generally pick up new languages when working on projects written in them. Haskell is next on the horizon due to [Nikki and the Robots](https://github.com/nikki-and-the-robots).

**me**: _Describe your current most memorable situation as software developer/hacker?_

**pabs**: I had a great time creating fractals in BASIC, learning about the Mandelbrot set, L-systems and more. My days and nights of hacking on frhed (a GPLed hex editor for Windows) to help me cheat at Civilisation were pretty memorable. frhed led to my work on reverse engineering the CHM file format (a documentation format for Windows programs). A stand-out moment during my time with Debian was hacking on the [derivates census patch generation code](https://wiki.debian.org/Derivatives/Integration#Patches) during the Debian UK BBQ weekend, surrounded by geeks playing Portal, cooking things, hacking on Debian and generally having a good time (thanks Steve!).

**me**: _Some memorable moments from Debian conferences?_

**pabs**: There are so many; meeting Debian folks, playing Mao once and then never again, late night games of werewolf, both delectably delicious and hideously disgusting cheeses, fried insects, day trips to beautiful landscapes, inspiring keynotes, exciting BoFs, secret IRC channels for planning surprise birthday parties, blue hair, wet air, blocks of fried cheese, a vast quantity of icecream, pants, geeks in the surf, volcanoes, hiking, a wonderful view, a uni-cycling stormtrooper & more.

**me**: _How do you see future of Debian development?_

**pabs**: I hope we will continue to exist and uphold our principles for the foreseeable future. I don't have any crystal balls though.

**me**: _You recently became member of Debian DSA - what is that like, what roles do you have and what tasks are in front of DSA?_

**pabs**: We wrote a bit of text about that for [DPN](https://lists.debian.org/debian-publicity/2015/02/msg00021.html) recently.

**me**: _You have large knowledge on Debian and you share it with anyone who wants to know more. What motivates you to do so?_

**pabs**: I want the operating system I personally rely on to exist into the future, helping folks work on and join Debian can help with that.

**me**: _Why should developers and users join Debian community? What makes Debian a great and happy place?_

**pabs**: Every Debian contributor has different reasons for joining the community. Personally the Social Contract, the DFSG and the spirit and culture behind them are the main reason to be involved. I also like our many efforts towards technical excellence and correctness. Of course I've made a number of good friends over the years, especially as a result of attending DebConf every year since 2007.

**me**: _You are member of Debian publicity team which writes Debian news - do you need more people to join that team and how can they start?_

**pabs**: Since there is an infinite amount of work to do, pretty much every part of Debian always needs help, that includes the publicity team. We published a [post](https://lists.debian.org/20141114115824.GA4049@pryan.ekaia.org) about ways to help here.

**me**: _If someone wants to contribute to Debian in terms of packaging, can they do it anonymously (for example over Tor network, does Debian have .onion address)?_

**pabs**: Due to Debian's penchant for transparency it is harder but there are definitely package maintainers who have built up a reputation for good work under a pseudonym over the years and become Debian contributors as a result. I'm not aware of completely anonymous package maintainers but there are definitely people who file bugs using one-off pseudonyms, which is almost the same thing as anonymously. There are definitely Debian contributors and members who use Tor while contributing to Debian. In fact, as Debian is very highly dependent on OpenPGP and the best practices for OpenPGP include [refreshing your keyring slowly](https://help.riseup.net/en/security/message-security/openpgp/best-practices#refresh-your-keys-slowly-and-one-at-a-time) over Tor, so probably quite a number of Debian contributors use Tor. As far as I know Debian itself does not run any Tor relays or onion services.

**me**: _What are places that non-packaging developers and people could join and help spread Debian even more?_

**pabs**: There are many ways to [help Debian](https://www.debian.org/intro/help), including non-technical ones. Unfortunately our web page about helping Debian isn't quite up-to-date with all of them but a few more are to [volunteer](http://debconf15.debconf.org/volunteer.xhtml) at [DebConf](http://www.debconf.org/), helo with [artwork requests](https://wiki.debian.org/DebianArt/RequestArtwork), [speak](https://www.debian.org/events/speakers/) about Debian at events or even come up with [ideas](https://wiki.debian.org/Ideas) for projects. Whatever skills you have, Debian can probably make use of them. If you aren't sure where to start, jump on the debian-mentors mailing list or IRC channel and we can probably guide you to the right place within Debian. Don't worry about not being skilled enough, everyone starts somewhere.

**me**: _How do you see Debian will manage webapps?_

**pabs**: Personally I prefer locally installed software, standard data formats and standard data transfer protocols to the wild webapps world but I understand they are becoming very popular to produce and use due to the ubiquity of the web browser platform. Antonio Terceiro is mentoring a [project](https://wiki.debian.org/SummerOfCode2015/Projects/AutoConfigWebApps) for this year's newcomer mentorship programs (outreachy/gsoc) that aims to improve support for installing web apps on Debian installations. I hope it succeeds as it could help make Debian more popular on servers and home servers in particular.

**me**: _How would you advise Debian (and other FLOSS users) to setup their machine in terms of security and anonymity?_

**pabs**: All technology has upsides and downsides. I would advise anyone to analyse their situation and protect themselves accordingly. For example if you have a bad memory, full disk encryption, which is based on pass-phrases might lead to data loss and physical security might be a better choice for protecting your data. The right choices around technology are very much a personal thing.

**me**: _Is it better to setup xmonad (because it is Haskell based WM) with small dependency chain or GNOME (because it is getting sandboxed apps) in term of security and privacy implications?_

**pabs**: Again, the right choices around technology are very much a personal thing. Due to the design of X11, both of these are approximately equivalent from a window-manager security properties point of view, that is to say, pretty bad. Wayland is one of the possible X11 successors and offers much better security properties. GNOME folks are working on switching to Wayland. Ultimately though it comes down to how each person uses their window manager and which software they run under it.

**me**: _Should Debian join Tor project as distro that installs Tor relays by default - should it offer that as option in installer in Debian 9?_

**pabs**: Running a Tor relay requires a reasonably fast and reliable Internet connection and should be a conscious [decision](https://www.torproject.org/docs/faq.html.en#HowDoIDecide) on behalf of the sysadmin for a computer so Debian probably shouldn't install them by default. If tasksel gets support for [installing tasks from Debian Pure Blends](https://bugs.debian.org/758116), then we could add a Tor relay task to the [Debian Sanctuary Pure Blend](https://wiki.debian.org/DebianSanctuary).

**me**: _Have you ever considered joining initiatives such as FreedomBox?_

**pabs**: I was quite moved by Eben Moglen's [talk](http://penta.debconf.org/dc10_schedule/events/641.en.html) at DebConf10 in New York and the resulting [BoF](http://penta.debconf.org/dc10_schedule/events/690.en.html). It seemed like a very ambitious project but I didn't really have the knowledge, skills or time to contribute yet.

**me**: _Are you a gamer? Valve Steam games are offered for free to Debian Developers - do you use steam and play Valve games? Your thoughts on Steam and non-free Linux gaming?_

**pabs**: I play computer games occasionally, all from Debian main or ones that I'm packaging. 0ad is my current go-to for a bit of gaming. I don't have any experience with Steam or non-free games on Linux.

**me**: _Is there something you would change in FLOSS ecosystem?_

**pabs**: Various folks have highlighted new and ongoing challenges for the FLOSS ecosystem in various places in recent years.

Something that I would like to highlight that does not get talked about enough
is the choices we make around our digital artefacts. This is the discussion
around "preferred form for modification" or "source". The "source" for a
particular digital artefact is a deliberate choice on behalf of the authors.
Often generated files are distributed alongside the "source" without any
instructions for reproducing the generated files from the "source". It
sometimes happens that FLOSS contributors forget to distriute what they have
chosen as "source", instead just distributing the generated files. This is a
fairly well known issue but still happens. What isn't thought about quite as
much is that the choice of "source" has consequences for future development
possibilities of that "source". Some forms of "source" are more expressive
than others, can be modified in a wider variety of ways and are better choices
in general. Sometimes the consequences of choosing less expressive forms are
mild and other times they are quite important. I hope more people will start
to think about these choices. Some examples where, in my opinion, various
people could have made better choices are listed in [the
mail](https://lists.debian.org/debian-devel-games/2014/02/msg00094.html) I
sent to the games team list last year.

Another thing I would like to highlight is the work that organisations like
[Software Freedom Conservancy](https://sfconservancy.org/) and [Software in
the Public Interest](http://www.spi-inc.org/) do to protect, defend, promote
and support FLOSS projects. It is very important work that needs our interest
and support.

**me**: _Can FLOSS world create great alternatives to Viber, Dropbox, WhatsUp, Facebook, Skype and other non-free services?_

**pabs**: I think that the FLOSS world has already created alternatives to all of those. The success of non-free services doesn't take these alternatives away but it does mean some of them are less useful because some of them are the kind of tools that become more useful with a larger amount of people using them. I don't know what it would take for the FLOSS alternatives to achieve similar success as [network effects](https://en.wikipedia.org/wiki/Network_effects) are hard to overcome. Hopefully mako is right and the [network effects are overrated](http://mako.cc/copyrighteous/why-facebooks-network-effects-are-overrated).

**me**: _Your thoughts and compare Cloud, IaaS, PaaS, SaaSS? To what should the FLOSS world pay more attention and energy?_

**pabs**: Initially I dismissed these as buzzwords and a threat to Free Software. These days I view them as potential opportunities for Free Software. Cloud-related technologies such as OpenStack and virtual machines can make private compute farm hardware more flexible and useful to their owners. IaaS providers can be used to run Debian more simply and cheaply and therefore bring Debian to more people than possible with hardware. PaaS providers can be used to run Free Software services. SaaSS can be based entirely on Free Software and respect users. Of course, just like running Free Software on hardware (proprietary or libre), cloud technology, IaaS, PaaS and SaaSS all come with downsides. The FLOSS world should aim to inform users of our software of these downsides. For example, the Debian installer could note that it is running on Intel CPUs with a proprietary BIOS and various proprietary software running, that it is running on a mobile phone with a locked bootloader, that it is running in a Xen VM on machines owned by Amazon. Free Software services could note they are running on Google App Engine etc. Free Software web browsers, chat clients etc could note when they are connecting to proprietary network services. All these notes could inform users about the downsides present in the particular situation encountered. There is also much work to be done making it easier to run Free Software on top of or use Free Software to connect to all manner of platforms from lowRISC to UEFI to VMware to Google App Engine to GitHub to Facebook. The more places Free Software can reach, the more people will be exposed to the philosophy behind it and the more potential there is for folks to join the community. While co-option of the FLOSS world is a dangerous certainty, co-option of proprietary platforms might be able to expand the reach of the philosophy behind Free Software.

**me**: _Your thoughts on Purism (the open hardware laptop initiative that got recently funded on CrowdSupply)?_

**pabs**: I don't know enough about that to comment but personally I am more interested in a laptop based on a libre CPU architecture. The [RISC-V ISA](http://riscv.org/) and the [lowRISC](http://www.lowrisc.org/) project seems to be one of the more promising possibilities at this point in time.

**me**: _Did you watch Citizenfour - comments on it?_

**pabs**: I've seen the trailer and look forward to watching it at some point, I read there might be a [screening at DebConf15](http://lists.debconf.org/lurker/thread/20150225.212330.f223038c.en.html).
