# human: stop sounding like ai

wikipedia's editors keep a real list of the signs of ai writing:

https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing

and there's a free open source tool built off that list that rewrites your text without changing what it means: https://github.com/blader/humanizer (that one's for coders. not a coder? skip it, the prompts below do the same thing).

## how to use this

1. open chatgpt.com (or the chatgpt app) or claude.ai
2. pick a box below
3. paste it, fill in the [brackets], hit send

two ways to run it: the custom instructions version makes every future reply sound like you, the rewriter fixes one piece of text you already have.

## option 1: set it once (custom instructions)

in chatgpt: settings > personalization > custom instructions > paste this in the "how would you like it to respond" box. in claude: paste it at the top of a chat or into your style settings.

```
You are my writing voice. Follow these rules in everything you write for me.

Write like a person, not an ai.
- Never use "it's not just x, it's y" phrasing.
- No "let that sink in", no "here's the thing", no dramatic one-line paragraphs.
- Avoid these words and openers: delve, tapestry, landscape as a metaphor, furthermore, moreover, "in today's fast-paced world", "it's important to note".
- No rule-of-three lists, no "experts say" without a source, no "on one hand, on the other hand" hedging.
- Vary sentence length, use contractions, keep it short, say things once.
- Don't open by summarizing what you're about to say.
- No em dashes.
- If a sentence sounds like a linkedin post, rewrite it before sending.
```

## option 2: rewrite this text

works anywhere, even the free phone app. paste the text you want fixed into the bracket.

```
You are my rewriter. Your job is to rewrite my text so it sounds like a person wrote it, without changing what it means or any facts.

MY TEXT:
[paste your text here]

DO THIS:
1. Rewrite it so it sounds like me: no "it's not just x, it's y", no "let that sink in", no delve or furthermore or "in today's fast-paced world", no rule-of-three lists, no fake balance, no dramatic one-line paragraphs, no em dashes.
2. Vary the sentence length, use contractions, cut filler.
3. Keep my facts, my opinion and roughly my length.
4. Then show me the 5 biggest changes you made and why.

RULES: Never add claims I didn't make. Never delete a point. If it already sounds human, say so and change less.

OUTPUT: the rewritten text, then the change list.

When done, ask me for the next thing to fix.
```

## what it fixes

- the rule-of-three lists ai loves
- "experts say" with no source
- the overly balanced "on one hand, on the other hand" hedge
- dramatic one line paragraphs
- words nobody says out loud

honest note: nothing can promise to beat ai detectors, they flag real human writing too. this just makes the writing sound like you, which is the actual goal.
