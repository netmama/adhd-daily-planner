# ADHD-Optimized Daily Planner

A Claude Code skill that helps you plan your day with realistic time estimates, energy-based task allocation, and ADHD-friendly workflows.

## 🎯 What It Does

This skill acts as your daily planning assistant, helping you:

- **Set a meaningful anchor** - Identify the ONE thing that would make today feel like a win
- **Account for time blindness** - Break down tasks with realistic estimates including startup, buffer, and transition time
- **Match tasks to energy** - Allocate complex work when you have high energy, simple tasks for low energy
- **Plan for capacity, not wishes** - 70% capacity planning that accounts for interruptions and "got pulled into" moments
- **Balance work and life** - Protect personal/family time with low-cognitive-load task scheduling

## ⚡ Key Features

### Realistic Time Estimation
The skill breaks down every task into:
- **Core work time** - The actual hands-on time
- **Startup cost** - Getting into the task, loading context (5-15min)
- **Buffer** - For unexpected issues and scope creep (25-50% extra)
- **Transition time** - Between tasks (5-10min each)

Example: "Write blog post" becomes:
- Writing: 45-60min
- Finding flow/starting: 10min
- Editing/revising: 15min
- Unexpected rewrites: 20min buffer
- **Total: ~90min realistic, 2hr safer estimate**

### Energy-Based Task Allocation
- **High energy days:** 3-4 complex tasks + quick wins
- **Medium energy days:** 2-3 moderate tasks + administrative work
- **Low energy days:** 1-2 simple tasks + maintenance work

### ADHD-Friendly Principles
- ✅ Plans for 70% capacity, not 100%
- ✅ Minimizes context-switching
- ✅ Accounts for startup and transition costs
- ✅ Validates realistic planning instead of aspirational wish lists
- ✅ Focuses on meaningful wins, not task completion counts

## 📦 Installation

### Option 1: Direct Installation (Recommended)

1. **Download this skill:**
   ```bash
   cd ~/.claude/skills/
   git clone https://github.com/netmama/adhd-daily-planner.git
   ```

2. **Restart Claude Code** (or reload the skills directory)

3. **Test it:**
   Type `/adhd-daily-planner` in any Claude Code conversation

### Option 2: Manual Installation

1. Download or clone this repository
2. Copy the entire `adhd-daily-planner` folder to `~/.claude/skills/`
3. Restart Claude Code
4. Use `/adhd-daily-planner` to activate

### Verify Installation

Check that the skill is loaded:
```bash
ls ~/.claude/skills/adhd-daily-planner/
```

You should see `SKILL.md` and `README.md`.

## 🚀 Usage

### Basic Usage

Simply type in any Claude Code conversation:
```
/adhd-daily-planner
```

Or ask naturally:
```
Help me plan my day
```

### Example Planning Session

```
You: /adhd-daily-planner

Claude: What would make today feel like a win?

You: Finishing the authentication feature for the app

Claude: Perfect. That's your anchor: "Finish authentication feature"

Quick context check:
1. What's your energy level today? (High/Medium/Low)
2. Any schedule constraints or time commitments?
3. Anything else carrying forward from yesterday?

You: Medium energy, have a 2pm meeting, need to review PR feedback

Claude: Got it. Let me estimate times...

[Continues with realistic time breakdowns and capacity planning]
```

### What You'll Get

At the end of the planning conversation, you'll receive:
- A structured daily plan formatted for easy copy-paste
- Realistic time estimates for each task
- Task allocation across energy-appropriate time blocks
- Clear identification of your "anchor" (the win for the day)
- Math showing available time vs. planned tasks

## 🎨 Customization

You can customize this skill for your specific needs by editing `SKILL.md`:

### Adjust Time Blocks
The skill adapts to your schedule. During planning, it will ask about your typical time blocks. You can also hardcode your preferred schedule in the skill file.

### Change Task Categories
Modify the task complexity definitions to match your work type:
- High complexity
- Medium complexity
- Low complexity

### Personalize the Conversation Style
Edit the "Conversation Style" section to match your preferences (more/less verbose, different tone, etc.)

## 🧠 Philosophy

This skill is built on these core beliefs:

1. **Time blindness is real** - Many people with ADHD struggle with time estimation. Explicit breakdowns help.
2. **Energy varies daily** - What you can do today depends on today's energy, not theoretical capacity.
3. **Realistic > Aspirational** - Planning 3 tasks you'll actually do beats listing 10 you hope to do.
4. **The anchor matters** - One meaningful accomplishment beats scattered productivity.
5. **Transitions are expensive** - Context-switching has a real cognitive cost that must be planned for.

## 🤝 Contributing

Contributions are welcome! If you have improvements or adaptations:

1. Fork this repository
2. Make your changes
3. Submit a pull request with a clear description

Ideas for contributions:
- Additional planning templates (weekly planning, project planning)
- Integration with specific task management systems
- Variations for different work contexts (remote work, office work, creative work)
- Translations to other languages

## 📄 License

MIT License - see `SKILL.md` for full license text.

You're free to:
- ✅ Use this skill personally or commercially
- ✅ Modify it for your needs
- ✅ Share it with others
- ✅ Fork it and create derivatives

Just include the original copyright notice.

## 🙏 Acknowledgments

Created by **Erin Leibowitz** for the ADHD community and anyone who struggles with time blindness, energy management, or realistic planning.

Inspired by real-world struggles with executive function and the need for planning tools that work *with* ADHD brains, not against them.

## 💬 Support & Feedback

- **Issues:** [GitHub Issues](https://github.com/netmama/adhd-daily-planner/issues)
- **Discussions:** [GitHub Discussions](https://github.com/netmama/adhd-daily-planner/discussions)

---

**Built with Claude Code** • [Learn more about Claude Code](https://github.com/anthropics/claude-code)
