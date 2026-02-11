# Example Planning Sessions

This document shows real-world examples of how the ADHD Daily Planner skill works in practice.

---

## Example 1: Medium Energy Day with External Constraints

### User Input
```
Help me plan today. I have medium energy, a dentist appointment at 11am,
and I really need to finish the authentication feature for my app.
```

### Planning Conversation

**Claude:** What would make today feel like a win?

**User:** Finishing the authentication feature - it's been blocking me for days

**Claude:** Perfect. That's your anchor: "Finish authentication feature"

Quick context check - you mentioned:
- Energy: Medium
- Dentist at 11am
- Anything else carrying forward?

**User:** I also need to review two PRs and respond to a client email

**Claude:** Got it. Let me estimate times:

**Authentication feature (your anchor):**
- Core coding work: 2-3 hours
- Getting into flow: 15min startup
- Testing/debugging: 45min buffer
- **Total: ~3-4 hours realistic**

**Review 2 PRs:**
- Reading + understanding: 20min each = 40min
- Writing feedback: 10min each = 20min
- Startup cost: 5min
- **Total: ~65min**

**Client email:**
- Drafting response: 15min
- Thinking about what to say: 5min
- **Total: ~20min**

Now let's look at your available time:

**Morning (assume 9am start - 11am dentist):**
- Available: 2 hours
- Minus transitions: 10min
- **Realistic: ~1hr 50min**

**Afternoon (assume 12pm return - 5pm end):**
- Available: 5 hours
- Minus lunch/midday reset: 45min
- Minus post-break startup: 15min
- Minus transitions: 15min
- **Realistic: ~3hr 45min**

**Total capacity: ~5.5 hours work time**
**Total tasks: ~5-5.5 hours**

This is tight but doable. Here's the plan:

### Daily Plan Output

```
📅 DAILY PLAN - Today

⚡ Energy Level: Medium
🎯 Today's Anchor: Finish authentication feature

🌅 MORNING BLOCK (9:00am-11:00am)
□ Client email response - Admin - 20m (quick win!)
□ Start authentication feature - Dev - 90m

--- DENTIST APPOINTMENT (11am-12pm) ---
--- Midday Reset: Eat, Move, Check Energy ---

🔥 AFTERNOON FOCUS (12:00pm-5:00pm)
□ Continue authentication feature - Dev - 2h (CORE ANCHOR TIME)
□ Review PR #1 - Dev - 30m
□ Review PR #2 - Dev - 30m

🌙 END OF DAY
If auth feature complete: Victory!
If not complete: Document what's left for tomorrow
```

**Notes:**
- Email first = momentum booster
- Auth work split across morning/afternoon
- Protect 2hr afternoon block for deep work
- PRs after your brain is tired from coding = good match

Sound good?

---

## Example 2: Low Energy Day

### User Input
```
/adhd-daily-planner

I'm really dragging today. Low energy, didn't sleep well.
But I have things I need to get done.
```

### Planning Conversation

**Claude:** What would make today feel like a win?

**User:** Honestly? Just keeping things moving. Maybe getting through my email backlog.

**Claude:** Let's make that more concrete. What if your anchor was: "Process email inbox to zero and respond to urgent items"?

That's achievable even on low energy, and it'll feel great to have a clear inbox.

Quick check:
- Any time constraints today?
- What else is on your mind that needs attention?

**User:** No meetings. I also have some documentation to write and a bug report to file.

**Claude:** Okay, let me estimate for low energy:

**Email processing:**
- Reading/sorting: 45min
- Responding to urgent items: 30min
- **Total: ~75min** (This is your anchor - protect this)

**Documentation writing:**
- Actual writing: 30min
- Starting/organizing thoughts: 10min
- **Total: ~40min**

**Bug report:**
- Writing up the issue: 15min
- Finding screenshots/examples: 10min
- **Total: ~25min**

On a low energy day, here's what I recommend:

**Available energy: ~3-4 hours of actual work capacity**
**Planned tasks: ~2.5 hours**

This gives you buffer for brain fog and rest breaks.

### Daily Plan Output

```
📅 DAILY PLAN - Today

⚡ Energy Level: Low
🎯 Today's Anchor: Process email inbox to zero

🌅 MORNING (9:30am-12:00pm)
□ File bug report - Admin - 25m (Quick, clear task to start)
□ Email processing (Anchor) - Admin - 75m

--- Long Midday Reset: Eat, Walk, Maybe Nap (1hr) ---

🧘 AFTERNOON (1:00pm-3:00pm)
□ Documentation writing - Admin - 40m
□ If energy allows: [Bonus tasks]
□ If not: Rest is productive too

🌙 END OF DAY
Celebrate clear inbox
Note tomorrow's #1 priority
```

**Important for today:**
- Take the full midday break - rest is part of productivity
- Documentation is last because it's lowest stakes
- If you finish by 2pm and feel done, that's OKAY
- Low energy days are for maintenance, not breakthroughs

Sound good?

---

## Example 3: High Energy, Multiple Projects

### User Input
```
I have high energy today and want to make serious progress on my app.
Help me plan an ambitious but realistic day.
```

### Planning Conversation

**Claude:** Love the energy! What would make today feel like a win?

**User:** Shipping the new dashboard feature - getting it fully done and deployed

**Claude:** Beautiful anchor: "Ship dashboard feature to production"

