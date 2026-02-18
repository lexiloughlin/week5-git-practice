# Week 5 Git Practice Assignment - Student Instructions

## 📚 What You'll Learn

By completing this assignment, you will:
- ✅ Practice forking repositories on GitHub
- ✅ Clone a repository to your computer
- ✅ Make multiple commits with good messages
- ✅ Push your work to GitHub
- ✅ Use the complete Git workflow
- ✅ Build your GitHub portfolio

---

## 🎯 Assignment Overview

**Points:** 100  
**Submission:** GitHub repository URL on Canvas

You will complete a practice notebook that guides you through essential Python and Git concepts while practicing the Git workflow you learned this week.

---

## 📋 Step-by-Step Instructions

### Step 1: Fork the Repository

**What is forking?** Creating your own copy of someone else's repository.

1. **Go to the instructor's repository:**
   - `https://github.com/allengwinn/week5-git-practice`

2. **Click the "Fork" button**
   - Located in the top-right corner
   - Looks like a fork icon with a number

3. **Wait for fork to complete**
   - GitHub creates YOUR copy
   - URL changes to: `github.com/YOUR-USERNAME/week5-git-practice`
   - Notice: YOUR username, not instructor's!

4. **Verify it worked:**
   - You should see: "forked from instructor-name/week5-git-practice"
   - You now have YOUR OWN copy

---

### Step 2: Clone YOUR Fork Using VS Code (Not the Instructor's!)

⚠️ **IMPORTANT:** Clone YOUR fork, not the instructor's repository!

**Method 1: Using VS Code Source Control (RECOMMENDED)**

1. **Open VS Code**

2. **Click the Source Control icon** in the left sidebar (looks like a branch with circles)
   - Or press: `Ctrl+Shift+G` (Windows/Linux) or `Cmd+Shift+G` (Mac)

3. **Click "Clone Repository" button**
   - You'll see a big button in the Source Control panel

4. **Click "Clone from GitHub"**
   - VS Code may ask you to sign in to GitHub
   - Click "Allow" if prompted
   - Sign in with your GitHub account

5. **Search for YOUR repository:**
   - Type: `YOUR-USERNAME/week5-git-practice`
   - You should see YOUR fork in the list
   - **NOT the instructor's** - make sure it has YOUR username!
   - Click on YOUR repository

6. **Choose where to save it:**
   - Browse to your Documents or Desktop
   - Or create a "Python-Course" folder
   - Click "Select as Repository Destination"

7. **Open the repository:**
   - VS Code will ask "Would you like to open the cloned repository?"
   - Click "Open"

8. **Verify it worked:**
   - You should see `week5-git-practice` in the Explorer panel
   - Look for `week5_git_practice.ipynb` in the file list

**Method 2: Using Command Palette (Alternative)**

1. **Open VS Code**

