---
name: new-app
description: "Use this skill whenever the user wants to start a new app, project, or tool — even if they phrase it casually. Trigger on phrases like \"I want to build an app for X\", \"let's start a new project\", \"create a new app\", \"I have an idea for an app\", \"set up a new project for X\", or \"start a new tool\". This skill automates the full local setup: it creates the design folder structure, drops in a ready-to-fill PRD template, and scaffolds the Next.js project — so the user can go from idea to running code in one conversation."
---
 
# New App Setup Skill
 
When the user says they want to create a new app or start a new project, this skill handles the full local setup automatically. Your job is to ask a few quick questions, then run the setup on their machine.
 
## Step 1 — Gather inputs
 
Use the `AskUserQuestion` tool to ask:
 
1. **App name** — what should the project folder be called? (lowercase, hyphens, e.g. `sar-field-guide`)
2. **Where to create the project** — offer these options:
   - Projects folder (`~/Projects/`) — recommended default
   - Other (let them type a path)
3. **Does this app need a content folder?** — for apps that read from local files (docs, data, markdown). Yes or No.
Keep it to one `AskUserQuestion` call with all three questions at once.
 
## Step 2 — Create the design folder
 
Once you have the app name, create the design folder structure:
 
```bash
mkdir -p ~/Design/[app-name]/{research,wireframes,mockups,assets}
```
 
Then copy the PRD template in, renamed and ready to fill out:
 
```bash
cp ~/Projects/templates/prd-template-v2.md ~/Design/[app-name]/prd.md
```
 
If `~/Projects/templates/prd-template-v2.md` doesn't exist, skip copying it and note this to the user.
 
## Step 3 — Scaffold the Next.js project
 
Run `create-next-app` non-interactively with all the right flags. Use the destination they chose in Step 1:
 
```bash
cd [destination] && npx create-next-app@latest [app-name] \
  --typescript \
  --eslint \
  --tailwind \
  --src-dir \
  --app \
  --no-import-alias \
  --yes
```
 
This takes ~30 seconds. Let the user know it's running.
 
## Step 4 — Set up content folder (if needed)
 
If the user said yes to a content folder, create it inside the project:
 
```bash
mkdir -p [destination]/[app-name]/content
```
 
Then tell the user: "When you're ready to add your docs or data files, copy them into the `content/` folder inside your project."
 
## Step 5 — Report back
 
Give the user a clear summary of what was created. Use this structure:
 
---
**Done! Here's what was set up:**
 
📁 **Design folder:** `~/Design/[app-name]/`
- `research/`, `wireframes/`, `mockups/`, `assets/`
- `prd.md` — your PRD template, ready to fill out
💻 **Project:** `[destination]/[app-name]/`
- Next.js + TypeScript + Tailwind, App Router
- `content/` folder ready for your docs *(if they said yes)*
**Your next steps:**
1. Fill out the PRD — talk through the idea here first, then capture it in `~/Design/[app-name]/prd.md`
2. Start the dev server: `cd [destination]/[app-name] && npm run dev`
3. Open [http://localhost:3000](http://localhost:3000) to confirm it works
4. Push to GitHub when ready — come back here and I'll walk you through it
---
 
## Notes
 
- If `npx create-next-app` fails because Node.js isn't installed, tell the user to install it from [nodejs.org](https://nodejs.org) (LTS version), then try again.
- The `--yes` flag makes the setup non-interactive. If for some reason it still prompts, the user should answer: TypeScript yes, ESLint yes, Tailwind yes, src/ yes, App Router yes, import alias no.
- Keep the tone friendly and practical — the user is a designer learning this workflow, not a seasoned developer.
