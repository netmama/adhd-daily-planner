# Planning Model

This document explains the reasoning behind the Life-Aware Daily Planner. The main operational instructions live in `SKILL.md`.

## The planning loop

`Direction → Milestone → Next action → Daily plan → Real-world feedback → Adjustment`

The loop should stay lightweight. A user should be able to ask for today's priorities without having to complete a weekly review first.

## Four connected layers

### 1. Direction
Keep sight of what the user is building or caring for over time. Goals may span income, career, learning, home, health routines, relationships, worship or personal values, and enjoyment. Do not assume all areas have equal priority or need attention every day.

### 2. Capacity and context
Plan around the user's actual day. Mental focus and physical stamina are not interchangeable. Symptoms, stress, social demands, travel, and recovery can affect capacity in different ways. Ask only about the factors that matter today.

### 3. Execution
Translate priorities into small actions with realistic startup, transition, and uncertainty costs. Make the first step clear enough to begin. Leave optional work optional.

### 4. Feedback
Use real task durations and brief user reflections to improve future estimates. Do not build a second tracker when the user already has one. Missing data is not negative evidence.

## Choosing today's priorities

A useful order of consideration:

1. Fixed commitments and time-sensitive responsibilities.
2. The smallest meaningful action toward the most important current goal.
3. Essential maintenance (food, medication routines as prescribed, home basics, personal care).
4. Supporting life areas that fit today's capacity.
5. Optional extras only if the day genuinely has room.

This is a decision aid, not a rigid ranking. The user's own values and circumstances take precedence.

## Capacity is not a single meter

A person may have enough mental focus to read but not enough physical stamina for an outing; or enough physical energy for a simple errand but little capacity for complex decisions. Avoid collapsing these differences into one score.

Useful dimensions, only when relevant:
- Cognitive: focus, working memory, decision fatigue, initiation.
- Physical: stamina, mobility, pain, weakness, exertion tolerance.
- Symptoms: the user's own description of what is affecting them.
- Emotional and social: stress, conflict, interaction load.
- Recovery: recent demands and expected after-effects.

Do not make medical judgments from these planning inputs.

## Why estimates must adapt

Generic estimates are starting hypotheses. User-provided elapsed-time logs are stronger evidence, but one observation does not establish a stable pattern. Compare repeated examples and account for task complexity, interruptions, startup, and context.

If a task repeatedly overruns, consider whether its scope or definition is unclear before increasing its scheduled duration indefinitely.

## What this model avoids

- Scheduling every available minute.
- Treating a low-capacity day as a failed high-capacity day.
- Assuming all fatigue is psychological.
- Treating paid work as the only meaningful progress.
- Requiring lengthy daily journaling.
- Requiring the user to log the same task in two places.
- Pretending to access a local app or health record without a real connected integration.
- Repeatedly moving unfinished tasks forward without examining why they remain unfinished.
