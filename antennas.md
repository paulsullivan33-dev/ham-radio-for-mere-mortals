# Antennas

The old saying in the hobby: **a $50 radio with a $200 antenna
outperforms a $200 radio with a $50 antenna.** Antennas are where
beginners get the most improvement per dollar — and where the
real safety hazards live. Both halves matter.

## The idea

An antenna converts electrical signals into radio waves (and
back). Its size relates to wavelength: efficient antennas are
typically a half or quarter wavelength long. That's why HF
antennas are big (a 40-meter dipole is ~66 feet) and UHF
antennas are small (a 70-cm whip is inches).

**Height and clear surroundings beat almost everything else.**
An antenna in the clear hears and reaches dramatically farther
than the same antenna behind obstacles.

## The dipole: the simplest real antenna

A **dipole** is two wires, end to end, fed in the middle — total
length about a half wavelength for the band you want. Hung
horizontally between two supports, fed with coaxial cable, it
just works. Hams have talked around the world on dipoles made
from hardware-store wire.

You don't need to build one today. But knowing the dipole exists
matters because: (a) it's the reference everything else is
compared to, (b) it's cheap enough to be your first HF antenna,
and (c) understanding it demystifies every fancier antenna
you'll meet later.

## SWR: what it means and why it matters

**SWR** (Standing Wave Ratio) measures how well your antenna
system accepts power from the radio. Think of it as a match
score between the radio and the antenna:

- **1:1 is perfect.** All power goes out the antenna.
- **1.5:1 is fine.** Normal, healthy.
- **2:1 is the practical limit** for most radios without a
  tuner. Above this, modern radios automatically reduce power
  to protect themselves ("foldback").
- **3:1 and up is a problem.** Significant power reflects back
  toward the radio as heat. Sustained transmitting into very
  high SWR can damage the final amplifier transistors.

High SWR usually means something is wrong: a broken connection,
the wrong antenna for the frequency, a damaged feedline, or
metal objects too close to the antenna. An **SWR meter** (or the
built-in meter on many radios) tells you the number; fixing it
is a matter of checking connections and antenna length
(see [Troubleshooting](troubleshooting.md)).

An **antenna tuner** doesn't fix the antenna — it tricks the
radio into seeing a good match. Useful, but a resonant antenna
(always low SWR by design) is better than a tuner compensating
for a bad one.

## Antenna safety — stated plainly

> **Safety:** Antennas involve real hazards. Take these
> seriously.
>
> - **Lightning.** An outdoor antenna is a lightning target.
>   Disconnect feedlines from your radios when storms approach,
>   and ground your antenna system. No grounding scheme makes a
>   direct strike harmless — disconnection is the protection.
> - **Falling.** Tower and rooftop work kills people. Climbing
>   is a specialized skill with specialized safety gear. If an
>   antenna needs to go somewhere you can't safely reach from
>   the ground or a stable ladder, hire someone or choose a
>   different antenna.
> - **RF exposure.** The FCC requires stations to evaluate RF
>   exposure (47 CFR §97.13(c)). At typical beginner power
>   levels with normal antennas, you're fine — the rule matters
>   when you run high power near people. Keep antennas away
>   from where people linger, and re-evaluate if you add an
>   amplifier.
> - **Power lines.** Never put an antenna where it could fall
>   onto power lines — during installation, in wind, or in ice.
>   If it can touch a line when it falls, it's too close.

> **Check:** If your radio has a built-in SWR meter, check the
> SWR on each band you use, at low power, and write the numbers
> down. That baseline tells you instantly when something
> changes — a sudden jump in SWR means something broke.

**Next:** [Digital Modes](digital-modes.md) — talking with
computer help.
