# ✍️ Communicate using Markdown

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

![GitHub Skills](https://img.shields.io/badge/GitHub-Skills-181717?style=for-the-badge&logo=github)
![Markdown](https://img.shields.io/badge/Markdown-Formatting-blue?style=for-the-badge&logo=markdown)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Self-Paced](https://img.shields.io/badge/Self--Paced-☕%20Anytime-orange?style=for-the-badge)

> **Hey vahlpahlelias-svg!** Mona here. I'm done preparing your exercise. Hope you enjoy! 💚  
> Remember, it's self-paced — feel free to take a break whenever you need! ☕️

[![Go to Exercise →](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/vahlpahlelias-svg/skills-communicate-using-markdown/issues/1)

---

## 📖 What You'll Learn

In this exercise you'll build a **personal blog post** step by step, practicing core Markdown skills along the way:

| Step | Skill | What You'll Do |
|------|-------|----------------|
| 1 | **Headings** | Create a `day-1.md` file with `#` and `##` headers |
| 2 | **Task Lists** | Add a to-do checklist under your morning planning section |
| 3 | **Code Blocks** | Save a code snippet with syntax highlighting |
| 4 | **Images** | Decorate your post with a sized, aligned image |
| 5 | **Pull Request** | Merge your blog post into `main` to finish 🎉 |

---

## 🚀 Quick Start

> **Prerequisites:** A GitHub account. No local tools are required — everything happens in the browser!

1. Click **[Go to Exercise →](https://github.com/vahlpahlelias-svg/skills-communicate-using-markdown/issues/1)** above.
2. Follow the instructions posted in the issue by Mona (the bot).
3. Each time you commit your work, Mona automatically checks it and unlocks the next step.

---

## 🤖 Agent Prompts — Getting Set Up

If you're using a **GitHub Copilot agent** (or any AI assistant) to help you get started, copy and paste one of these prompts:

<details>
<summary><strong>📋 Prompt: Fork & open this exercise</strong></summary>

```
I want to start the "Communicate using Markdown" GitHub Skills exercise.
Please help me:
1. Fork the repository at https://github.com/skills/communicate-using-markdown
2. Confirm that GitHub Actions are enabled on my fork (Settings → Actions → Allow all actions)
3. Open the auto-created Issue #1 in my fork so I can begin Step 1
```

</details>

<details>
<summary><strong>📋 Prompt: Enable GitHub Actions on my fork</strong></summary>

```
I forked https://github.com/skills/communicate-using-markdown but the
exercise bot (Mona) never posted instructions in Issue #1.
GitHub Actions may be disabled on my fork.
Please guide me to: Settings → Actions → General → "Allow all actions and
reusable workflows", then re-run the "Step 0" workflow so Mona can post
the first step instructions.
```

</details>

<details>
<summary><strong>📋 Prompt: Create the exercise branch and first file</strong></summary>

```
I'm on Step 1 of the Communicate using Markdown exercise.
I need to:
1. Create a branch called "start-blog" in my repository
2. Create a new file called "day-1.md" on that branch
3. Add a level-1 heading "# Daily Learning" and two level-2 headings
   "## Morning Planning" and "## Review"
4. Commit the file directly to the start-blog branch
Please walk me through each step using the GitHub web UI.
```

</details>

---

## 🛠️ Agent Prompts — Troubleshooting

If something isn't working as expected, paste the relevant prompt into your AI assistant:

<details>
<summary><strong>🐛 Mona never replied / no issue was created</strong></summary>

```
I forked the Communicate using Markdown exercise repo but Issue #1 was
never created and Mona never posted instructions.
Likely causes:
- GitHub Actions is disabled on my fork
- The "Step 0" workflow didn't trigger
Please help me:
1. Go to my repo's Settings → Actions → General and enable all actions
2. Go to the Actions tab, find the "Step 0" workflow, and manually
   trigger it (or push an empty commit to main to re-trigger it)
3. Verify Issue #1 now appears with Mona's instructions
```

</details>

<details>
<summary><strong>🐛 I committed day-1.md but Mona didn't advance to Step 2</strong></summary>

```
I committed day-1.md to the start-blog branch with the required headings,
but the exercise bot (Mona) hasn't advanced me to Step 2.
Please help me check:
1. Is the file named exactly "day-1.md" (lowercase, hyphen, not underscore)?
2. Is it committed to the "start-blog" branch (not main)?
3. Does it contain at least one "# " (level-1) heading with a space after #?
4. Does it contain at least two "## " (level-2) headings with a space after ##?
5. Did the "Step 1" GitHub Actions workflow run and pass? (Check the Actions tab)
If the workflow failed, show me the error log so I can fix the content.
```

</details>

<details>
<summary><strong>🐛 My code block / task list / image isn't being accepted</strong></summary>

```
I'm on Step [2 / 3 / 4] of the Communicate using Markdown exercise
and Mona is not accepting my submission.
Please review my day-1.md file on the start-blog branch and check:
- Step 2 (task list): Each item uses "- [ ]" or "- [x]" with a space inside
  the brackets and a space after the dash.
- Step 3 (code block): The block uses three backticks (```) not single quotes (''').
  The language hint (bash) is on the same line as the opening backticks.
- Step 4 (image): The <img> tag includes the src= attribute and is valid HTML.
Show me exactly what the content should look like so I can copy it in.
```

</details>

<details>
<summary><strong>🐛 Pull request won't merge / Step 5 not completing</strong></summary>

```
I'm on Step 5 of the Communicate using Markdown exercise.
I opened a pull request from "start-blog" into "main" and merged it,
but Mona hasn't posted the congratulations review.
Please help me:
1. Confirm the PR was merged (not just closed) using the GitHub UI.
2. Check the Actions tab for a "Step 5" workflow run and its status.
3. If the workflow failed, show me the error so I can fix it.
4. If it hasn't run at all, check that the "Step 5" workflow is enabled
   in Actions → Manage workflows.
```

</details>

<details>
<summary><strong>🐛 General: workflow stuck / not triggering</strong></summary>

```
A GitHub Actions workflow in my Communicate using Markdown exercise repo
is stuck or not triggering. Please help me:
1. Navigate to the Actions tab of my repo.
2. Check whether the relevant "Step N" workflow is enabled.
3. If disabled, enable it via the "..." menu next to the workflow name.
4. Identify the most recent workflow run, open it, and read the failure logs.
5. Based on the error, suggest the exact fix I need to make (file content,
   branch name, or settings change).
```

</details>

---

## 📚 Resources

| Resource | Link |
|----------|------|
| GitHub Markdown docs | [Basic writing and formatting syntax](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) |
| All GitHub Skills exercises | [skills.github.com](https://skills.github.com) |
| Continue learning: GitHub Pages | [github.com/skills/github-pages](https://github.com/skills/github-pages) |
| GitHub Getting Started | [docs.github.com/get-started](https://docs.github.com/get-started) |

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

