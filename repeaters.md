# Repeaters

A **repeater** is a radio on a tall place — a tower, a
skyscraper, a hilltop — that listens on one frequency and
instantly retransmits what it hears on another, at high power
from high up. Your 5-watt handheld can't reach across the city;
the repeater hears your whisper and shouts it across the county.

This is the beginner's superpower. Most first contacts happen
through repeaters, most clubs run weekly nets on them, and
emergency traffic flows through them. Understanding three
settings — offset, tone, and simplex — covers 90% of repeater
use.

## How it works

A repeater uses **two frequencies**:

- The **input** — what the repeater listens on (what *you*
  transmit on).
- The **output** — what the repeater transmits on (what *you*
  listen on).

The gap between them is the **offset**. It's fixed by convention
per band, so you usually just set "plus" or "minus" and the
radio does the math:

| Band | Standard offset |
|---|---|
| 2 m (144–148 MHz) | ±600 kHz |
| 70 cm (420–450 MHz) | ±5 MHz |

So a 2-meter repeater with output 146.94 MHz and a *minus*
offset listens for you on 146.34 MHz. Publish a repeater as
"146.94, minus offset" and every ham knows both frequencies.

## The tone: CTCSS / PL

Many repeaters require a **sub-audible tone** — a very low
frequency hum your radio adds to your transmission, too low to
hear but the repeater listens for it. This is **CTCSS**
(Continuous Tone-Coded Squelch System), which Motorola branded
as **PL** (Private Line). Same thing.

The tone keeps the repeater from waking up for noise, distant
stations, or interference. When a repeater listing says
"146.94, minus, 103.5," that 103.5 Hz is the tone your radio
must send. Set the wrong tone (or none) and the repeater ignores
you completely — the single most common beginner problem
(see [Troubleshooting](troubleshooting.md)).

> **Check:** Find your local repeaters before you buy a radio.
> Search "repeater directory" plus your city, or check a national
> repeater database. Note each repeater's output frequency,
> offset direction, and tone — you'll program these into your
> radio on day one.

## Simplex: talking direct

**Simplex** means transmitting and receiving on the *same*
frequency — radio to radio, no repeater. Range is whatever your
antennas and terrain allow: a mile or two between handhelds,
much more from a hilltop.

Two simplex frequencies are set aside nationally as **calling
frequencies** — places to meet before moving elsewhere:

- **146.52 MHz** — the national 2 m simplex calling frequency
- **446.000 MHz** — the national 70 cm simplex calling frequency

Etiquette: call, make contact, then move off to another simplex
frequency so the calling channel stays clear. Think of it as the
lobby, not the living room.

## Nets and etiquette

A **net** is a scheduled on-air gathering on a repeater —
weekly club check-ins, weather nets, emergency drills. Joining
one is the fastest way to become part of the local community.

Repeater etiquette, the short version:

1. **Listen first.** Spend time hearing how the repeater is used
   before you transmit. Every repeater has its own culture.
2. **Keep transmissions short.** Leave pauses between
   transmissions so others (including emergency traffic) can
   break in.
3. **ID per the rule.** Callsign at the end of your contact and
   every 10 minutes (§97.119) — same as everywhere else.
4. **Don't kerchunk.** Keying the mic just to hear the repeater's
   courtesy beep, without identifying, is the classic beginner
   faux pas. If you're testing, say your callsign: "KI5ABC,
   testing."
5. **Emergency traffic has absolute priority.** If someone
   declares an emergency, clear the frequency.

> **Check:** Listen to a local repeater for a week before
> transmitting. You'll absorb the rhythm — how people call,
> how nets run check-ins, how long the pauses are — better than
> any written description.

**Next:** [Your First Radio](first-radio.md) — what to buy (and
what the categories actually mean).
