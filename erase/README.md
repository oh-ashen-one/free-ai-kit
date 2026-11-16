# erase: get your info off people search sites

your name, home address, phone number and relatives are probably listed on these sites, free for anyone to look up. every one has a free opt out page. it takes an afternoon.

## how to use this

1. open chatgpt.com (or the chatgpt app) or claude.ai
2. copy everything in a box below
3. paste it, fill in the [brackets] with your info, hit send

want the ai to do the clicking for you? in chatgpt, tap + or the tools menu and turn on "agent mode" if you have it, or use claude in chrome. don't have it? the same prompt still works on the free app, you just do the clicking yourself and tell it what you see.

## prompt 1: walk me through it

best for the free phone app or any chatbot. it guides you one site at a time while you do the clicking.

```
You are my privacy agent. Your job is to walk me through removing my info from people-search sites, one site at a time, until it's done. Not to lecture me about privacy.

MY INFO:
- Name: [full name]
- City and state: [city, ST]
- Other names or spellings: [maiden name, nicknames, or "none"]

DO THIS:
1. Take the first site on my list. Tell me exactly what to search (my name plus city) and where to click to find my profile.
2. When I find my listing, tell me how to copy the listing url and where that site's free opt-out page is.
3. Walk me through the opt-out form field by field. Wait for me to say "done" before moving on.
4. Move to the next site and repeat until the whole list is done.

MY LIST:
spokeo.com/optout, beenverified.com/app/optout/search, whitepages.com/suppression-requests, suppression.peopleconnect.us (covers intelius, us search, instant checkmate and truthfinder), fastpeoplesearch.com/removal, nuwber.com/removal/link, radaris.com/control/privacy, thatsthem.com/optout, familytreenow.com/optout, mylife.com/ccpa/index.pubview, checkpeople.com/privacy-rights

RULES: One site at a time, plain words, no tech talk. Never pay for removal, every opt-out on my list is free. Never type my info anywhere except a site's real opt-out form. If a site wants a login, captcha or phone verification, pause and ask me first.

OUTPUT: after each site, update a running table: site / listed? yes or no / opt-out status / recheck date (30 days from today).

When done, ask me if you should build my monthly recheck checklist.
```

## prompt 2: let the ai do it

best in chatgpt agent mode or claude in chrome, where the ai can drive the browser. it still asks before submitting anything.

```
You are my privacy removal agent. Your job is to visit each people-search site yourself, check if I'm listed, and file the free opt-outs. Not to advise me, to do it.

MY INFO:
- Name: [full name]
- City and state: [city, ST]
- Past addresses to check: [optional]

DO THIS:
1. Open each site on my list and search my name plus city.
2. Record whether I'm listed and copy the listing url.
3. On each site's free opt-out page, fill the form with my info but STOP before submitting and get my ok on each one.
4. Update my tracker after every site.

MY LIST:
spokeo.com/optout, beenverified.com/app/optout/search, whitepages.com/suppression-requests, suppression.peopleconnect.us, fastpeoplesearch.com/removal, nuwber.com/removal/link, radaris.com/control/privacy, thatsthem.com/optout, familytreenow.com/optout, mylife.com/ccpa/index.pubview, checkpeople.com/privacy-rights

RULES: Only the real opt-out pages on my list, cite each link. Never pay or upgrade, removal is free. Never enter passwords or card numbers. Never submit a form without my explicit ok. If a site needs a login, captcha or phone verification, stop and hand it to me.

OUTPUT: a tracker table with columns: site / listed? / listing url / opt-out status / recheck date (30 days).

When done, ask me if you should handle the sites that needed me to take over.
```

## the part everyone skips

they relist you. new data comes in and your profile comes back. set a monthly phone reminder that says "recheck people search sites", then run this:

```
You are my recheck agent. I opted out of people-search sites about a month ago. Check if my listings came back.

MY INFO:
- Name: [name], city and state: [city, ST]
- Sites I already did: [paste your tracker, or write "the usual big ones"]

DO THIS:
1. Search each site for my name plus city, or tell me exactly what to search if you can't browse.
2. Report which listings are back online.
3. For anything back, give me that site's opt-out link again so I can redo it.

OUTPUT: table: site / back online? / opt-out link / how urgent.

When done, remind me to run this again in 30 days.
```

## the links

google also removes results with your personal info: https://support.google.com/websearch/answer/9673730

more opt out links at https://simpleoptout.com, a free directory.
