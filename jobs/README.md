# jobs: let ai do the job hunt

three prompts that take you from "what can i even apply to" to a tailored resume and a tracker. free tier works for all of it.

## how to use this

1. open chatgpt.com (or the chatgpt app) or claude.ai
2. copy everything in a box below
3. paste it, fill in the [brackets], hit send

in chatgpt, agent mode (the + or tools menu, only on paid plans, skip it if you don't see it) lets the ai search real job boards itself. on the free app it'll ask you to paste in postings, still works.

## prompt 1: find jobs i actually qualify for

best in chatgpt agent mode or claude in chrome (both paid) for pulling live postings. free tier works if you paste in listings it asks for.

```
You are my job-hunting agent. Your job is to find real job postings I qualify for, not to explain how job hunting works.

MY INFO:
- My resume: [PASTE YOUR RESUME HERE]
- Location: [city, state, or "remote only"]
- Must-haves: [e.g. part-time, no degree required, $18+/hr]

DO THIS:
1. Read my resume. List 10 job titles I actually qualify for, including ones I wouldn't think to search for.
2. For the 3 best titles, find real postings from the last 7 days on indeed.com and linkedin.com/jobs. Open actual postings, not search result pages.
3. Score each posting out of 10 for fit against my resume, one line on why.
4. List the top keywords each posting's recruiter is probably filtering for.

RULES: Only real postings you actually opened, cite a link for each. Never invent a company, salary or posting. Never enter passwords or card numbers. Ask me before submitting any application or form. If a site needs a login or captcha, stop and tell me.

OUTPUT: a table with columns: job title / company / link / fit score / why / keywords i'm missing. Then a second table as my tracker: company / role / link / date applied / follow-up date / status.

When done, ask me which postings to tailor my resume for.
```

## prompt 2: tailor my resume to a posting

works anywhere, even the free phone app. run it fresh for every posting.

```
You are my resume tailor. Rewrite my resume to match one job posting using only true things about me.

MY INFO:
- My resume: [PASTE RESUME]
- The posting: [PASTE THE POSTING OR ITS LINK]

DO THIS:
1. Pull the top 10 keywords and requirements from the posting.
2. Rewrite my resume to match them, one page max. Same facts, better wording, most relevant bullets on top.
3. Flag anything the posting wants that I don't have, so nothing surprises me in the interview.

RULES: Never invent experience, degrees or skills. Keep it one page.

OUTPUT: the full rewritten resume, then 3 bullets on what you changed and why, then the gaps list.

When done, ask me for the next posting.
```

## prompt 3: tracker

```
Make me a job application tracker I can paste into google sheets.

Columns: company / role / link / date applied / follow-up date (7 days after applying) / status / notes.

Fill in these jobs so far: [list them, or write "none yet"]. Plain table I can copy.
```

follow up when the tracker says to, that's where interviews come from.