2. **Press:** `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac)

3. **Type:** "Git: Clone"

4. **Select:** "Clone from GitHub"

5. **Choose YOUR repository:**
   - Look for: `YOUR-USERNAME/week5-git-practice`
   - NOT: `allengwinn/week5-git-practice`

6. **Choose location and open** (same as Method 1)

---

### Step 3: Complete the Notebook

1. **Open the notebook:**
   - In VS Code, click on `week5_git_practice.ipynb`

2. **Read the instructions carefully**
   - Each section has clear instructions
   - There are 5 sections total

3. **Complete Section 1:**
   - Fill in your personal information
   - Save the file (Ctrl+S or Cmd+S)
   - **Make your first commit** (see Step 4 below)

4. **Repeat for each section:**
   - Complete Section 2 → Save → Commit → Push
   - Complete Section 3 → Save → Commit → Push
   - Complete Section 4 → Save → Commit → Push
   - Complete Section 5 → Save → Commit → Push

---

### Step 4: Commit and Push (Do This After EACH Section!)

**The Git Workflow - Follow This Every Time:**

#### 4A. Save Your Changes
- Press `Ctrl+S` (Windows/Linux) or `Cmd+S` (Mac)
- Make sure file is saved!

#### 4B. Open Source Control
- Click the branch icon in left sidebar
- Or press: `Ctrl+Shift+G` (Windows/Linux) or `Cmd+Shift+G` (Mac)

#### 4C. Stage Your Changes
- You'll see `week5_git_practice.ipynb` listed
- Click the `+` icon next to it
- File moves to "Staged Changes"

#### 4D. Write a Commit Message
- In the message box at top, type a GOOD message
- Examples:
  - ✅ "Add personal information to Section 1"
  - ✅ "Complete Python practice in Section 2"
  - ✅ "Answer Git knowledge questions in Section 3"
  - ❌ "update" (too vague!)
  - ❌ "changes" (not descriptive!)
  - ❌ "asdf" (not helpful!)

#### 4E. Commit
- Press `Ctrl+Enter` (Windows/Linux) or `Cmd+Enter` (Mac)
- Or click the ✓ checkmark above message box

#### 4F. Push to GitHub
- Click the "Sync Changes" button
- Or click the `...` menu → Push
- Enters your work to GitHub!

#### 4G. Verify It Worked
- Go to YOUR repository on GitHub
- Click "commits" link
- You should see your new commit!

**Repeat this workflow after completing EACH section!**

---

### Step 5: Final Checks

Before submitting, verify:

- [ ] **All 5 sections are complete**
  - No "[Your answer here]" left
  - All code cells work
  - All questions answered

- [ ] **Made at least 5 commits**
  - Go to GitHub → click "commits"
  - Count them: Need 5 or more
  - Each section should be its own commit

- [ ] **Commit messages are descriptive**
  - Not vague ("update", "fix", "changes")
  - Describe what you did
  - Future you will thank you!

- [ ] **Everything is pushed to GitHub**
  - Visit your repository on GitHub
  - You can see all your changes
  - Notebook shows your completed work

- [ ] **Outputs are cleared** (if asked in instructions)
  - In notebook: Cell → All Output → Clear
  - Keeps repository clean
  - Make final commit: "Clear outputs before submission"

---

### Step 6: Submit on Canvas

1. **Go to your GitHub repository**
   - URL format: `https://github.com/YOUR-USERNAME/week5-git-practice`

2. **Copy the URL** from your browser address bar

3. **Go to Canvas assignment**

4. **Paste YOUR repository URL**
   - Make sure it's YOUR username, not the instructor's!
   - Double-check the URL before submitting

5. **Submit!**

---

## ❓ Common Questions

### Q: Do I fork or clone first?
**A:** Fork FIRST (on GitHub), then clone YOUR fork (to your computer).

### Q: Why can't I push?
**A:** Most common reason - you cloned the instructor's repository instead of YOUR fork. 

**To fix:**
1. Close VS Code
2. Delete the local folder
3. Make sure you FORKED on GitHub first (click Fork button)
4. Open VS Code
5. Use Source Control → Clone Repository → Clone from GitHub
6. Select YOUR fork (YOUR-USERNAME/week5-git-practice)
7. Try again

### Q: How many commits should I make?
**A:** At least 5. Best practice: one commit per section. More is better!

### Q: What if I make a mistake in my commit?
**A:** That's okay! Make another commit to fix it. That's how Git works.

### Q: Can I delete commits?
**A:** Yes, but don't worry about it for this assignment. Extra commits are fine.

### Q: Do I need to clear outputs?
**A:** Only if specifically instructed. For this assignment, check the notebook instructions.

### Q: What if my code doesn't work?
**A:** Debug it! Run the cell, read the error, fix it. Use Copilot to help. Ask questions in office hours.

### Q: Can I use Copilot?
**A:** Yes! This is an AI-assisted course. Use Copilot to help write code and understand Git commands.

---

## ⚠️ Common Mistakes to Avoid

### Mistake #1: Cloning the wrong repository
- ❌ **Wrong:** Cloning `instructor/week5-git-practice`
- ✅ **Right:** Cloning `YOUR-USERNAME/week5-git-practice`

**How to check in VS Code:**
- Look at the bottom-left corner of VS Code
- You should see a branch icon and text
- Open Source Control panel
- Click the "..." menu → Show Git Output
- Look for the repository URL - should have YOUR username

**Fix:** 
1. Close VS Code
2. Delete the local folder
3. Fork the repository on GitHub first
4. Clone YOUR fork using Source Control panel

### Mistake #2: One giant commit
- ❌ **Wrong:** Complete all 5 sections, then make 1 commit
- ✅ **Right:** Complete each section, commit after each one

**Why it matters:** Practice the workflow! In projects, you'll commit frequently.

### Mistake #3: Vague commit messages
- ❌ **Wrong:** "update", "changes", "fix", "asdf"
- ✅ **Right:** "Add personal information to Section 1"

**Why it matters:** Good messages help you and teammates understand what changed.

