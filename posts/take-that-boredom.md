<!-- 
.. title: Take that boredom
.. slug: take-that-boredom
.. date: 2016-08-24 07:45:02 UTC+02:00
.. tags: debian, blog, tor, nginx
.. category: 
.. link: 
.. description: 
.. type: text
-->

While I was bored on Defcon, I took the smallest VPS in DO offering (512MB RAM, 20GB disk), configured nginx on it, bought domain zlatan.tech and cp'ed my blog data to blog.zlatan.tech. I thought it will just be out of boredom and tear it apart in a day or two but it is still there.

Not only that, the droplet came with Debian 8.5 but I just added unstable and experimental to it and upgraded. Just to experiment and see what time will I need to break it. To make it even more adventurous (and also force me to not take it too much serious, at least at this point) I did something on what Lars would scream - I did not enable backups!

While having fun with it I added letsencrypt certificate to it (wow, that was quite easy).

Then I installed and configured Tor. Ende up adding an .onion domain for it! It is: pvgbzphm622hv4bo.onion

My main blog is still going to be zgrimshell.github.io (for now at least) where I push my Nikola (static site generator written in python) generated content as git commits. To my other two domains (on my server) I just rsync the content now. Simple and efficient.

I must admit I like my blog layout. It is simple, easy to read, efficient and fast, I don't bother with comments and writing a blog in markdown (inside terminal as all good behaving hacker citizen) while compiling it with Nikola is breeze (and yes, I did choose Nikola because of Nikola Tesla and python). Also I must admit that nginx is pretty nice webserver, no need to explain the beauty of git but I can't recommend enough of rsync.

If anyone is interested in doing the same I am happy to talk about it but these tools are really simple (as I enjoy simple things and by simple I mean small tools, no complicated configs and easy execution).
