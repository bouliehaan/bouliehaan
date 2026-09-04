# jake debus

I'm an artist. Sometimes the art is open source software.
---

## samo — a self-hosted listening system

Six repos, one system, five languages. Unifies your whole music, audiobook, podcast
and radio libraries. Started as a "home hosted spotify" and became better than that.
Bit perfect playback from the server to the android DAC and into your headphones.
Right next to your podcast feed. Right next to your recently added audiobook.
Right next to your favorite playlist and radio station. Complete with the ability to
program your own custom radio station on samo-server to serve to your samo-radio.

| | |
|---|---|
| **[samo](https://github.com/bouliehaan/samo)** | the client — Android (React Native + Kotlin) and desktop (Electron), one shared core |
| **[samo-server](https://github.com/bouliehaan/samo-server)** | the backend — Go + Postgres. Music, audiobooks, podcasts and radio as first-class domains, not one stapled onto another |
| **[samo-radio](https://github.com/bouliehaan/samo-radio)** | a headless Go daemon that holds a Linux box's sound card open and plays out the aux port |
| **[samo-proxy](https://github.com/bouliehaan/samo-proxy)** | the internet-facing edge — Go, ffmpeg transcoding, artwork sizing, compression |
| **[samo-explo](https://github.com/bouliehaan/samo-explo)** | weekly ListenBrainz discovery, wired to the server |
| **[sxm-proxy](https://github.com/bouliehaan/sxm-proxy)** | a SiriusXM → Icecast bridge, in C# because upstream was |

---

## The part I spend most of my focus

Anyone can make a screen appear. Making it feel like a *physical object* is what makes
something feel good in your hand.

From `theme/choreography.ts`, on why a perfectly smooth transition can still feel cheap:

> Every entrance in this app was a rigid slab — a detail page's cover, its title, its
> buttons and its fifty track rows all started moving on the same frame, travelled the
> same distance at the same speed, and stopped together. Nothing in the physical world
> moves like that. The eye has no hierarchy to follow, so the whole screen arrives as
> one flat card rather than as an object with parts.
>
> The fix is Disney's fifth principle, follow-through and overlapping action: the heavy
> thing leads, and the light things attached to it lag, then catch up. A hand moves
> before the fingers; the cloth arrives last.

That's the work. The motion tokens, the 60fps contract, the elevation ladder, deciding
that a muted headphone jack with nothing plugged into it is *correct* and must be left
alone. Judgement calls about feel, made on purpose and written down.

---

## Also here

**[secondbrain](https://github.com/bouliehaan/secondbrain)** — a wall-mounted kiosk for
the things I'd otherwise carry in my head. Externalizes your calendar, texts, packages,
server alerts, weather, currently playing on samo-radio, everything you need to run a household.
And a couple of shell scripts from 2017, back in the
Kali days, which I'm keeping because lol

---

## Work with me

I'm open to **UX/UI engineering and product design** work — consulting or otherwise.
The useful version of me is the one deciding what a product should be and how it should
feel, then taking it far enough that you can hold it.

📍 the moon · 🏢 big jake industries
 jakedebus.art@gmail.com
