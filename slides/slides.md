---
theme: default
title: Confessions of a Distro-Hopper
info: |
  A Linux Group Session

  linuxtalk.bowmanjd.com
drawings:
  presenterOnly: true
  persist: false
selectable: true
mdc: true
transition: slide-left
class: text-center
hideInToc: true
layout: intro
duration: 40min
---

# Confessions of a Distro-Hopper

<div class="smalltux">
	<img src="/tux-outline.svg" alt="Tux">
</div>

An Invitation to Tinker

<!--

Good morning and welcome. I am Jonathan Bowman. I started using Linux in 1999. I got used to it. I think you could to. Linux is an operating system that comes in many flavors. Each flavor is simply an arrangement of configuration and applications that is commonly called a distribution, or "distro" for short. Since there are so many distributions, and they are all free, it is terribly fun to collect them all, or at least a few! Moving from one distribution to another is sometimes called "distro-hopping". When I titled this talk, my son was quick to point out, "Dad you have been using the same distro for years, you aren't really a distro-hopper." As is often the case, he is correct. But if you take my whole Linux life and compress it, I've dabbled a good bit. I suspect some of you have as well. And I suspect more of you will.
-->

---

<Toc minDepth="1" maxDepth="1" />

---

## Questions you might answer

- I was surprised to see Linux on...
- Story about installing Linux from floppy disks?
- Challenges getting Linux to install/compile?
- Smallest device you have seen Linux on?
- How did you obtain your first Linux distribution?
- Current favorite/interesting/recommended distro?
- Apps and services to host on Linux?
- Adventurous Linux (I installed Linux on my showerhead!)
- Stump the chumps (Linux problems you encounter)

<!--
I hope to have some story-telling from you during our time together. We will engage variations of each of these questions throughout; be prepared to volunteer!
-->

---
layout: section
---

# What is Linux?

<!--
Let's start with an honest and strangely tricky question... What is Linux?
-->

---
layout: image
image: /shrug.svg
backgroundSize: contain
---

<!--
The thing is... Linux is many things...
-->

---
layout: image
image: /kernel.png
backgroundSize: contain
---

<!--
At the very least, it is a system that uses the Linux kernel. The kernel of the operating system is the primary orchestrator between hardware, system processes, memory, and so on. The Linux kernel has a lot of features, supports a lot of hardware, and can be pretty small, because you can compile it to just have what you need. You might be surprised how many devices in your normal life have Linux on them. They used to joke about putting Linux on a toaster like that would be farfetched. I am sure by now there are many toasters with Linux.
-->

---
layout: fact
---

I was surprised to see Linux on...{.biggie}

<!-- Anyone seen Linux used in the wild in a surprising way? I noticed Linux on our coffee machine at work... Where have you seen it? -->

---
layout: image
image: /steam-chrome-android.svg
backgroundSize: contain
---

<!--
So Linux is definitely Linux if it has the Linux kernel on it. Funny, though. Not everyone is equally comfortable calling these 2 systems Linux, even though they have the Linux kernel at their heart. Are all of these truly Linux? A Linux purist would probably say "yes, sorta, maybe". Steam deck is legit. It is based on the Arch Linux distribution, it uses the very popular open source KDE desktop environment, it uses the open source Proton compatibility layer to run games. ChromeOS? Definitely Linux kernel, and a lot of Linuxy tools, and it even provides a terminal and exposes the innards to developers. Android? Has a linux kernel. But other than that, it does not resemble to many other distributions.

I am not a purist. These are each Linux in their own way. Fire up a terminal on a Chromebook or root an Android phone and it starts to feel pretty familiar.
-->


---
layout: image
image: /other-os.svg
backgroundSize: contain
---

<!--
So we say that Linux is *probably* Linux if it has the Linux kernel on it. Funny, though. Some of you who don't use the Linux kernel are still going to feel quite at home with at least 80% of our conversation today. These other operating systems have different kernel's but there is overlap in culture, methods, ecosystem, and vision. If you are at home with Linux and you switch to FreeBSD, you will be able to pretty quickly make yourself at home there. If you bring your own Wi-Fi adapter.
-->

---
layout: image
image: /shrug2.svg
backgroundSize: contain
---

<!--
So, where are we going here?
-->

---
layout: image
image: /in-the-beginning-was-the-command-line.jpg
backgroundSize: contain
---

