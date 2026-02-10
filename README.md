## Hello everyone!

For those who do not know me I will tell you a bit of my story.
I'm a programming enthusiast who has spent some of his little free time in recent years contributing to the ps4 scene.

### [pkg2usb](https://github.com/SiSTR0/ps4-pkg2usb)

I started with a POC on how to use [symbolic links](https://en.wikipedia.org/wiki/Symbolic_link) to link pkg on external hard drives. I named the payload pkg2usb, [CelesteBlue](https://github.com/CelesteBlue-dev) kindly posted the source code on his [git](https://github.com/CelesteBlue-dev/ps4-pkg2usb). 
With great pleasure [stooged](https://github.com/stooged) was inspired by my work to create something more complete with his [AppToUSB](https://www.psxhax.com/threads/apptousb-by-stooged-a-modification-of-pkg2usb-for-ps4.4704/).

### [ps4-hen-vtx](https://github.com/SiSTR0/ps4-hen-vtx)

When I switched to fw 5.05 from 4.05 I immediately noticed a serious lack in the HEN designed by [flatz](https://github.com/flatz) and implemented by [xvortex](https://github.com/xvortex), namely the lack of rest mode support. flatz gave some tricks to solve the problem, but it wasn't enough, so I dedicated some time to fix and improve it on the [HEN 2.x](https://github.com/SiSTR0/ps4-hen-vtx/commits/master) versions.

### [ps4ren](https://github.com/SiSTR0/ps4ren)

Another lack I had encountered was the activation of the [remote play](https://en.wikipedia.org/wiki/Remote_Play) on not activated ps4.
Even this new challenge takes me some time to study the registration process of the various devices until I also found a couple of solutions there. First one was to simulate on the fly the IDU mode that bypasses the check on the activation of the ps4. It worked, but it was not optimal because it brought with it some problems of the IDU mode such as the deactivation of the start button. I studied a better way to enable remote play and so [ps4ren v2.0](https://github.com/SiSTR0/ps4ren/releases/tag/2.0.0) was born. It was also integrated into [HEN v2.1.3](https://github.com/SiSTR0/ps4-hen-vtx/releases/tag/2.1.3).
After some time [Al-Azif](https://github.com/Al-Azif) added my solution on [mira](https://github.com/OpenOrbis/mira-project/commit/211745632b4fad1b5a510665ff440eb9eb9a312b).

### [mira](https://github.com/OpenOrbis/mira-project)

Given my experience with HEN, [kiwidog](https://github.com/kiwidoggie) asked for my help to integrate HEN on mira for the first time, and we succeeded :trophy:

### [jkpatch](https://github.com/ChendoChap/jkpatch)

I often collaborate with other ps4 devs like [ChendoChap](https://github.com/ChendoChap) with whom we have added [rest mode](https://github.com/ChendoChap/jkpatch/commit/0393c855867b4e8a39fd73c98bd802483a639487) support on [jkpatch](https://github.com/ChendoChap/jkpatch), father of [ps4debug](https://github.com/jogolden/ps4debug) by [golden](https://github.com/jogolden).

### [GoldHEN](https://github.com/GoldHEN)

Lately I have concentrated all my experiences to design and implement a new HEN, GoldHEN, which tries to solve some of the various problems born especially in the latest firmware. After some people requests, I integrated a persistent [FTP](https://github.com/xvortex/ps4-ftp-vtx) to HEN.
The project is currently private because over time I have seen a sad abuse of the source code that I, like the previous devs who worked on it, have been pleased to make it available to everyone to study and maybe improve it.

### Mono Injection

Another interest of mine was to modify the Shell UI and so I started a working POC about how to inject code inside [Mono](https://www.mono-project.com/). Due to the short time I could devote to the project, I passed this on to some other interested devs of the scene such as [Znullptr](https://github.com/dmiller423) and [Seremo](https://github.com/seremo), the latter with great skill managed to make great progress but unfortunately still private at the moment.
With great pleasure, perhaps stimulated by my little POC inside GoldHEN, [OSM](https://github.com/OSM-Made) created an interesting open source project called [Orbis Toolbox](https://github.com/OSM-Made/Orbis-Toolbox). 
He also wrote some excellent [writeups](https://web.archive.org/web/20210709222729/https://www.hackingadventures.ca/blog/ps4-mono-ui-part-2) that I invite you to read (thanks for quote [me](https://web.archive.org/web/20210709222729/https://www.hackingadventures.ca/blog/ps4-mono-ui-part-2#block-yui_3_17_2_1_1625803114290_4093) :wink: )

I haven't stopped my passion to go on and in my little free time I am adding other interesting and useful features on GoldHEN, so stay tune!

### Donations

If you like my works and want to support me :smiley:

* [Ko-fi](https://ko-fi.com/SiSTRo)
* [Buy Me a Coffee](https://buymeacoffee.com/SiSTRo)
* [GitHub Sponsorship](https://github.com/sponsors/SiSTR0)
* [Alipay](https://goldhen.github.io/resources/alipay.jpg)
