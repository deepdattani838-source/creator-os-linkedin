# Voice profile — business/finance LinkedIn posts

Derived from 4 sampled posts (EV infrastructure lease, Gartner stock surge, NASCAR/O'Reilly
promotion, Brazil Potash mining). Treat as a first pass — validate against the full 20+ before
relying on it for real drafts; these four all happened to be market/business-news reactions,
so structure or tone may vary outside that category.

## Structural template (all 4 samples matched this exactly)
1. **Opening paragraph** — states the news event with 2–3 concrete numbers pulled directly from
   the source (dollar figures, percentages, timeframes). 3 of 4 samples opened with "A major ___."
2. **Second paragraph** — explains why it matters / the strategic angle. Recurring openers:
   "By ___ing,", "For [company], this ___ is a strategic move to", "This development is a
   significant milestone for."
3. **Third paragraph** — forward-looking, hedged. Recurring openers: "The big question going
   forward is whether...", "Going forward, the key factor to watch is...", "It will be worth
   watching whether...", "Moving forward, the key challenge will be...". Frequently closes with
   "...could serve as a blueprint for [some future scenario]."
4. **Closing line** — always a direct, binary engagement question: "Do you think A, or B?"

## Recurring phrases (reuse these — they're the voice, not accidental repetition)
- "A major ___" as an opener
- "could serve as a blueprint for"
- "worth watching whether"
- "Do you think X, or Y?" as the closer

## Tone
- Third-person, analyst/journalist register. No first-person opinion stated directly.
- No personal anecdotes, no emojis, no slang.
- Numbers-heavy — every post leads with 2+ hard figures from the source.
- Medium-length declarative sentences, comfortable with hedged language ("could," "it will be
  worth watching").

## Where the creator's actual opinion lives
None of the 4 samples state a personal take in so many words. The reaction is expressed
*implicitly*, through:
- which story got chosen at all
- which angle paragraph 3 takes
- the specific framing of the closing question

So "creator's reaction" as an input to the drafting step should be captured as: which
forward-looking angle, and which side of the closing question — not as a separate opinion
paragraph to write and insert.

## What NOT to flag as repetition
The structural phrases above repeat on purpose across posts — that consistency is part of what
makes them recognizably this creator's. A dedup/voice check should compare topic and specific
claims (same company, same event) against the archive, not these connective phrases — otherwise
it will keep wrongly flagging the creator's own consistent style as "too similar to last time."