<!--
To get a bit of a feel of what might attract people to Linux, what makes Linux culture unique, and how Linux culture has changed, I am going to read an excerpt from Neil Stephenson's book _In the Beginning was the Command Line_

A glimpse of what it was like when Linux first became popular... Some of this is no longer accurate or fair. Windows is not as bad as it used to be. In fact, Windows is a great way to run Linux. Mac OS feels a lot more customizable and Linux-y, but with more rounded corners.

In spite of the shiftin landscape over time, I still think you will find this entertaining and relevant.

<hr>

Imagine a crossroads where four competing auto dealerships are situated. One of
them (Microsoft) is much, much bigger than the others. It started out years ago
selling three−speed bicycles (MS−DOS); these were not perfect, but they worked,
and when they broke you could easily fix them.

There was a competing bicycle dealership next door (Apple) that one day began
selling motorized vehicles−−expensive but attractively styled cars with their
innards hermetically sealed, so that how they worked was something of a
mystery.

The big dealership responded by rushing a moped upgrade kit (the original
Windows) onto the market. This was a Rube Goldberg contraption that, when
bolted onto a three−speed bicycle, enabled it to keep up, just barely, with
Apple−cars. The users had to wear goggles and were always picking bugs out of
their teeth while Apple owners sped along in hermetically sealed comfort,
sneering out the windows. But the Micro−mopeds were cheap, and easy to fix
compared with the Apple−cars, and their market share waxed.

Eventually the big dealership came out with a full−fledged car: a colossal
station wagon (Windows 95). It had all the aesthetic appeal of a Soviet worker
housing block, it leaked oil and blew gaskets, and it was an enormous success.
A little later, they also came out with a hulking off−road vehicle intended for
industrial users (Windows NT) which was no more beautiful than the station
wagon, and only a little more reliable.

Since then there has been a lot of noise and shouting, but little has changed.
The smaller dealership continues to sell sleek Euro−styled sedans and to spend
a lot of money on advertising campaigns. They have had GOING OUT OF BUSINESS!
signs taped up in their windows for so long that they have gotten all yellow
and curly. The big one keeps making bigger and bigger station wagons and ORVs.

On the other side of the road are two competitors that have come along more
recently.

One of them (Be, Inc.) is selling fully operational Batmobiles (the BeOS). They
are more beautiful and stylish even than the Euro−sedans, better designed, more
technologically advanced, and at least as reliable as anything else on the
market−−and yet cheaper than the others.

With one exception, that is: Linux, which is right next door, and which is not
a business at all. It's a bunch of RVs, yurts, tepees, and geodesic domes set
up in a field and organized by consensus. The people who live there are making
tanks. These are not old−fashioned, cast−iron Soviet tanks; these are more like
the M1 tanks of the U.S. Army, made of space−age materials and jammed with
sophisticated technology from one end to the other. But they are better than
Army tanks. They've been modified in such a way that they never, ever break
down, are light and maneuverable enough to use on ordinary streets, and use no
more fuel than a subcompact car. These tanks are being cranked out, on the
spot, at a terrific pace, and a vast number of them are lined up along the edge
of the road with keys in the ignition. Anyone who wants can simply climb into
one and drive it away for free.

Customers come to this crossroads in throngs, day and night. Ninety percent of
them go straight to the biggest dealership and buy station wagons or off−road
vehicles. They do not even look at the other dealerships.

Of the remaining ten percent, most go and buy a sleek Euro−sedan, pausing only
to turn up their noses at the philistines going to buy the station wagons and
ORVs. If they even notice the people on the opposite side of the road, selling
the cheaper, technically superior vehicles, these customers deride them cranks
and half−wits.

The Batmobile outlet sells a few vehicles to the occasional car nut who wants a
second vehicle to go with his station wagon, but seems to accept, at least for
now, that it's a fringe player.

The group giving away the free tanks only stays alive because it is staffed by
volunteers, who are lined up at the edge of the street with bullhorns, trying
to draw customers' attention to this incredible situation. A typical
conversation goes something like this:

Hacker with bullhorn: "Save your money! Accept one of our free tanks! It is
invulnerable, and can drive across rocks and swamps at ninety miles an hour
while getting a hundred miles to the gallon!"

Prospective station wagon buyer: "I know what you say is true...but...er...I
don't know how to maintain a tank!"

Bullhorn: "You don't know how to maintain a station wagon either!"

