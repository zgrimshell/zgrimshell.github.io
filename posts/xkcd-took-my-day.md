<!-- 
.. title: xkcd took my day
.. slug: xkcd-took-my-day
.. date: 2015-02-01 21:52:47 UTC+02:00
.. tags: xkcd, scripts
.. link: 
.. description: 
.. type: text
-->

Yep, thank you xkcd for love and thank you brain for being pain in the ass. I
decided to download all xkcd images and then watch them in slideshow. You
wouldn't believe that getting all images from xkcd is not an easy job. At
least not for begginer as me. And especially not if you just start to search
where are all the images.

<!-- TEASER_END -->

So after hour or two of research I wrote a big python script. I was not happy
because I like to make scripts as small (in number of lines) as possible. Then
I rewrote it. Of course using JSON. The I rewrote it again. After 6-7 rewrotes
I was happy. About 50 lines. Awesome. Now just to make it open and slide
randomly. That became a real pain in the ass for me. I did ended somehow doing
that but file became very big. And I ended with two files (probably could do
one but, you know, brain). And I was so tired that I became afraid how to
automate that. So I wrote shell script. Now I have shell script that executes
python scripts. I am not happy. Big files, shell script, python script. Looks
like a mess to me. So I start rewriting everything in Bash. I wrote first
time. Too big. Second time, not that big but complicated. Then I rewrote it in
Perl. Then I came back to Bash. And after rewriting it for 10th time I ended
up with this (notice that here I didn't specify directory where it downloads
all images so make your own and copy there this script):

    
    
    #!/bin/bash
    for i in seq `1 1453`
    do
    wget http://xkcd.com/$i/
    wget `grep http://imgs.xkcd.com/comics/ index.html | head -1 | cut -    d\" -f2`
    convert -append $(ls -t | tail -n 1) $i.jpg $i.png
    rm index.html
    rm *.jpg
    rm *.png
    done
    feh -z -D 10
    

And I was a bit happy. It did what I need. There can be some improvements. I
made a debian package. I wish I didn't. So I decided it was enough. I lost
like many hours. Too many.

But now I got another idea - why not learn node-webkit and create a desktop
app?! Yep, I am probably brain damaged. Who knows, lets see tomorrow.
