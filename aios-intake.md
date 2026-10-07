# AIS-OS Intake

This is the source-of-truth file for your AIOS. Fill it in by typing, voice-pasting (Wispr Flow / OS dictation), or running `/onboard` for a guided conversation. Whichever mode, this file is what `/onboard` reads to scaffold your Day-1 setup.

**Hard cap: 7 questions.** Each answerable in under 60 seconds. Don't overthink — you can edit and re-run `/onboard` any time.

---

## Q1 — Who are you, what do you sell, who do you sell it to?

Identity, offer, ICP. One paragraph each is fine.

```
I am Nguyen Hoang Son, a solopreneur offering AI consulting and implementation for businesses that want to adopt AI in their operations.
```

---

## Q2 — Paste 1-2 things you've written recently. Don't edit them.

An email, a LinkedIn post, a DM, a doc — anything that sounds like you when you're not trying. **Paste verbatim.** Do not type these mid-conversation with Claude — chat-shaped samples are worse than no samples (voice contamination).

```
Hi, I'm Son.

I recently noticed a blog on your website about AI, I'm impressed by your point: 'AI is a multiplier, not a strategist. It amplifies whatever you feed it. Which mean the real question is not 'which AI tool should I use', it is 'what am I actually feeding it'.'
But, it seems like you still use it like a chatbot (maybe use it to do some small tasks). If you wanna chat about how to build an AI operating system to streamline your workflow, where AI can 'does' task, feel free to hop on a brief call with me
```

```
Hi, I'm Son.
I recently read one of your blogs on your website: Will SEO Be Replaced by AI? and you said that AI tools now can answer question instantly, Summarize complex topics, Generate blog posts, product descriptions, blabla.
Not thing is wrong, but it seems like you still chat with it, then it generates an answer, and you use that answer to do the work by yourself. If you wanna know how to integrate AI into your workflow to make it 'automatic', let's chat about it in a brief call.
```

---

## Q3 — What are your 2-3 biggest priorities for the next 90 days?

Quarterly priorities. Not yearly aspirations. Things that, if not done by July, would make you say "I wasted Q2."

```
1. Close my first client.
2. Document how I work with clients and post it on Instagram to build proof and attract more clients.
```

---

## Q4 — Where does revenue actually land, and where is it tracked?

Multiple answers OK. Stripe? Skool? GoHighLevel? QuickBooks? A spreadsheet?

```
Revenue is tracked in a spreadsheet.
```

---

## Q5 — Where do you talk to customers, your team, and the outside world day-to-day?

Email, Instagram, and Notion.

```
[Your answer here]
```

---

## Q6 — Where do meeting recordings, notes, and important docs live?

Granola? Otter? Fireflies? Google Drive? Notion? Dropbox? A folder on your desktop you keep meaning to organize?

Meeting recordings, notes, and important documents live locally.

```
[Your answer here]
```

---

## Q7 — What's the one task that eats your week, and where do you currently track work?

The single biggest time-suck or recurring drudgery. Plus where tasks/projects live (ClickUp / Asana / Linear / Notion / a notebook).

My biggest time-suck is cold email outreach and follow-ups. Work is tracked in Notion.

```
[Your answer here]
```

---

When this file is filled, run `/onboard` (or re-run it) and the wizard will scaffold your Day-1 file set: `context/`, `references/voice.md`, populated `connections.md`, and a filled `CLAUDE.md`.
