---
ID: 467
post_title: 'There are a whole crapload of pre built&#8230;'
author: theojones
post_date: 2015-12-24 01:16:20
post_excerpt: ""
layout: post
permalink: https://microblog.theojones.name/?p=467
published: true
tumblr_theopjones_permalink:
  - >
    https://theopjones.tumblr.com/post/146449534292/there-are-a-whole-crapload-of-pre-built
tumblr_theopjones_id:
  - "146449534292"
---
<p>There are a whole crapload of pre-built linux-based devices with jaw-droppingly insecure default settings.</p>
<p>The favorite one I’ve seen is a slightly off brand (but still $150) NAS that one of my friends bought. It runs a variant of ARM Debian.  It by default puts both telnet and SSH services online as a default setting. And it used universal plug and play to make these services available on the open internet (without any prompting from the user required). The manual and configuration menu does not make this clear.  Or really provide any indication that anything is going on beyond the LAN. Its initial config does not force a password change. My friend got it to store music and photos on a home network and wasn’t quite the computer type. The default password was “admin” and this corresponded to an ssh accessible account with full sudo permissions of “admin”. And, of course, the NAS was as pw3d as you would guess after a week. The friend called me in to clean up the mess after his ISP forwarded him an abuse complaint from a german forum admin complaining that something on the friend’s IP address spammed his site.</p>
<p>Because it is a weird embedded device I couldn’t figure out how to de-rootkit the NAS</p>