Buyer: "But this dealership has mechanics on staff. If something goes wrong
with my station wagon, I can take a day off work, bring it here, and pay them
to work on it while I sit in the waiting room for hours, listening to elevator
music."

Bullhorn: "But if you accept one of our free tanks we will send volunteers to
your house to fix it for free while you sleep!"

Buyer: "Stay away from my house, you freak!"

Bullhorn: "But..."

Buyer: "Can't you see that everyone is buying station wagons?"
-->

---
layout: image
image: /c64.gif
backgroundSize: contain
---

<!--
This is not Linux, but it primed me for Linux. The K-Mart in E-town had a computer department. This is where my brother and I went while the rest of the family shopped. And this is what was there. An open keyboard and a blinking cursor. And a few books on a shelf. Eventually the C64 and one of the books showed up under the tree at Christmas and we had this open keyboard and blinking cursor in our living room -- this invitation to build, because there was nothing else to do with it. I spent years with that machine, learning to program in Basic, LOGO, Assembly...
-->

---
layout: image
image: /tux.svg
backgroundSize: contain
class: bg-sky-800:40
---

<!--
Fast forward to 1999. Someone told me about Linux. I was an English major, and it had been some time since I'd taken a look at the innards of any operating system, but I have always found sustainable, cost-effective technology fascinating, and this sounded very sustainable. So I dove in. It was like the old blinking cursor on the Commodore, but so much better. Because we had the Internet, I was older and smarter, and things that cost money at K-Mart were now free to download and use. Or order from reputable web storefronts.
-->

---
layout: quote
---

random post from alt.os.linux, Sep 2, 1998, 3am

> I tryed cheapbytes.com, and find linux redhat version 5.1 for $ 2.00 ....<br>
> How can it be so cheap ????<br>
> Is this really reliable ???<br>
><br>
> Thx to responces ...

---
layout: fact
---

Ever installed Linux from floppies?{.biggie}

---
layout: image
image: /tools.svg
backgroundSize: contain
---

<!--
For me, the thing about Linux is the tinkering. The invitation to tinker. Tools can shape us, so we should ask what shape we want to be in, and then feel free to choose tools that shape us in that way. I want to be a tinkerer, and I like to be with tinkerers, because there is already so much consumption and I find creation to be a refreshing counterpoint to that, and because there is so much to discover in the big and the small parts of the universe so why not pause and dig in and inspect and reflect rather than just use and be used, and because I think to serve each other well with kindness and care requires ingenuity and resourcefulness. I want to be someone who makes old and broken things work again, and maybe even invents or adapts new tools and toys, after taking them apart of course. In fact, I hope that all of us could become a little more tinkering. And Linux, like other open, malleable tools, invites us to be that. Tinkerers.
-->

---
layout: image
image: /redhat52.png
backgroundSize: contain
---

<!--
It started with the Redhat 5.2 default desktop. A little Clunky
-->

---
layout: image
image: /mandrake.png
backgroundSize: contain
---

<!--
I soon switched distributions to Mandrake 5.3. This was Redhat 5.2 mixed with the rather new KDE desktop environment.
-->

---
layout: image
image: /distrobox.png
backgroundSize: contain
---

<!--
And here we are today, running NixOS and others. In between was a couple years with Debian. Debian sid, of course, or derivatives of Debian, like Crunchbang. And Ubuntu. Then Arch (maybe a little Yellowdog Linux in there at some point). A lot of Arch. Then Fedora. Fedora lasted a good long time. And now NixOS, mixed with some Alpine on occasion. My son just installed Asahi Linux a week ago, and that is interesting for sure.
-->

---
layout: fact
---

Challenges getting Linux to install/recompile?{.biggie}

<!--
Anyone have a story about waiting forever for Gentoo to compile, or accidentally wiping out a partition, or other challenges dramatic or mundane with installing Linux?
-->

---
layout: image
image: /daily-driver.svg
backgroundSize: contain
---

<!--
An opportunity, a consideration: make Linux your daily driver for a season. And lean in to the tinkering. In my early experience with Linux, I remember the untethered feeling when I stopped dual booting Linux and Windows, and just went whole hog Linux. If there was a gap, like missing fonts or slow video acceleration, or poor Wi-Fi performance, I had to get my hands dirty in Linux and figure it out. Or when I did the same at one workplace years later. With a Linux laptop, I had to figure out an easy way to enter a meeting room, plug in my laptop, and have the monitors work at the correct resolution. And that's when I learned about Wayland, and dropped X. The outcome every time is that I learned not one skill but many, frankly marketable skills, from that one simple choice.
-->

