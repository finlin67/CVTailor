# API Keys Guide

This page shows where to create API keys and what to expect for cost.

## Quick Comparison

| Provider | Sign-up URL | Key format example | Light use ballpark |
|---|---|---|---|
| Anthropic (Claude) | [console.anthropic.com](https://console.anthropic.com) | `sk-ant-api03-...` | around `$0.003` per generation (varies by prompt size/model) |
| OpenAI (ChatGPT API) | [platform.openai.com](https://platform.openai.com) | `sk-...` | often a few cents for multiple runs, depends on model and length |
| Google (Gemini API) | [aistudio.google.com](https://aistudio.google.com) | `AIza...` | free tier available, then low pay-per-use pricing |

Costs change over time. Check each provider pricing page for current numbers.

---

## 1) Anthropic (Claude)

### Where to sign up

- Go to [https://console.anthropic.com](https://console.anthropic.com)
- Create an account and complete billing setup

### Where to find your key

1. Open the Anthropic Console
2. Go to API keys
3. Create a new key
4. Copy the key immediately

### What the key looks like

Starts with:

`sk-ant-api03-...`

### Cost (light use)

For resume tailoring workflows, a single generation is often around **$0.003** at smaller prompt sizes, and more for longer prompts or larger models.

---

## 2) OpenAI (ChatGPT API)

### Where to sign up

- Go to [https://platform.openai.com](https://platform.openai.com)
- Create an account
- Add billing to unlock full API usage

### Where to find your key

1. Open OpenAI Platform
2. Go to API keys
3. Create a new secret key
4. Copy and store it somewhere safe

### What the key looks like

Starts with:

`sk-...`

### Cost (light use)

Usually low for job-search level usage. A session with several generations is often in the cents range, depending on prompt length and model pricing.

---

## 3) Google (Gemini API)

### Where to sign up

- Go to [https://aistudio.google.com](https://aistudio.google.com)
- Sign in with your Google account

### Where to find your key

1. Open Google AI Studio
2. Click **Get API key**
3. Create/select a project
4. Copy generated key

### What the key looks like

Starts with:

`AIza...`

### Cost (light use)

Gemini usually offers a free tier, which is enough for many personal tests. Paid usage is available after that, typically at low per-request cost.

---

## Safety Tips for API Keys

- Treat API keys like passwords.
- Do not post keys in screenshots.
- Do not commit keys into GitHub repositories.
- If a key is exposed, revoke it and create a new one.

