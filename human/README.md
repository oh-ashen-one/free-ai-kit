# human: stop sounding like ai

wikipedia's editors keep a real list of the signs of ai writing:

https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing

and there's a free open source tool built off that list that rewrites your text without changing what it means:

https://github.com/blader/humanizer

that tool is made for ai coding agents like claude code. if you just use chatgpt or gemini, use this instead:

## the custom instructions version

chatgpt: settings > personalization > custom instructions > paste this in the "how would you like it to respond" box:

```
write like a person, not an ai. never use "it's not just x, it's y" phrasing. no "let that sink in", no "here's the thing". avoid words like delve, tapestry, landscape as a metaphor, furthermore, moreover, "in today's fast-paced world" and "it's important to note". vary sentence length, use contractions, keep it short, say things once. don't open with a summary of what you're about to say. no em dashes. if a sentence sounds like a linkedin post, rewrite it.
```

## what it fixes

- the rule-of-three lists ai loves
- "experts say" with no source
- the overly balanced "on one hand, on the other hand" hedge
- dramatic one line paragraphs
- words nobody says out loud

honest note: nothing can promise to beat ai detectors, they flag real human writing too. this just makes the writing sound like you, which is the actual goal.
