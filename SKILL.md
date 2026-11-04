---
name: video-script
description: Write scripts for short vertical videos (TikTok, Instagram Reels, YouTube Shorts) built to hold viewers to the end (hook, beats, payoff, loop), as spoken lines only. Use when asked for a short-form script, hooks, a reel/TikTok/Short idea turned into words, or to rewrite a script that sounds generic or AI-written.
---

# Video Script

The viewer's thumb is already moving. Every line either earns the next second or loses the video. All three platforms rank on the same thing: how many people stay past the first seconds and how much of the video they watch (TikTok: completion and rewatches; Reels: skips in the first 3 s, then watch time and sends; Shorts: average % viewed). A script is written for that, not for reading.

Write in the person's language and the way their audience talks (Spanish: their country's Spanish, not neutral textbook Spanish).

## Before writing

Criterio lives in a private git repo, so every machine and cloud session shares one copy. Find `criterio.md`:
1. `~/.video-script-skill/criterio.md` (local clone).
2. Otherwise, the attached criterio repo in this session (cloud sessions clone every attached repo).
3. Neither: create `~/.video-script-skill/criterio.md` as in [Criterio](#criterio) (local only, not synced).

If found in `~/.video-script-skill/`, `git pull --rebase` there before reading (cloud clones are already fresh). Read it and follow it: **Innegociable** always; **Preferencias** by default; **A confirmar** too, so they get tested, unless they clash with something above them.

If you changed it and its folder is a git repo, in that folder: `git add criterio.md && git commit -m "criterio: <what changed>" && git pull --rebase && git push`.

Get, or assume and state in one line: **topic**, **platform**, **max length** (only if given), **format** (talking head, voice-over, skit), **goal** (follows, comments, a click, a sale), **who's watching**. Defaults: as short as the idea allows, talking head, goal = watch to the end.

**One video, one idea.** If you need "and" to say what it is about, it's two videos. Find the one specific thing the viewer gets at the end (a number, a trick, a reveal, a punchline) — the payoff. Write the payoff first, then the hook that promises it.

**Shorter is better.** Length is a result, not a target: write the idea, then cut until nothing more can go without breaking the payoff. Every extra word costs viewers. If there is a max length, cut ideas, not words from a line.

## Structure

| Beat | Job |
| --- | --- |
| **Hook** | Stop the thumb with the first line. |
| **Stakes** | Why this viewer should care, and a promise of what's coming. No backstory. |
| **Beats** | Something new in every line. Each beat opens a small question the next one answers. |
| **Re-hook** | Around the 60% mark of the lines: a turn ("but that's not the weird part"), a twist, a second open loop. Where the curve sags. |
| **Payoff** | Deliver exactly what the hook promised, with the most specific detail. |
| **Out** | Stop right after the payoff, or end on a line that flows back into the first (loop). CTA only if the goal needs one, and only one. |

**The hook is the first spoken line:** ≤12 words, the first word already in the topic. Specific: a number, a name, a place, a price, an object.

**Hook patterns** (pick by topic, then make it specific — the pattern is not the hook):
- Result first: "This $12 part fixed a car three mechanics gave up on."
- Callout: "If you've ever lost a game because of lag, watch this."
- Wrong belief: "You've been charging your phone wrong, and it's costing you a year of battery."
- Mid-story: "So the landlord walks in, sees the wall, and goes silent."
- Countdown/test: "I tried every cheap mic under $30. One is actually good."

Kill on sight: "Hey guys", "In this video…", "Did you know…?" with nothing specific after it, "Let me tell you", any intro before the first piece of value.

**Open loops:** one big one from the hook, closed only at the payoff; small ones beat to beat. One or two big loops max; every loop you open you close.

## Writing for the ear

- Read every line out loud. If you'd never say it to a friend, rewrite it.
- One idea per sentence. Mix lengths: short. Then one that runs a little longer because it's carrying a detail. Then short again.
- Concrete beats abstract: "my rent went from 400 to 650" over "costs increased significantly".
- Words the audience uses, including slang and contractions. No words you'd have to look up.
- Specificity is the proof: a real number, a date, a brand, a mistake you made. Never invent stats or quotes; a missing fact is `[DATO: …]` for the person to fill in.
- Cut the first sentence. Most drafts start one line too early.

## Not sounding like AI

Viewers recognise AI scripts in a second and swipe. Treat everything below as banned unless the person's own voice uses it.

**Structures**
- "It's not X, it's Y" / "No es X, es Y" / "Not just X, but Y" — the biggest tell. Zero per script.
- Lists of three: three adjectives, three benefits, three short sentences in a row with the same rhythm. Use two, or four, or one.
- Question then answer: "The result? Insane." / "¿El resultado? Increíble." "The secret? …"
- Colon reveals and em dashes everywhere. In a spoken script, use full stops.
- Every sentence the same length; every beat starting the same way; perfect parallelism.
- Explaining the hook after it lands; recapping what was just said; "In short…", "En resumen…", "En conclusión…".
- Motivational or moral closer: "Because at the end of the day…", "Remember: …", "Y recuerda: …".
- Hedging and balance nobody asked for: "it depends", "there are pros and cons", "everyone is different".
- Generic examples: "imagine a business owner", "a friend of mine" with no name or detail.

**Words and phrases**
- EN: delve, dive into, unlock, unleash, elevate, game-changer, revolutionize, seamless, effortless, journey, landscape, realm, tapestry, testament, crucial, pivotal, harness, navigate, empower, "here's the thing", "let that sink in", "buckle up", "trust me", "and the best part?", "in today's world".
- ES: sumérgete, descubre, desbloquea, potencia, revolucionario, imprescindible, crucial, clave (as an adjective in every line), "en el mundo actual", "en la era digital", "cabe destacar", "es importante mencionar", "sin más preámbulos", "te sorprenderá", "prepárate", "el secreto está en", "y lo mejor de todo", "no te lo pierdas", "acompáñame".

**Formatting:** no emoji in spoken lines, no hashtag walls in the caption (3–5 relevant ones max), no "🚀🔥💡" decoration.

**What makes it sound human:** an opinion someone could disagree with; a detail only someone who was there would know; a small admission ("I got this wrong for years"); an aside or interruption; a sentence that ends early. Some roughness is fine — it's a person talking.

## Output

Give the script as spoken lines only, one line per beat (name the beat in front). No timings, no on-screen text, no visuals:

```
TITLE: working title · PLATFORM · FORMAT

Hook: ...
Stakes: ...
Beat: ...
Payoff: ...
```

Then:
- **3 alternative hooks** (different patterns, same payoff), best first.
- **Caption** (1–2 lines, adds something the video doesn't say, or asks a real question that invites comments) + 3–5 hashtags.
- One line of **delivery notes** only if needed (which word to hit, where to cut; no pauses, lines run back to back).

## Check before delivering

1. **Swipe test:** read it line by line as a bored stranger. Mark every line where you'd swipe. Fix or cut those lines.
2. **Hook test:** is the first line specific, and does the hook promise exactly what the payoff delivers? A hook the payoff doesn't keep is clickbait and kills retention and trust.
3. **Cut:** remove every line, word and beat the payoff survives without. Then try once more.
4. **AI scan:** go through the "Not sounding like AI" list line by line. Any hit gets rewritten, not softened.
5. **Out loud:** read the whole thing at speaking pace. Anything you stumble over gets rewritten.

## Criterio

`~/.video-script-skill/criterio.md` holds the person's script taste. It lives outside the skill, so every project shares it and updating the skill never wipes it. Format:

```md
# Criterio
Guía, no reglas. Si algo no aplica al guion, ignoralo.
## Innegociable
## Preferencias
## A confirmar
## Ejemplos
(Antes / Después / Por qué; máx. 3, de tipos distintos)
```

Learn from every correction, not only approved ones:
- The person states a rule ("nunca", "siempre", "anotá esto"): write it straight into **Innegociable** (hard rule) or **Preferencias**.
- A correction with a pattern behind it: write the intent, not the wording, in **A confirmar**. If it's already there, move it to **Preferencias** with its why.
- A one-off about this topic only: don't save it.
- The person pastes back a script they edited themselves: compare it with yours and learn from the differences the same way.
- An entry with a data source in parentheses (e.g. another account's stats) moves to **Preferencias** only when new data confirms it or the person approves it. A correction from the person about their own videos outweighs another account's data.

After saving, say in one line what was saved and where, so the person can veto it.

Keep it small: Preferencias ≤15, A confirmar ≤10. Merge before adding: entries about the same part of the script (hook, cierre, tono…) become one. If a section is still full, ask the person which entry to drop; never drop one on your own. When an entry contradicts a newer correction, the newer one wins and the old one goes. Replace an example only with a better one of the same kind. Examples show judgment, not a template: never copy their structure or phrases.

If the video will be built with the `video-edit` skill, the spoken lines are the voice-over script.
