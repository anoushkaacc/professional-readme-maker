
# Build a Professional GitHub Profile README Using AI

A step-by-step guide to generating a structured, industry-ready GitHub profile README from your resume — using Claude and a ready-made template.

---

## What You Will End Up With

A GitHub profile README that:
- Presents your experience, projects, and tech stack with professional formatting
- Uses [Shields.io](https://shields.io/) badges for visual structure
- Displays live GitHub stats, streak, and top languages
- Looks polished without writing a single line of Markdown manually

---

## Prerequisites

- A GitHub account
- A repository named exactly `[your-github-username]/[your-github-username]` (this is your special profile repo)
- Your resume ready — either as a PDF, a `.docx`, or plain text

> **Create the profile repo:** Go to GitHub → New Repository → name it exactly the same as your username → check "Add a README" → Create.

---

## Step 1 — Download the Template

Download [`professional_github_readme_template`](./professional_github_readme_template) from this repository.

This is a structured Markdown template with placeholder text (`[Your Full Name]`, lorem ipsum descriptions, `[your-github-username]`, etc.) that Claude will fill in using your resume.

---

## Step 2 — Open Claude

Go to [claude.ai](https://claude.ai) and start a new conversation.

---

## Step 3 — Send This Prompt

Copy and paste the following prompt into Claude exactly as written:

```
I want to build a professional GitHub profile README. I am going to give you two things:
1. A Markdown template with placeholder text
2. My resume

Your job is to fill in the template using my resume. Follow these rules strictly:
- Replace all [bracketed placeholders] with real content from my resume
- Replace all lorem ipsum descriptions with accurate descriptions of my actual experience and projects
- Keep every section that exists in the template — do not add or remove sections
- Write project and experience descriptions in third-person professional prose, leading with the most impressive metric or outcome
- Generate correct Shields.io badge URLs for every technology mentioned in my resume
- Replace [your-github-username] with my actual GitHub username throughout, including in the stats card URLs
- Do not use emojis
- Output only the final Markdown, nothing else

Here is the template:

[PASTE THE CONTENTS OF profile-template.md HERE]

Here is my resume:

[PASTE YOUR RESUME TEXT HERE]
```

---

## Step 4 — Fill In Your Details

Before sending, replace the two placeholders at the bottom of the prompt:

**`[PASTE THE CONTENTS OF profile-template.md HERE]`**
Open `profile-template.md` and paste the full file contents.

**`[PASTE YOUR RESUME TEXT HERE]`**
Paste your resume as plain text, or copy-paste from your PDF. The more detail you include, the better the output.

Make sure the following information is present in your resume before sending — Claude needs all of these to fill the template correctly:

| Field | Example |
|---|---|
| Full name | - |
| Current or most recent role title | - |
| Organisation name and URL | - |
| Employment dates | Jan 2025 – Jun 2025 |
| Project names | - |
| GitHub repository names or links | - |
| Technologies and tools used | Python, GCP, WebSockets, Django |
| Quantified outcomes | 20x faster inference, 40% load time reduction |
| Degree, institution, and dates | B.Tech CSE |
| Email address | -@gmail.com |
| LinkedIn handle | linkedin.com/in/- |
| GitHub username | - |

---

## Step 5 — Copy the Output

Claude will return a complete, filled-in Markdown file. Copy the entire output.

---

## Step 6 — Paste Into GitHub

1. Go to your profile repository on GitHub (`github.com/[username]/[username]`)
2. Click the pencil icon to edit `README.md`
3. Select all existing content and delete it
4. Paste Claude's output
5. Click **Commit changes**

Your profile will update immediately.

---

## Step 7 — Fix Your GitHub Username in Stats Cards

Find these three lines in the README and confirm `[your-github-username]` has been replaced with your actual GitHub username:

```
https://github-readme-stats.shion.dev/api?username=[your-github-username]...
https://github-readme-stats.shion.dev/api/top-langs/?username=[your-github-username]...
https://streak-stats.demolab.com/?user=[your-github-username]...
```

If the stats cards show an error, this is almost always the cause.

---

## Files in This Repository

| File | Purpose |
|---|---|
| `professional_github_readme_template` | The blank template to paste into Claude |
| `README.md` | This guide |

---

## Credits

Badge generation via [Shields.io](https://shields.io/).
GitHub stats cards via [github-readme-stats](https://github.com/anuraghazra/github-readme-stats).
Streak stats via [github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats).
