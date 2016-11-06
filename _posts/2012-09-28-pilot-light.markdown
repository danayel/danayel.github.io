---
layout: post
title:  "Pilot Light"
date:   2012-09-28 00:00:00 +0900
categories: linux-foundation comics
---

![{{ page.title }}]({{ site.comicsurl }}50-PilotLight.jpg)

This comic originally appeared on [linux.com](https://www.linux.com) and was sponsored by [The Linux Foundation](https://www.linuxfoundation.org/).


Another true story for you today.

I am looking for some more stories to make into comics so if you have a good one please send it to editors[at]linux[dot]com. I can't promise to make them all into comics, but I will see what I can do.

The story behind the comic, courtsey of Tykeal:

>I was working for a decently well along startup and it was my turn on
pager duty when I got pulled out of sleep early one Saturday morning at
the start of a 3-day weekend by my pager. We're talking 02:30 early
here.
>
>The reason for my pager doing the tango off my night stand happened to
be one of our primary file servers for our website had just fallen off
the network. No ping, nothing from the remote console server. Seemed
dead as a door nail.
>
>Now at this point in time our infrastructure wasn't robust enough to
just let this lie around till the start of the work week, I needed to
find out what was really wrong as at this point 1/3 of all of our
picture data wasn't available to our customers.
>
>So here I am, the nearest to the colo (drat, can't pawn this off to
someone else) but the colo is 30 minutes away from (well that's
annoying) and I can't remote toggle the power to it as we don't have
remotable PDUs. Guess I'm heading into the colo.
>
>When I finally get there the server is still offline, I could hope that
it would come back all on its own but I'm not that lucky apparently. I
reverify that I've got no console, find it isn't taking the power button
command at the faceplate for a forced poweroff / poweron (yes it's
currently "running") and decide to yank the power cords and then plug it
back in.
>
>This is when I notice a rather faint and new smell along with a
flickering blue light coming out of one of the exhaust ports on the
system. Now, mind you this is before all those blue LEDs started showing
up on systems so I shouldn't be seeing any blue coming out of my
machine, especially not flickering blue or with the smell of burnt
electronics. So I hunker down close to the back of the system and peer
in and to my amazement I saw a little blue flame dancing around in my
server, to which I made the silly statement to nobody (since I was alone
there) "servers shouldn't have pilot lights!" and promptly pulled the
power plugs watching as my pilot light went out.
>
>Unfortunately the system in question wasn't under any kind of 4 hour
turn around warranty and we couldn't get any service on it till the next
business day (2 days away) but when we did what we found was that one of
our capacitors on the motherboard had died.