---
layout: section
---

# Minimalism

---
layout: image
image: /home-is-where.png
backgroundSize: contain
---

<!--
Not a big fan of generated images in presentations, but isn't it cute -- all I prompted was "Home is where my web browser and terminal are" and out came a picture of me. See the little Tux picture? So adorable. But the real point is -- if you are someone who thinks that you don't actually need that much stuff on your computer, Linux allows you to go minimalist to an unusually high degree.
-->

---
layout: image
image: /minimal.png
backgroundSize: contain
---

<!--
Here is my desktop. One of the appealing things about Linux for me is you can remove everything you don't need.
-->

---
layout: image
image: /minimal2.png
backgroundSize: contain
---

<!--
Where your browser and your terminal are...
-->

---
layout: image
image: /4panes.png
backgroundSize: contain
---

<!--
Just focus on as many things as you want to do but little else.
-->

---
layout: two-cols
---

```
/data/
/data/.config/
/data/.config/rustdesk/
/data/.config/rustdesk/RustDesk.toml
/data/db_v2.sqlite3
/data/db_v2.sqlite3-shm
/data/db_v2.sqlite3-wal
/data/id_ed25519
/data/id_ed25519.pub
/dev/
/etc/
/etc/group
/etc/hostname
```

::right::

```
/etc/hosts
/etc/mtab
/etc/passwd
/etc/resolv.conf
/proc/
/run/
/run/.containerenv
/sys/
/usr/
/usr/bin/
/usr/bin/hbbr
/usr/bin/hbbs
```

<!--
Minimalism can take on many forms: here is the contents of a Linux container, a full OS (other than the kernel and accoutrements) in 15 files and a few directories. The is the Rustdesk proxy so that I can connect, screenshare, and control my parents' computers.
-->

---
layout: fact
---

Smallest device you have seen Linux on?{.biggie}

<!--
Speaking of minimalism...
-->

---
layout: section
---

# Where to get Linux? Which distro? Where to put it?

<!-- how do you obtain Linux and then where do you put it? -->

---
layout: image-left
image: /linuxfloppy.jpg
backgroundSize: contain
---

## Obtaining

- Borrow it
- Download it
- May already have it

<!-- If you don't have great Internet, find someone who does, or download it, or just launch it. Chromebooks have it already, Windows Subsystem for Linux (WSL) will download and guide you through configuration. -->

---
layout: fact
---

How did you obtain your first Linux distribution?{.biggie}

---
layout: image
image: /fedoradownload.png
backgroundSize: contain
---

<!--
Find your distro of choice, go to their web page, learn how to install it
-->

---

Which distro?{.biggie}

---
layout: image
image: /fedora1.svg
backgroundSize: contain
---

<!--
There are...
-->

---
layout: image
image: /fedora2.svg
backgroundSize: contain
---

<!--
so many...
-->

---
layout: image
image: /fedora3.svg
backgroundSize: contain
---

<!--
good options...
-->

---
layout: image
image: /fedora4.svg
backgroundSize: contain
---

<!--
Explore and experiment...
-->

---
layout: image
image: /fedora5.svg
backgroundSize: contain
---

<!--
And you
-->

---
layout: image
image: /fedora6.svg
backgroundSize: contain
---

<!--
will surely
-->

---
layout: image
image: /fedora7.svg
backgroundSize: contain
---

<!--
choose well
-->

---
layout: image
image: /choose-linux-infographic.jpg
backgroundSize: contain
---

<!--
Found this. A little dated, but not too bad. Let's follow the Linux track...
-->

---
layout: image
image: /nixos.svg
backgroundSize: contain
---

<!--
By the way. I use Nix. By the way.
-->

---
layout: fact
---

Shout-out to a distro of your choice?{.biggie}

---

Where do I put it?{.biggie}

---
layout: image
image: /se30.jpg
backgroundSize: contain
---

<!--
Linux is great for old computers you have lying around, or you can help your friends de-clutter by taking their trash.
-->

---
layout: image
image: /raspberry-pi.jpg
backgroundSize: contain
---

<!--
You can buy a new computer for Linux
-->

---
layout: image
image: /asahi.svg
backgroundSize: contain
---

