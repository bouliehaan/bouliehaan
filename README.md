# jake debus

**I make art. Sometimes the art is open source software.**

Product and design first. Code is how I get there, not why I'm here.

Before this I spent years in high-level IT and infosec. The
taste came later.

---

## samo — a self-hosted listening system

Six repos, one system, five languages. Not a portfolio piece: it's what plays music, podcasts, radio and audiobooks
in my house every day, and when I get it wrong it breaks my setup.

| | |
|---|---|
| **[samo](https://github.com/bouliehaan/samo)** | the client — Android (React Native + Kotlin) and desktop (Electron), one shared core |
| **[samo-server](https://github.com/bouliehaan/samo-server)** | the backend — Go + Postgres. Music, audiobooks, podcasts and radio as first-class domains, not one stapled onto another |
| **[samo-radio](https://github.com/bouliehaan/samo-radio)** | a headless Go daemon that holds a Linux box's sound card open and plays out the aux port |
| **[samo-proxy](https://github.com/bouliehaan/samo-proxy)** | the internet-facing edge — Go, ffmpeg transcoding, artwork sizing, compression |
| **[samo-explo](https://github.com/bouliehaan/samo-explo)** | weekly ListenBrainz discovery, wired to the server |
| **[sxm-proxy](https://github.com/bouliehaan/sxm-proxy)** | a SiriusXM → Icecast bridge, in C# because upstream was |

---

## The part I actually care about

Anyone can make a screen appear. Making it feel like an *object* is the job.

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

**The house rules, from the server README:**

- no jank
- no fake data
- no throwaway glue-server architecture
- small boring reliable pieces

---

## Also here

**[secondbrain](https://github.com/bouliehaan/secondbrain)** — a wall-mounted kiosk for
the things I'd otherwise carry in my head.
And a couple of shell scripts from 2017, back in the
Kali days, which I'm keeping because I was here.

---

## Work with me

I'm looking for **UX/UI engineering and product design** work — consulting or otherwise.
The useful version of me is the one deciding what a product should be and how it should
feel, then taking it far enough that you can hold it.

📍 the moon · 🏢 big jake industries
