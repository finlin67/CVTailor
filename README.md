# Resume Tailor (Open Source)

Resume Tailor is a browser-based tool that helps you apply to jobs faster with stronger materials.

You paste:
- the job description
- your current resume

Then it helps you generate:
- a resume tailored to that role
- a cover letter
- a LinkedIn connection note
- a LinkedIn outreach message

Everything runs in your own browser tab. Your files are not uploaded to this repository or a project server.

## What You Need

- A browser (`Chrome`, `Edge`, `Firefox`, or `Safari`)
- One AI API key (Claude, ChatGPT, or Gemini)  
  - or `Ollama` if you want local/offline generation

## Quick Start (3 Steps)

1. **Download** this repository to your computer.
2. **Open** `index.html` in your browser.
3. **Paste** your API key into the key field and start tailoring.

## Privacy Note

This app is fully local. It does not send your data to a project-owned backend.

When you click generate, content is sent directly from your browser to the AI provider you selected (Anthropic, OpenAI, Google, or your local Ollama server).

## Screenshots

Add your screenshots here after first publish:

- `![Main screen](docs/images/main-screen.png)`
- `![Fit analysis](docs/images/fit-analysis.png)`
- `![Generated outputs](docs/images/generated-output.png)`

## Which AI Should I Use?

| Provider | Best For | Cost (light use) | Output Quality for Resume Tailoring | Sign Up |
|---|---|---|---|---|
| Claude | Strong writing tone and nuanced rewrites | Pay-per-use, low cost per request | Excellent for polished, human-sounding wording | [console.anthropic.com](https://console.anthropic.com) |
| ChatGPT (`gpt-4o`) | Balanced speed + quality | Pay-per-use, usually moderate | Very strong and consistent for resume + cover letter drafts | [platform.openai.com](https://platform.openai.com) |
| Gemini (`gemini-1.5-flash`) | Lower cost and fast turnaround | Often lowest paid cost, plus free-tier options | Good quality for most tailoring workflows | [aistudio.google.com](https://aistudio.google.com) |

If you are deciding where to start, Claude and ChatGPT usually produce the strongest first drafts for this use case, while Gemini is often the budget-friendly option for frequent iteration.

## Free/Offline Option: Ollama

You can run compatible local models through Ollama for no per-request API billing.

- Website: [ollama.com](https://ollama.com)
- Great when you want local control or when you prefer not to send resume data to a cloud API.

See `docs/SETUP.md` for the full Ollama walkthrough.

## FAQ

### Does this cost money?

The tool itself is free.  
Cloud AI providers charge based on usage. For most job search sessions, costs are typically low, but they are not zero.

### Is my data safe?

Your repository has no backend that stores your content. Data stays in your browser except when you send prompts to your chosen AI provider. Review that provider's policies before use.

### Does it work on Mac and Windows?

Yes. If you can open `index.html` in a browser, you can use the tool on both Mac and Windows.

### What if URL fetch does not work?

Some company career pages block scraping/proxy requests.

If that happens:
- copy the job description manually from the posting
- paste it into the Job Description box
- continue as normal

## Documentation

- Beginner setup: `docs/SETUP.md`
- API key setup: `docs/API_KEYS.md`

## Credits / Built By

Built by **[YOUR NAME HERE]**

- Website: `[your site link]`
- LinkedIn: `[your LinkedIn link]`
- GitHub: `[your GitHub link]`