Quick context:
- Any meetings or constraints?
- What else needs attention today?

**User:** No meetings. I also want to start the API refactor we discussed,
and I need to review the designer's mockups for the next feature.

**Claude:** Okay, let's reality check this with time estimates:

**Dashboard feature (anchor):**
- Final implementation: 90min
- Testing across browsers: 30min
- Deployment prep: 20min
- Deploy + monitoring: 20min
- **Total: ~2.5 hours**

**Start API refactor:**
- Planning/architecture: 45min
- Initial implementation: 60min
- Testing setup: 30min
- **Total: ~2 hours**

**Review design mockups:**
- Reviewing designs: 20min
- Writing feedback: 15min
- **Total: ~35min**

**Total tasks: ~5 hours**

Even with high energy:

**Available capacity (9am-5pm):**
- Total time: 8 hours
- Minus lunch + breaks: 1hr
- Minus transitions: 30min
- Minus startup costs: 20min
- **Realistic: ~6 hours**

You have room! But let's add one more thing...

**User:** What do you have in mind?

**Claude:** With your extra capacity, add either:
1. Documentation for the dashboard feature
2. Write tests for API refactor
3. Clean up technical debt that's been bugging you

What sounds good?

**User:** Tests for the API refactor - I always skip those

**Claude:** Perfect. Adding 45min for test writing.

### Daily Plan Output

```
📅 DAILY PLAN - Today

⚡ Energy Level: High 🔥
🎯 Today's Anchor: Ship dashboard feature to production

🌅 MORNING SPRINT (9:00am-12:30pm)
□ Dashboard final implementation - Dev - 90m
□ Review design mockups - Design - 35m
□ Dashboard testing - QA - 30m
□ Dashboard deployment - Ops - 20m ✨ ANCHOR COMPLETE

--- Victory Lap Break (30min) ---

🔥 AFTERNOON BUILD (1:00pm-5:00pm)
□ API refactor planning - Dev - 45m
□ API refactor implementation - Dev - 90m
□ Write tests for API refactor - Dev - 45m

🌙 END OF DAY CELEBRATION
Dashboard shipped! ✅
API refactor started with tests ✅
Tomorrow: Continue API refactor
```

**Notes:**
- Tackle anchor FIRST while energy is highest
- Mockup review is a nice cognitive break between coding tasks
- Deploy before lunch = you can monitor during break
- API work is meaningful progress without needing to finish today
- Tests immediately after coding = better than "I'll add them later"

This is an ambitious day - but it's realistic for high energy.
If something takes longer, the API refactor is flexible to continue tomorrow.

Sound good?

---

## Example 4: Overwhelm Recovery

### User Input
```
I'm so behind. I have a million things to do and I don't even know where to start.
Can you help me plan today?
```

### Planning Conversation

**Claude:** Let's cut through the overwhelm.

First, take a breath. The million things can wait.

**What's the ONE thing that, if you did it today, would give you relief?**

Not the most urgent, not the most important - what would make you feel less overwhelmed?

**User:** Probably the client presentation. It's due Friday and I haven't even started.

**Claude:** Perfect. That's your anchor: "Make real progress on client presentation"

Now, let's be realistic. You're already feeling overwhelmed, so we're going to plan small.

What does "real progress" look like?
- Outline complete?
- First draft?
- Just getting started?

**User:** I'd feel so much better if I had an outline and knew what I was going to say.

**Claude:** Excellent. Updated anchor: "Complete presentation outline"

That's achievable and will make the rest feel less scary.

Energy check - with the overwhelm, what's your energy really like?

**User:** Honestly, low. I'm stressed.

**Claude:** Okay. Low energy + overwhelm = we plan TINY.

**Presentation outline:**
- Brain dump ideas: 20min
- Organize into structure: 25min
- **Total: 45min**

That's it. That's your whole focus work for today.

### Daily Plan Output

```
📅 DAILY PLAN - Today (Overwhelm Recovery Mode)

⚡ Energy Level: Low (+ stressed)
🎯 Today's Anchor: Complete presentation outline

🌅 WHEN YOU'RE READY TO START
□ Presentation outline - Work - 45m

That's it.
ONE task.
Everything else can wait.

🧘 AFTER ANCHOR IS DONE
□ Take a walk
□ Celebrate the win
□ If you feel like it: Pick ONE more small thing
□ If not: Rest. You're doing enough.

🌙 END OF DAY
Presentation has structure now ✅
Tomorrow will be easier because today you started ✅
```

**Important:**
- Seriously, just do the outline
- Don't try to catch up on everything
- Overwhelm recovery requires tiny wins
- Momentum builds from completion, not from long todo lists

Does this feel doable?

**User:** Yeah, actually. That feels manageable.

**Claude:** Good. When you finish that outline, message me and we'll plan tomorrow.

One day at a time.

---

## Common Patterns Across Examples

### The Anchor Always Comes First
Every planning session starts with identifying what would make the day feel like a win.

### Time Math is Explicit
The skill always shows:
- Estimated time for each task
- Available time in each block
- Whether the plan fits

### Energy Matching
- High energy → complex, creative work
- Medium energy → moderate tasks + admin
- Low energy → simple tasks + maintenance

### Buffer is Built In
Every estimate includes:
- Startup time
- Buffer time
- Transition time

### Flexible Endings
Plans always acknowledge that life happens and provide guidance for what to do if things don't go as planned.