<!--
Yes, Linux will work great on your Macbook or Mini.
-->

---
layout: two-cols
---

## Virtualization on Mac

- UTM
- Lima

## Virtualization on Windows

- WSL
- Hyper-V

::right::

## Virtualization on Linux

- Distrobox
- Virt-manager

<!--
Virtualization and/or containers provide a great way to "wade in" -- you keep your existing OS as is, and then you launch Linux inside of it. But I hope you might consider making Linux your daily driver. On a Mac, UTM is a great free vm management tool. Lima is as well, and behaves more like WSL. Speaking of which, that is Windows Subsystem for Linux -- the best way to run Linux on Windows. It is fast, easy, and has official support from several distros. On Linux, I really love playing around with distrobox -- fast and lightweight because it uses containers, not VMs.
-->

---
layout: image
image: /proxmox.svg
backgroundSize: contain
---

<!--
If you have a machine with some decent hard drive space and RAM, you may find that proxmox offers a powerful and convenient way to host and experiment.
-->

---
layout: image
image: /proxmox.png
backgroundSize: contain
---

<!--
 This is our proxmox that lives in our basement. You can spin up and configure VMs or persistent containers easily. You can connect to them remotely, even with a full graphical user interface.
-->

---

## Containers

docker, podman, nerdctl, colima, rancher...

- [hub.docker.com](https://hub.docker.com/)
- [GitHub](https://github.com/search?type=registrypackages)

![Podman](/podman.svg)

<!--
I have mentioned containers many times. Docker and its successors run a mini Linux OS (or many!) and typically a single container provides one tool or service, but they provide a great way to dice and slice Linux
-->

---
layout: section
---

# What apps/services are good to use on Linux?

---

## The Usual

- Firefox, Chromium, Chrome, Brave, Edge
- So. Many. Terminals.
- Inkscape, Gimp, Krita, Blender
- OBS Studio, VLC, Haruna, Audacity
- Steam, Aisleriot, Colossal Cave Adventure
- Calibre
- OpenOffice
- Many more

---

## The Unique

- Waydroid

---

## Command Line apps

All of them are awesome on Linux

---
layout: two-cols
---

## Self-hosting

- Web servers: Nginx, Caddy
- Proxmox, Komodo, Portainer, Cockpit
- Password manager: Vaultwarden
- VPN (Wireguard, Tailscale, Nebula)
- Jellyfin
- Immich

::right::

- Nextcloud
- Home Assistant
- Karakeep (previously Hoarder)
- Open WebUI, Librechat
- llama.cpp, Ollama, vLLM

---
layout: section
---

# Off-the-beaten-path Linux

---
layout: image
image: /openwrt.svg
backgroundSize: contain
---

<!--
OpenWrt is best known as a custom router firmware you can flash to your aging Wi-Fi access point. But it is also a full-fledged Linux distro, just more compact, with a strong leaning to network usage. You can make a travel router for hotel or AirBnB, a whole house web filter, a VPN tunnel, captive portal, file server, security camera...
-->

---
layout: image
image: /buildroot1.png
backgroundSize: contain
---

<!--
Years ago I had an old white iBook with some problems. It couldn't get too hot, it didn't have much RAM. And I went down a deep rabbit hole with buildroot, building my own very tiny Linux distro that could run a few things on it. Buildroot let's you choose features and packages from a menu, and then it builds everything, kernel, initial ramdisk, and the filesystem.
-->

---
layout: image
image: /openembedded-yocto.svg
backgroundSize: contain
---

<!--
With a similar goal but so many more features and much more flexibility is the Yocto project, built on the OpenEmbedded. These are build frameworks. They aren't Linux distributions; they *make* Linux distrubtions that can be exceedingly small if desired. I may have tried, with 40% success, to get Linux onto an old Palm PDA once upon a time. It booted, but was not usable. Maybe if I had tried harder.
-->

---
layout: image
image: /linux-from-scratch.png
backgroundSize: contain
class: bg-white:70
---

<!--
If the "rolling your own" idea appeals, hands down the best way to get into the weeds is the Linux From Scratch project. The focus is on learning, minimalism, and a whole lot of compiling.
-->

---
layout: fact
---

Linux Adventures?{.biggie}

---
layout: center
---

![Amish Tux](/llug.png)

Lancaster Linux User Group, every third Thursday, 7pm

---
layout: fact
---

Linux Questions?{.biggie}

