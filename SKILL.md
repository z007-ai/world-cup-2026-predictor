---
name: world-cup-2026-predictor
description: Forecast the 2026 FIFA World Cup with a structured, evidence-based method that balances team strength, tournament path, roster quality, coaching, form, injuries, and uncertainty. Use when Codex needs to predict the 2026 FIFA World Cup champion, finalists, semifinalists, dark horses, group-stage outcomes, knockout paths, upset risks, or matchup probabilities, especially when the user asks for reasoned sports forecasting instead of casual opinions.
---

# World Cup 2026 Predictor

Use this skill to produce forecasts that are explicit about evidence, uncertainty, and timing. Treat predictions as dated estimates, not timeless truths.

## Workflow

1. Confirm the prediction scope.
2. Gather current evidence.
3. Build a shortlist of contenders.
4. Evaluate each team with a consistent rubric.
5. Adjust for tournament path and variance.
6. Produce the forecast with confidence levels and caveats.

## Confirm The Scope

Identify exactly what the user wants:

- Champion prediction
- Finalists or semifinalists
- Full bracket projection
- Group-stage qualifiers
- Dark horse teams
- Match-specific or head-to-head probability

If the user does not specify, default to:

- one predicted champion
- three main contenders
- two dark horses
- one likely disappointment

## Gather Current Evidence

This domain is time-sensitive. Always browse for current information before making a substantive forecast.

Read `references/data-sources.md` before collecting evidence if you need source priority, search patterns, or source-quality rules.

Prioritize:

- FIFA rankings or Elo-style team strength signals
- recent competitive results and form
- qualification performance
- likely squad pool and player availability
- manager quality and tactical fit
- injuries, suspensions, and aging curves
- host-nation effects and venue/travel considerations
- current tournament structure and draw status

Use primary or high-quality sources where possible. Distinguish confirmed facts from inference.

If the user asks for a forecast far in advance of the tournament, explicitly note that uncertainty is higher because squads, injuries, and the draw can change materially.

## Evaluate Teams Consistently

Use the rubric in `references/evaluation-framework.md`.

At minimum, score or discuss:

- baseline team quality
- top-end star power
- squad depth
- balance across defense, midfield, and attack
- coaching and tactical adaptability
- recent form in serious matches
- tournament experience and mentality
- path difficulty
- downside risk

Do not rely on a single metric. Combine quantitative signals with qualitative tournament judgment.

## Adjust For Tournament Reality

World Cup forecasting is path-dependent. Improve the forecast by accounting for:

- group difficulty
- likely round-of-16 and quarterfinal opponents
- travel burden across host countries
- extra-time and penalty variance
- matchup asymmetries such as high press vs. weak build-up or elite transition attack vs. slow center backs

When the draw is unknown or incomplete, say so and separate:

- best team overall
- most likely champion given current assumptions

Those are not always the same.

## Output Format

Prefer a compact forecast with dated assumptions.

Use this structure:

```markdown
## 2026 World Cup Forecast

As of <date>:

- Predicted champion: <team>
- Best challenger: <team>
- Dark horses: <team>, <team>
- Possible disappointment: <team>

### Why <champion>
3-5 concise reasons tied to evidence.

### Main risks to this prediction
- <risk>
- <risk>

### Confidence
<low/medium/high>, with a one-sentence explanation.
```

If the user asks for a richer answer, add a contenders table or knockout-path notes.

## Source Discipline

Use sources in this priority order:

1. Official FIFA tournament, ranking, draw, squad, and regulations pages
2. Official federation sources such as AFA, CBF, FFF, RFEF, FPF, or equivalent
3. High-quality analytical or reporting outlets for injuries, availability, and tactical context
4. Model-based forecast sites only as secondary support, never as the sole basis for the answer

If multiple sources conflict:

- prefer the newest official source for facts
- prefer the most direct source for squad or injury status
- tell the user when a key assumption is unsettled

## Reasoning Standards

Be willing to make a real prediction. Avoid hiding behind excessive hedging.

At the same time:

- never imply certainty
- avoid fabricated injury or roster claims
- separate observed facts from projection
- use absolute dates when discussing "current" form or rankings
- revise the forecast if newer information materially changes the outlook

## References

Read `references/evaluation-framework.md` when you need the detailed scoring rubric, tie-break logic, and answer templates.
Read `references/data-sources.md` when you need browsing patterns, source priority, or a reusable evidence checklist.
