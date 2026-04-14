# Resume Tailor (Open Source)

**Resume Tailor** is a lightweight, browser-based tool that helps you turn *one* resume into a role-specific application package—fast.

Paste:
- a job description
- your current resume

Generate:
- a tailored resume draft
- a cover letter draft
- a LinkedIn connection note
- a LinkedIn outreach message

**No accounts. No backend.** It runs in your browser tab—your files aren’t uploaded to this repository or any project server.

---

## Why this exists

Applying well takes time: reading the posting, matching keywords, rewriting bullets, adjusting tone, writing a cover letter, and then doing LinkedIn outreach.

Resume Tailor focuses on the repetitive parts so you can spend your energy where it matters:
- refining your story
- verifying accuracy
- customizing details that *should* be human

---

## Features

- **Local-first**: open `index.html` and run it immediately
- **Multiple AI providers**: Claude, ChatGPT, Gemini, or local models via **Ollama**
- **Practical outputs**: resume + cover letter + LinkedIn messaging in one flow
- **Privacy by design**: no project-owned backend storing your content

---

## Quick Start (3 steps)

1. **Download** (or clone) this repository.
2. **Open** `index.html` in your browser (`Chrome`, `Edge`, `Firefox`, or `Safari`).
3. **Paste** your API key, choose a provider, and start tailoring.

---

## Privacy & Data Handling

This app is fully local and does not send your data to a project-owned backend.

When you click **Generate**, the text you provided is sent **directly from your browser** to the AI provider you selected:
- Anthropic (Claude)
- OpenAI (ChatGPT)
- Google (Gemini)
- or your local Ollama server (if configured)

If privacy is your top priority, consider using **Ollama** for local/offline generation.

---

## Screenshots

Add screenshots to `docs/images/` and update these paths:

- `![Main screen](docs/images/main-screen.png)`
- `![Fit analysis](docs/images/fit-analysis.png)`
- `![Generated outputs](docs/images/generated-output.png)`

---

## Which AI should I use?

| Provider | Best For | Cost (light use) | Output Quality for Resume Tailoring | Sign Up |
|---|---|---|---|---|
| Claude | Strong tone + nuanced rewrites | Pay-per-use, low cost per request | Excellent for polished, human-sounding wording | https://console.anthropic.com |
| ChatGPT (`gpt-4o`) | Balanced speed + quality | Pay-per-use, usually moderate | Very strong + consistent drafts | https://platform.openai.com |
| Gemini (`gemini-1.5-flash`) | Speed + lower cost | Often lowest paid cost, plus free-tier options | Great for frequent iteration | https://aistudio.google.com |

If you’re not sure where to start: **Claude** and **ChatGPT** typically produce the strongest first drafts for this use case; **Gemini** is often the budget-friendly option for lots of iterations.

---

## Free / Offline option: Ollama

Use compatible local models through **Ollama** for no per-request API billing.

- Website: https://ollama.com  
- Great when you want local control or prefer not to send resume data to a cloud API.

See `docs/SETUP.md` for the full Ollama walkthrough.

---

## FAQ

### Does this cost money?
The tool itself is free.

Cloud AI providers charge based on usage. For most job search sessions, costs are usually low—but not zero.

### Is my data safe?
This project has no backend that stores your content.

Your text stays in your browser except when you send prompts to your chosen AI provider. Review that provider’s data policies if you have strict privacy requirements.

### Does it work on Mac and Windows?
Yes. If you can open `index.html` in a browser, you can use it on Mac or Windows.

### What if URL fetch doesn’t work?
Some company career pages block scraping/proxy requests.

If that happens:
- copy the job description manually from the posting
- paste it into the **Job Description** box
- continue as normal

---

## Documentation

- Beginner setup: `docs/SETUP.md`
- API key setup: `docs/API_KEYS.md`

---

## Contributing

Issues and pull requests are welcome—especially for:
- better prompt templates
- UI improvements
- provider/model compatibility
- clearer setup docs and screenshots

---

## Credits

Built by **finlin67**  
GitHub: https://github.com/finlin67