# Quick Start: Publishing Your Skill

## ✅ What We've Done So Far

Your skill is ready to publish! Here's what's prepared:

```
adhd-daily-planner/
├── .git/                    # Git repository initialized ✓
├── .gitignore              # Ignore macOS and editor files ✓
├── CHANGELOG.md            # Version history tracker ✓
├── EXAMPLES.md             # Real-world usage examples ✓
├── PUBLISH.md              # Step-by-step publishing guide ✓
├── README.md               # Main documentation ✓
└── SKILL.md                # The actual skill with MIT license ✓
```

## 🚀 Next Steps (5 minutes)

### 1. Create GitHub Repository
1. Go to: https://github.com/new
2. Name: `adhd-daily-planner`
3. Visibility: **Public**
4. Don't initialize with anything (we have files already)
5. Click "Create repository"

### 2. Push Your Code
After creating the repo, GitHub will show you commands. Run:

```bash
cd ~/Documents/claude-skills-publishing/adhd-daily-planner
git remote add origin https://github.com/YOUR-USERNAME/adhd-daily-planner.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

### 3. Update README Links
Edit README.md and replace all instances of `YOUR-USERNAME` with your actual GitHub username.

```bash
# Open in your editor and find/replace:
# YOUR-USERNAME → youractualusername

git add README.md
git commit -m "Update README with correct GitHub URLs"
git push
```

### 4. Create Release
On GitHub:
1. Go to your repo → "Releases" → "Create a new release"
2. Tag: `v1.0.0`
3. Title: `v1.0.0 - Initial Release`
4. Copy description from PUBLISH.md
5. Click "Publish release"

### 5. Share!
Your skill is now published at:
```
https://github.com/YOUR-USERNAME/adhd-daily-planner
```

Share it on:
- Twitter/X
- Reddit (r/ADHD, r/ClaudeAI)
- Anthropic forums/Discord
- Your personal network

## 📋 Installation for Others

Others can install your skill with:

```bash
cd ~/.claude/skills/
git clone https://github.com/YOUR-USERNAME/adhd-daily-planner.git
```

Then use it with: `/adhd-daily-planner`

## 🔄 Making Updates Later

When you improve the skill:

1. Edit SKILL.md
2. Update version in SKILL.md frontmatter
3. Add entry to CHANGELOG.md
4. Commit and push:
   ```bash
   git add .
   git commit -m "Description of changes"
   git push
   ```
5. Create new release on GitHub with new version

## 💡 Pro Tips

### Add GitHub Topics
After publishing, add these topics to your repo:
- `claude-code`
- `claude-skill`
- `adhd`
- `productivity`
- `daily-planning`

(Click ⚙️ gear icon next to "About" on your repo page)

### Enable Discussions
Turn on GitHub Discussions for community Q&A:
- Settings → Features → Check "Discussions"

### Watch for Issues
Enable notifications to help users who have questions.

## 🎯 What Makes This Skill Valuable

Your skill solves real problems:
- ✅ Addresses time blindness (detailed estimates)
- ✅ Prevents overplanning (70% capacity rule)
- ✅ Matches energy to tasks
- ✅ ADHD-aware (exec function challenges)
- ✅ Produces actionable daily plans

This is genuinely helpful for people with ADHD!

## 📄 Your Rights

You own this skill. The MIT license means:
- ✅ Others can freely use it
- ✅ You get credit (attribution required)
- ✅ No liability on you
- ✅ Others can modify and share it

Your copyright is protected.

## 🆘 Need Help?

- **Publishing questions:** See PUBLISH.md
- **Git issues:** Google "git [your question]"
- **GitHub help:** https://docs.github.com

## 🎉 Congratulations!

You're about to share your work with the world. That's awesome!

Your skill can genuinely help people manage ADHD challenges.

Ready? Open PUBLISH.md and follow Step 1. 🚀
