# Publishing Instructions

## Step-by-Step Guide to Publish This Skill

### 1. Create GitHub Repository

1. Go to: https://github.com/new
2. Fill in:
   - **Repository name:** `adhd-daily-planner`
   - **Description:** "ADHD-optimized daily planning skill for Claude Code with realistic time estimates and energy-based task allocation"
   - **Visibility:** Public
   - **DO NOT** check any boxes (no README, .gitignore, or license - we already have these)
3. Click "Create repository"

### 2. Connect and Push

After creating the repository, GitHub will show you commands. Use these:

```bash
cd ~/Documents/claude-skills-publishing/adhd-daily-planner

# Add the remote (replace YOUR-USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/adhd-daily-planner.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3. Update README with Correct Links

After pushing, edit `README.md` and replace these placeholders:
- `YOUR-USERNAME` → your actual GitHub username

Find and replace all instances:
```bash
# In the README.md file, replace:
https://github.com/YOUR-USERNAME/adhd-daily-planner
# with:
https://github.com/youractualusername/adhd-daily-planner
```

Commit and push the update:
```bash
git add README.md
git commit -m "Update README with correct GitHub URLs"
git push
```

### 4. Add Topics (Tags) on GitHub

On your repository page:
1. Click the ⚙️ gear icon next to "About"
2. Add these topics:
   - `claude-code`
   - `claude-skill`
   - `adhd`
   - `productivity`
   - `daily-planning`
   - `time-management`
   - `ai-assistant`

### 5. Create a Release

1. Go to your repository on GitHub
2. Click "Releases" → "Create a new release"
3. Click "Choose a tag" → type `v1.0.0` → "Create new tag"
4. Release title: `v1.0.0 - Initial Release`
5. Description:
   ```
   ## 🎉 Initial Release

   ADHD-optimized daily planning assistant for Claude Code.

   ### Features
   - Realistic time estimation with startup, buffer, and transition costs
   - Energy-based task allocation (high/medium/low)
   - Anchor-focused planning (what would make today a win?)
   - ADHD-friendly principles (70% capacity, minimal context-switching)
   - Detailed examples and documentation

   ### Installation
   ```bash
   cd ~/.claude/skills/
   git clone https://github.com/YOUR-USERNAME/adhd-daily-planner.git
   ```

   See README.md for full documentation.
   ```
6. Click "Publish release"

### 6. Share Your Skill

Now that it's published, you can share it:

**On Social Media:**
```
I just published my first Claude Code skill! 🎉

ADHD Daily Planner helps with:
✅ Realistic time estimates (accounts for time blindness)
✅ Energy-based task allocation
✅ Planning for 70% capacity, not 100%

Perfect for anyone who struggles with executive function.

https://github.com/YOUR-USERNAME/adhd-daily-planner
```

**On Reddit** (r/ADHD, r/ClaudeAI):
```
Title: Created an ADHD-optimized daily planning tool for Claude Code

Body:
I struggle with time blindness and overplanning, so I created a Claude Code
skill that helps plan realistic daily schedules.

Key features:
- Breaks down tasks with startup time, buffer time, transitions
- Matches tasks to energy levels
- Plans for 70% capacity instead of aspirational 100%
- Focuses on ONE meaningful win per day

It's free and open source: [link]

Would love feedback from the community!
```

**On Anthropic Forum/Discord** (if available):
Share with other Claude Code users who might benefit.

### 7. Optional: Submit to Skill Directory

If Anthropic has an official skills marketplace or directory:
1. Check submission guidelines
2. Submit your skill for review
3. Follow any additional requirements

---

## Maintenance

### For Future Updates

When you make improvements:

1. **Update version in SKILL.md:**
   ```yaml
   version: 1.1.0
   ```

2. **Commit changes:**
   ```bash
   git add .
   git commit -m "Description of changes"
   git push
   ```

3. **Create new release** on GitHub with updated version number

### Accepting Contributions

If others contribute:
1. Review pull requests carefully
2. Test changes before merging
3. Update version number
4. Create new release
5. Thank contributors!

---

## Copyright Notice

You own the copyright to this work automatically. The MIT license means:
- ✅ Others can use it freely
- ✅ Others can modify it
- ✅ Others can distribute it
- ✅ You get attribution
- ❌ No warranty/liability on you

Your copyright is protected even if someone copies the code - they must include your copyright notice per the MIT license terms.

---

## Next Steps After Publishing

1. Monitor GitHub issues and discussions
2. Consider creating additional skills for related workflows
3. Share updates on social media as you improve it
4. Help users who have questions or issues
5. Collect feedback for version 2.0

Good luck! 🚀
