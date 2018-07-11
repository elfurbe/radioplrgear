[Mixers](mixers.md) | [Interfaces](interfaces.md) | [Mics](microphones.md) | [Headphones](headphones.md) | [Software](software.md)
# Software

There are a lot, like _A LOT_, of ways to solve the problem of broadcastings your sounds to the icecasts. This will hardly be an exhaustive study of all of them, but one or more of these applications will allow you to Do The Needful and play music for people. There are essentially two things you'll need to sort out here.

Stage one is capturing and potentially mixing audio noises from various computer sources to produce the output you'll stream. Primarily this is a thing you'll do if you aren't using a big swingin' [mixer](mixers.md) and are instead doing the sane thing and just using a USB audio [interface](interfaces.md) or USB [microphone](microphones.md#usb). You'll need to be able to route the sound from your music playout application (Spotify or iTunes or whatever) and your microphone input into your broadcast application. Typically this requires some juju to sneaky snake audio away from the system sound service _before_ it tries to render it on the DAC and redirect that stream somewhere else. Most applications that do this play shadow games with the system by creating pretend audio interfaces that don't _really_ exist but the system _thinks_ exist. It sounds kind of complicated but it really isn't that big a deal.

Stage two is broadcasting your terrible musical taste for everyone to judge. This is comparatively easier, you take a stream of audio and encode it to mp3 and ship that stream of bits to a place on the internet.

There also exist combination packages that do both of these things.

Oh, also. There are, of course, different packages for Mac and Windows. I will not be covering Linux here, sort yourself out if you're this person. I have no sympathy for you.

## All-in-One

#### Mac

##### Rogue Amoeba Audio Hijack ($60)

[Product Page](https://rogueamoeba.com/audiohijack/)

Rogue Amoeba makes a lot of assorted audio software, Audio Hijack is one of their most venerable packages. Truly the go anywhere do anything of Mac audio routing, they recently updated it with the ability to play out directly to an icecast server so it is now a one-stop shop for Macs. It is very graphical and generally intuitive. You set up chains of blocks that move sound from left to right. As is Rogue Amoeba's way, it is well designed and descriptive. It's likely you won't need any direction at all to get this up and running.

ElFurbe Says: Rogue Amoeba used to offer a dedicated single-bladed tool called Nicecast for doing this, but they've killed it off and rolled the functionality into Audio Hijack, so this is now the correct way to solve this problem on a Mac. There are other ways, but I'm not going to talk about them. They're all more complicated and less forgiving and more prone to difficult to diagnose misbehavior. Buy this. I know I keep suggesting things that cost money in every category but free things that do these tasks are more trouble than I think they save you in money, so I'm not going into them.

#### PC

I don't use a PC for this, so I have no idea if there are AIO packages for this.


## Audio Routing

#### Mac

Audio Hijack does this and the other thing. There aren't better options piecemeal. Audio Hijack is what you want.

#### PC

##### VB-Audio Voicemeeter Banana (Free/Donationware)

[Product Page](https://www.vb-audio.com/Voicemeeter/banana.htm)

ElFurbe Says: I don't really know much about this, I just know it's a thing people use. I'll try to get someone to write this up.


## Audio Broadcasting

#### Mac

Audio Hijack does this and the other thing. There aren't better options piecemeal. Audio Hijack is what you want.

#### PC

##### Broadcast Using This Tool aka BUTT (Free)

[Product Page](https://sourceforge.net/projects/butt/)

ElFurbe Says: This software is simple and it will take an input and broadcast it to an output. Also free so it's got that going for it, which is nice.

