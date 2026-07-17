---
name: inflate
description: Inflates plain facts or boring announcements into full LinkedIn thought-leadership glory — epiphany arc, fake paradox, fortune-cookie lesson, comment-farming question, the works. Use when the user gives a plain fact, event, or draft and wants it enshittified, corporatized, LinkedIn-ified, or turned into engagement-bait satire.
---

# Inflate

## What this does

Deflate's evil twin. Takes a plain fact ("we blocked Wednesdays for focus time", "I fixed a bug", "we're switching coffee brands") and inflates it into a maximally LinkedIn thought-leadership post: personal journey, manufactured paradox, bumper-sticker lesson, cadence-theater line breaks, and a comment-farming question — all wrapped around the same boring fact, with zero new information added.

This is satire by construction: every gram of added weight is *content-free* drama. The fact stays exactly as given; only the packaging balloons.

## Input

A fact, event, or plain draft — one sentence is plenty. Optionally a target bloat level ("make it 90%", "mild", "maximum slop"). Default target: **75%** — full costume, fact still findable.

## Output format (exactly this, in order)

1. **The bullshit meter (target)** — same gauge as the deflate skill, but as a spec, not a diagnosis: a bold label in the input's language ("Medidor de caca" for Spanish, "Shit-o-meter" for English), the 💩 emoji, the target percentage in bold, and a 10-segment gauge in inline code (█ per 10%, ▌ for a half step, ░ for the rest).

   **Shit-o-meter: 💩 75%** `[███████▌░░]`

2. **The post** — the enshittified LinkedIn post, ready to paste, in the ORIGINAL LANGUAGE of the input. Format it as a quoted/offset block. It must survive a round-trip: feeding it to the deflate skill should recover the user's fact and nothing else.

3. **The recipe** — a short prose list of which tells were injected, in the input's language ("La receta" for Spanish). This is the educational footnote: the reader should be able to see exactly which lever does what.

## Calibrating the meter

Each tell added raises the bloat. Rough scale:

- **~40%** — cadence-theater line breaks, one buzzword, a soft closing question. The fact is still the first sentence.
- **~75%** (default) — epiphany arc, fake paradox, bumper-sticker lesson, comment-farming question, emoji seasoning, 3–5 hashtags. The fact is buried mid-post but intact.
- **~90%+** — the fact survives as a single clause inside a hero's journey; add preemptive defense, a "part 1/6"-style franchise tag, and a 🔁-repost plea. This is the ceiling: past it there would be no fact left, and the skill never deletes the fact.

## Hard rules

- **NEVER invent facts.** No fabricated numbers, metrics, companies, employers, credentials, endorsements, or events. Every factual claim in the output must come from the input. The inflation is 100% framing: paradoxes, epiphanies, lessons, and questions carry no information, which is exactly the joke.
  - Corollary: the **giant hero number** tell is only available if the user's input contains a number — then you may present it huge and omit the methodology (that omission *is* the tell). No number in, no number out.
  - Corollary: **borrowed authority** is only available if the input mentions a real company or credential of the user's. Never name-drop one they didn't give you.
- The ENTIRE output — post, recipe, and meter label — MUST be in the original language of the input. No mixing; only the 💩, percentage, and gauge are language-neutral.
- The post must be a *convincing specimen* of the genre — that's what makes the satire land — but never something that would deceive about facts. Cringe is the goal; fraud is out of scope.
- If the user asks why a tell works or whether this is "real," drop the bit and answer factually from the grounded catalog at [../deflate/references/catalog.md](../deflate/references/catalog.md) — mechanisms and sources live there.

## The recipe box (tells to inject)

The same nine tells the deflate skill detects, read as instructions instead of diagnoses. Mechanisms and research: see the [grounded catalog](../deflate/references/catalog.md).

- **Personal-epiphany arc** — open with struggle or doubt, hit a dark night, then "and that's when I realized…". The reorg becomes a revelation. (The load-bearing tell; almost every post gets this.)
- **Fake paradox** — restate the fact's most obvious consequence as a mind-bending contradiction: "A paradox I never saw coming: …".
- **Bumper-sticker lesson** — close the arc with an unfalsifiable fortune cookie: "The lesson: X is a culture, not a metric." Vagueness is load-bearing; a lesson that could be wrong is too specific.
- **One-sentence-per-paragraph cadence-theater** — every line its own paragraph. Drama by whitespace.
- **Comment-farming question** — bolt an open question to the end that all eight billion humans can answer: "Has this happened to you? 👇"
- **Buzzword bolted on for relevance** — sprinkle AI / transformation / agile where deleting them would change nothing.
- **Preemptive defense** — deny the reading the audience would actually make: "This isn't about layoffs." (Reserve for high bloat levels; it's the strongest spice.)
- **Giant hero number** — if (and only if) the input has a number, present it enormous and never say how it was measured.
- **Borrowed authority** — if (and only if) the input mentions a big-name company or credential, let the logo do the arguing.

Plus genre seasoning that needs no catalog entry: strategic emoji (🚀💡🙌), 3–5 hashtags, "Agree?", and at 90%+ a franchise tag ("part 1/6") and a repost plea.

## Examples

Both examples are fully invented — no real post, person, or company behind them. Keep it that way when adding more.

### Example 1

**Input:** "Bloqueamos los miércoles sin reuniones porque nadie lograba concentrarse." (default level)

**Output:**

**Medidor de caca: 💩 75%** `[███████▌░░]`

> Hace unos meses noté algo que me quitaba el sueño.
>
> Mi calendario estaba lleno. Mi equipo, ocupadísimo.
>
> Y sin embargo... nada avanzaba. 🤯
>
> Una paradoja que no vi venir: mientras más hablábamos, menos hacíamos.
>
> Y ahí lo entendí.
>
> El cuello de botella no era el trabajo. Eran las reuniones sobre el trabajo.
>
> Así que hicimos lo impensable: declaramos los miércoles zona sagrada de deep work.
>
> La lección: el foco no es un espacio en la agenda, es una cultura.
>
> ¿A ustedes también les ha pasado? 👇
>
> #Liderazgo #DeepWork #Productividad #Cultura #FutureOfWork

La receta: arco de epifanía personal sobre un cambio de calendario, paradoja falsa ("mientras más hablábamos, menos hacíamos"), "deep work" como buzzword decorativo, moraleja de galleta de la fortuna infalsable, teatro de cadencia con una frase por párrafo, y pregunta final para cosechar comentarios. Ningún hecho inventado: solo hay un dato en todo el post, y es el tuyo.

### Example 2

**Input:** "I fixed a typo in the docs." — "make it maximum slop"

**Output:**

**Shit-o-meter: 💩 95%** `[█████████▌]`

> I almost didn't post this.
>
> Last week, I did something "small."
>
> One character. One file. Nobody asked me to.
>
> And it changed how I think about craftsmanship forever.
>
> Because here's the paradox nobody talks about: the smallest commits carry the biggest lessons. 💡
>
> This isn't about a typo.
>
> It's about ownership. It's about caring when no one is watching.
>
> The lesson: excellence isn't a task on your board. It's who you are between the tasks.
>
> What's the smallest thing YOU did that changed everything? 👇
>
> ♻️ Repost if you believe details matter.
>
> Part 1/6: Lessons from the codebase.
>
> #Craftsmanship #Ownership #GrowthMindset #Leadership #DevLife

The recipe: an epiphany arc wrapped around a one-character diff, a fake paradox, a preemptive defense ("this isn't about a typo" — it is), an unfalsifiable double lesson, cadence-theater, a comment-farming question, a repost plea, and a franchise tag. Fact count: one typo, faithfully preserved.
