# The Four Vedas — Faceless YouTube Channel

A production system for a faceless, bilingual (Hindi + English) YouTube channel that
explains the wisdom of the Four Vedas to complete beginners — history, philosophy,
and practical relevance, without religious preaching, mythology-as-fact, politics,
or debate.

## Mission

Make Vedic knowledge understandable for ordinary people, in 3–5 minute videos, with
Netflix-documentary-style visuals and Kurzgesagt/Johnny Harris/MagnatesMedia-style
storytelling. Every claim is sourced (Veda, Mandala, Sukta, Mantra). Where scholars
disagree, the video says so explicitly instead of picking a side.

## Repository layout

```
docs/
  production-guide.md   Master style guide — tone, structure, accuracy rules,
                         visual/audio spec, SEO spec. Read this first.
  roadmap-90-day.md      The 90-day / 90-video topic roadmap, grouped by month,
                         with a checkbox per episode to track production status.
templates/
  episode-template.md    Blank, fill-in-the-blank template implementing every
                         required section from the production guide. Copy this
                         to start a new episode.
episodes/
  NNN-slug/
    script.md            The finished script for one episode (all 13 required
                          sections, Hindi + English, Sanskrit sources, visuals,
                          narration, SEO) — produced from the template.
```

## Workflow for a new episode

1. Pick the next unchecked topic in `docs/roadmap-90-day.md`.
2. Copy `templates/episode-template.md` to `episodes/NNN-slug/script.md`.
3. Fill in every section. Do not invent Sanskrit citations or mystical claims —
   if a claim can't be traced to a specific Mandala/Sukta/Mantra, cut it or mark
   it as disputed per `docs/production-guide.md`.
4. Check the topic off in the roadmap and link the episode folder.

## Episode 1

[`episodes/001-did-the-vedas-mention-the-big-bang/script.md`](episodes/001-did-the-vedas-mention-the-big-bang/script.md) —
*Did the Vedas Mention the Big Bang?* (Nasadiya Sukta, Rigveda 10.129), a
myth-vs-fact episode chosen to set the channel's accuracy-first tone from day one.
