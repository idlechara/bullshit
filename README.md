# deflate 💩

**A Claude Code plugin that un-enshittifies LinkedIn posts.**

Paste any thought-leadership post, corporate announcement, or "personal journey" homily, and get back the real event underneath — said plainly, in the post's own language — plus a bullshit meter, a brutally honest one-liner, and a breakdown of the manipulation tricks used.

## Example

Feed it a post where a CEO announces "medimos un aumento de 4x en la productividad" over a giant 4x graphic, with zero methodology, tagged "SERIE 2/6":

> **Medidor de caca: 💩 90%** `[█████████░]`
>
> > Medimos que los ingenieros van 4x más rápido con IA. No expliqué cómo lo medimos.
>
> **"Tengo un número grande, un gráfico gigante que lo repite, y cero idea de cómo lo calculé."**
>
> Las señales: todo el post defiende el número sin decir nunca cómo se midió; un gráfico gigante con el numerote como sustituto de datos; y "SERIE 2/6" — cosecha de calendario de contenidos, esto ya es una franquicia.

## Install

In Claude Code:

```
/plugin marketplace add idlechara/deflate
/plugin install un-enshittifier@deflate
```

## Use

```
/un-enshittifier <paste the post>
```

Screenshots work too — paste an image of the post.

## What you get

1. **The bullshit meter** — 0% (a plain honest fact) to 100% (pure engagement farming with nothing underneath), with a gauge bar. Posts with a real event under the bloat cap around 80%; 90%+ is reserved for posts where stripping the bloat leaves nothing.
2. **The rewrite** — what actually happened, in 1–2 sentences, in the post's original language.
3. **The one-liner** — what the post is really *doing*, in one sentence.
4. **The tells** — the manipulation techniques at work, when they're interesting.

## The serious part

The humor comes strictly from deflation, never invention — the skill only mocks what is literally on the page. And the "tells" aren't made up either: each one maps to a documented persuasion technique — appeal to authority (Cialdini), pseudo-profound bullshit (Pennycook et al., 2015), narrative transportation (Green & Brock, 2000), processing fluency, anchoring (Tversky & Kahneman, 1974), engagement bait (formally defined and demoted by Meta since 2017), and classical apophasis.

The full grounded catalog — mechanism, research, and a practical "how to spot it" test for each tell — lives in [skills/un-enshittifier/references/catalog.md](skills/un-enshittifier/references/catalog.md). Ask the skill *why* a tell works and it answers from there, sources included, roast off. The framing owes everything to Harry Frankfurt's *On Bullshit*: these posts usually aren't lies — they're indifferent to truth, optimized for effect. That's what makes them deflatable.

## License

MIT
