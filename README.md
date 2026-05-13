# AI SEO — A Claude Skill

A free Claude skill that helps you show up in **ChatGPT, Perplexity, Gemini, and Google's AI answers**.

Just install it, then ask Claude things like:

> "Audit my website for AI search."
> "Why am I not showing up in ChatGPT?"
> "How do I get my blog quoted by AI?"

Claude takes it from there.

---

## ⬇️ Download

**[Download the skill (ZIP)](https://github.com/abiodedeyi/ai-seo/releases/latest/download/ai-seo-skill.zip)**

Then follow the option below that matches how you use Claude.

---

## Where will you install it?

| You use Claude on… | Follow… | Difficulty |
|---|---|---|
| **Claude Desktop app** (the **Cowork** tab) | **Option A** | Easy |
| **claude.ai** in a web browser | **Option B** | Easy |
| **Claude Code** (terminal app) | **Option C** | A few extra steps |

Not sure which one you use? Most people use claude.ai in their browser → **Option B**.

---

## Option A — Install in Claude Desktop (Cowork) ⭐

1. Open the **Claude Desktop** app on your Mac or Windows PC.
2. Click the **Cowork** tab.
3. In the left sidebar, click **Customize**.
4. Click the **+** button → choose **Upload a skill**.
5. Select the **`ai-seo-skill.zip`** file you downloaded.
6. Toggle the skill **on**.

That's it. Start a new chat and try:

> "Audit my website for AI search."

> Don't have Claude Desktop yet? Download it at [claude.com/download](https://claude.com/download). Cowork is only available in the desktop app (not the web or mobile app).

---

## Option B — Install on Claude.ai (web)

1. Go to **[claude.ai](https://claude.ai)** and sign in.
2. In the sidebar, click **Customize → Skills**.
3. Click the **+** button → **+ Create skill** → **Upload a skill**.
4. Select the **`ai-seo-skill.zip`** file you downloaded.
5. Toggle it on. Done.

Start a new chat and try:

> "Audit my website for AI search."

> If you don't see "Upload a skill," make sure **Code execution** is enabled under **Settings → Capabilities**.

---

## Option C — Install on Claude Code (terminal)

If you have [Claude Code](https://claude.com/claude-code) installed:

### Step 1 — Open the skills folder

**On a Mac:**

1. Open **Finder**.
2. Press `Cmd` + `Shift` + `G`.
3. Paste: `~/.claude/skills/`
4. Press **Enter**.

**On a Windows PC:**

1. Open **File Explorer**.
2. Click the address bar at the top.
3. Paste: `%USERPROFILE%\.claude\skills\`
4. Press **Enter**.

> If the `skills` folder doesn't exist, create it inside the `.claude` folder.

### Step 2 — Drop the skill in

1. Open the ZIP file you downloaded.
2. Drag the **`ai-seo`** folder from inside the zip into your `skills` folder.

### Step 3 — Test it

1. Open **Terminal** (Mac) or **Command Prompt / PowerShell** (Windows).
2. Type `claude` and press **Enter**.
3. Type:

> "Help me show up in ChatGPT answers."

If Claude starts asking about your business and website — 🎉 it's working.

---

## How to use it

Just chat with Claude. The skill kicks in automatically when you ask about AI search. Try things like:

- "Audit my website for AI search."
- "Why am I not showing up in Google's AI answers?"
- "What should I change on my blog so ChatGPT quotes it?"
- "How do I get cited by Perplexity?"
- "My competitor shows up in AI answers and I don't. Fix it."
- "Check if my robots.txt is blocking AI bots."

If Claude doesn't pick it up automatically, just say: **"Use the ai-seo skill."**

---

## What's inside

A complete playbook on AI search optimization:

- How each AI platform (ChatGPT, Perplexity, Gemini, Google AI Overviews, Claude, Copilot) picks the sources it cites.
- The 3 things you need to win: **Structure**, **Authority**, **Presence**.
- A 9-tactic ranking table from Princeton's research — which optimizations actually boost AI visibility (and which ones *hurt* you).
- Content templates for "What is X?", "How to X", "X vs Y", FAQs, and more.
- How to check whether AI bots can even read your site (huge missed step).
- Which schema markup to add for which content type.
- A free monthly checklist for tracking your AI visibility without paid tools.

---

## Troubleshooting

**(Option A — Cowork) "Upload a skill" doesn't appear**

- Make sure you're on the **Cowork** tab (not the regular chat tab).
- Make sure your Claude Desktop app is updated to the latest version.

**(Option B — Web) "Upload a skill" doesn't appear**

- Make sure **Code execution** is enabled under **Settings → Capabilities**.
- Reload claude.ai after enabling it.

**(Option C — Claude Code) Claude doesn't seem to know about the skill**

- Folder must be named exactly `ai-seo` — no spaces, no capitals.
- Folder must sit *directly* inside the `skills` folder (not nested).
- Restart Claude Code (close it and run `claude` again).

**Can't find the `.claude` folder (Option C)**

The `.` at the start hides it by default.

- **Mac:** In Finder, press `Cmd + Shift + .` (period) to reveal hidden folders.
- **Windows:** In File Explorer, click the **View** tab → tick **Hidden items**.

---

## License

MIT. Use it, fork it, share it, remix it. No attribution required, but appreciated.

---

Built by [CodeFreeIQ](https://codefreeiq.com). Questions? abi@codefreeiq.com