### Mistake #4: Not pushing to GitHub
- ❌ **Wrong:** Commit locally but forget to push
- ✅ **Right:** Commit AND push after each section

**How to check:** Visit your repository on GitHub. Can you see your commits?

### Mistake #5: Submitting wrong URL
- ❌ **Wrong:** Submitting the instructor's repository URL
- ✅ **Right:** Submitting YOUR fork's URL

**Double-check:** Does the URL have YOUR username?

---

## 🎓 Grading Rubric

**Total: 100 points**

### Completion (50 points)
- All 5 sections complete and thoughtful: 12 pts
- Most sections complete: 9-11 pts
- Some sections complete: 5-8 pts
- Few sections complete: 1-4 pts

### Git Workflow (25 points)
- 5+ commits with descriptive messages: 5 pts
- 5+ commits with some vague messages: 3-4 pts
- Fewer than 5 commits: 1-2 pts
- One giant commit: 0-1 pts

### Pushed to GitHub (25 points)
- Successfully pushed, visible on GitHub: 3 pts
- Not pushed or incorrect URL: 0 pts

---

## 🆘 Getting Help

### Before You Ask:
1. **Read the error message** carefully
2. **Check the instructions** again
3. **Look at the Git Quick Reference** (on Canvas)
4. **Ask Copilot:** "How do I [git operation]?"

### Where to Get Help:
- **Office Hours:** [See Canvas for schedule]
- **Email Instructor:** [instructor email]
- **Class Discord/Slack:** [link if applicable]
- **Canvas Discussions:** Ask questions, help classmates

### When to Ask:
- Git commands not working
- Can't push to GitHub
- Confused about workflow
- Code not running
- Any Git or GitHub issues!

**Don't struggle alone - ask for help early!**

---

## 💡 Tips for Success

### Time Management
- **Start early** - Don't wait until the due date
- **Do one section at a time** - Don't rush through all 5
- **Commit often** - After each section or even more frequently
- **Push regularly** - Don't wait until the end

### Git Best Practices
- **Pull before starting** (in case repository updated)
- **Write clear commit messages** while you remember what you did
- **Push frequently** - cloud backup of your work
- **Check GitHub** to verify pushes worked

### Learning Mindset
- **It's okay to make mistakes** - that's how you learn!
- **Every professional uses Git** - you're learning valuable skills
- **Practice makes perfect** - the more you commit, the more natural it becomes
- **Help your classmates** - teaching others helps you learn

---

## 🎉 After You're Done

Congratulations! You've practiced the complete Git workflow!

### What You Accomplished:
- ✅ Forked a repository
- ✅ Cloned it to your computer
- ✅ Made multiple commits
- ✅ Wrote good commit messages
- ✅ Pushed to GitHub
- ✅ Built your GitHub portfolio

---

## 📚 Additional Resources

### Git Basics:
- Git Cheat Sheet (on Canvas)
- GitHub Quickstart Guide: https://docs.github.com/en/get-started/quickstart
- VS Code Git Tutorial: https://code.visualstudio.com/docs/sourcecontrol/intro-to-git

### Interactive Learning:
- Learn Git Branching: https://learngitbranching.js.org/
- GitHub Learning Lab: https://lab.github.com/

### When You're Stuck:
- GitHub Docs: https://docs.github.com
- Stack Overflow: Search your error message
- Copilot: Ask "How do I [git task]?"

---

## ✅ Quick Checklist

**Before starting:**
- [ ] I forked the instructor's repository
- [ ] I cloned MY fork (not instructor's)
- [ ] I opened the notebook in VS Code

**While working:**
- [ ] Complete Section 1 → Commit → Push
- [ ] Complete Section 2 → Commit → Push
- [ ] Complete Section 3 → Commit → Push
- [ ] Complete Section 4 → Commit → Push
- [ ] Complete Section 5 → Commit → Push

**Before submitting:**
- [ ] All 5 sections complete
- [ ] At least 5 commits made
- [ ] Good commit messages (not vague)
- [ ] Everything pushed to GitHub
- [ ] I can see my work on GitHub.com
- [ ] I'm submitting MY fork URL (not instructor's)

**Submission:**
- [ ] Copied MY repository URL
- [ ] Submitted on Canvas
- [ ] Double-checked it's the right URL

---

**Good luck! You've got this!** 🚀

**Remember:** Everyone struggles with Git at first. It gets easier with practice. Ask questions when you need help!

---

*Student Instructions Version 1.0 - Week 5 Git Practice Assignment*
*Last updated: February 2026*
