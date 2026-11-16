# site: a real website for $0

the ai writes your whole site as one file, netlify drop puts it online with a real link. no card, no trial, no code.

heads up: you can do step 1 on your phone, but saving the file and putting it online is way easier on a laptop.

## how to use this

1. open https://chatgpt.com, https://claude.ai or https://gemini.google.com
2. paste the box below (fill in the [brackets] first) and send
3. ask for changes in plain words until you like it: "make it darker", "add my tiktok link", "bigger name". claude and gemini show you a live preview, in chatgpt ask it to "open this in canvas" to see it.
4. save the site as a file:
   - if there's a download button, use it and make sure the file is called `index.html`
   - no button? tap copy on the code box. on windows open notepad, paste, then file > save as, set "save as type" to "all files" and name it `index.html`. on a mac open textedit, hit format > make plain text first, paste, save as `index.html`.
5. make a new folder on your desktop called `mysite` and put `index.html` inside it. double-click the file, it should open in your browser looking like your site.
6. open https://app.netlify.com/drop, make a free account, and drag the `mysite` folder onto the page
7. it gives you a real live link. that's your site, done.

make the free account before you drop it, otherwise the site gets locked and deleted if you don't claim it within an hour. if your link asks friends to log in, open your site in netlify and switch its visibility to public in the settings.

## the starter prompt

```
You are my website builder. Build me a complete, working one-page site, not advice about websites.

MY INFO:
- Site type: [portfolio / club page / side hustle landing page / resume site]
- My name or brand: [name]
- What goes on it: [e.g. short bio, grid of my videos, contact button, my tiktok link]
- Vibe: [e.g. dark and clean, playful, minimal]

DO THIS:
1. Build the full site as ONE single file called index.html, with all the styling inside it. No frameworks, no separate files, nothing to install. It has to work when I just double-click the file.
2. Include: headline with my name, bio section, a section for my content, and a contact button.
3. Make it look right on a phone first, that's where people will see it.
4. Put clear placeholder spots for my links so I know where to paste them.
5. When it's built, list exactly what to change to make it mine.

RULES: One page, one file, fast. No stock photos of people, no fonts or assets that cost money. Everything editable without me knowing code. Whenever I ask for a change, give me the whole updated file again, not just the changed part.

OUTPUT: the full index.html in one code block, then a short "change this" list.

When done, ask me what to tweak: darker, bigger name, add a section.
```

## after it's live

want changes? ask the ai for the change, save the new `index.html` over the old one, then on netlify open your site > deploys and drag the folder in again. same link, updated site. swap portfolio for whatever you need: club page, side hustle landing page, resume site.
