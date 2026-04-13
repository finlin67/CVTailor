# Setup Guide (Beginner Friendly)

This guide walks you through everything from download to first generation.

## Before You Start

You need:
- a computer (Mac or Windows)
- a browser (`Chrome` or `Edge` recommended)
- one API key (Claude, ChatGPT, or Gemini)  
  See `docs/API_KEYS.md` for a full walkthrough.

---

## Part 1: Download the Project

1. Go to the repository page on GitHub.
2. Click the green **Code** button.
3. Click **Download ZIP**.
4. Open your Downloads folder.
5. Unzip the file (right-click -> Extract All on Windows, or double-click on Mac).

**Screenshot placeholder:**  
`[Add screenshot: GitHub Code button and Download ZIP]`

---

## Part 2: Open the Tool

1. Open the unzipped folder.
2. Double-click `index.html`.
3. Your browser should open Resume Tailor.

If double-click opens in the wrong app, right-click `index.html` and choose:
- **Windows:** Open with -> Chrome or Edge
- **Mac:** Open With -> Chrome

**Screenshot placeholder:**  
`[Add screenshot: index.html in folder]`

---

## Part 3: First-Run Setup Screen

At the top of the app:

1. Pick an AI provider from the **AI Provider** dropdown.
2. Paste your API key into the key field.
3. Confirm the status changes to **Ready**.

Use the **Get an API key** link next to the key field if you still need one.

**Screenshot placeholder:**  
`[Add screenshot: provider dropdown + API key field + Ready status]`

---

## Part 4: Paste Your Resume and Job Details

1. Paste your resume in **Base Resume**.
2. Paste the job description in **Job Description**.
3. Add company and role title.
4. Click **Analyze Fit & Generate**.

You will get:
- Tailored resume
- Cover letter
- LinkedIn connection note
- LinkedIn outreach message

**Screenshot placeholder:**  
`[Add screenshot: resume/job input fields]`

---

## Running with Ollama (Free, Offline)

Ollama lets you run AI models on your own machine. That means no cloud API key for generation calls.

### What is a terminal?

A terminal is a text-based window where you run commands.

- **Windows:** use **PowerShell** or **Command Prompt**
- **Mac:** use **Terminal** (Applications -> Utilities -> Terminal)

### Step-by-step Ollama setup

1. Install Ollama from [https://ollama.com](https://ollama.com)
2. Open a terminal.
3. Run these commands:

```bash
ollama pull llama3.1:8b
ollama serve
```

4. Keep that terminal window open while you use Resume Tailor.
5. In the app, choose **Ollama (local)** in the provider dropdown.
6. Keep host as `http://localhost:11434` unless you changed it.
7. Select a model and generate.

### If Ollama does not respond

- Confirm `ollama serve` is still running.
- Make sure no firewall or security tool is blocking local traffic.
- Try another model from the dropdown.

---

## Common First-Day Issues

### The page opens but buttons do nothing

Try Chrome or Edge first, then refresh.

### I get an API error

Double-check:
- provider selected in dropdown
- matching key pasted for that provider
- billing enabled (for paid APIs)

### URL fetch fails

Some job sites block scraping. Paste the job description manually and continue.

