# World Cup 2026 Predictor

A Codex skill for forecasting the 2026 FIFA World Cup with structured reasoning, current evidence, and explicit uncertainty.

## What This Skill Does

This skill helps Codex make better World Cup predictions by using a consistent workflow instead of casual sports opinions.

It is designed for tasks like:

- predicting the 2026 World Cup champion
- ranking the main contenders
- identifying dark horses
- projecting semifinalists or finalists
- estimating likely disappointment teams
- analyzing specific matchups and likely scorelines

## What Makes It Useful

The skill pushes Codex to:

- browse for current information before making serious forecasts
- prioritize official FIFA and federation sources
- separate confirmed facts from inference
- score contenders with a repeatable evaluation rubric
- account for tournament path, variance, injuries, and squad balance
- present predictions with confidence levels and dated assumptions

## Skill Name

Use this skill as:

`$world-cup-2026-predictor`

## Example Prompt

```text
Use $world-cup-2026-predictor to forecast the 2026 FIFA World Cup champion and strongest dark horses.
```

## Files

- `SKILL.md`: core instructions and workflow
- `agents/openai.yaml`: UI metadata for the skill
- `references/evaluation-framework.md`: scoring rubric and output guidance
- `references/data-sources.md`: source priority, search patterns, and evidence checklist

## Installation

If you want to install this skill into Codex manually, place the folder in:

```text
~/.codex/skills/world-cup-2026-predictor
```

On Windows, that is typically:

```text
C:\Users\<your-user>\.codex\skills\world-cup-2026-predictor
```

Then restart Codex so it can discover the skill.

## Forecasting Approach

The skill uses a simple but disciplined process:

1. Confirm the prediction scope.
2. Gather current evidence.
3. Build a shortlist of contenders.
4. Evaluate teams with a consistent rubric.
5. Adjust for path difficulty and tournament variance.
6. Produce a dated forecast with confidence and caveats.

## Notes

This skill is built for reasoned forecasting, not certainty. World Cup predictions can change meaningfully with injuries, final squads, draw changes, and late-form swings.
