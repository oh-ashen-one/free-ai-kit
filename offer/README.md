# offer: sell stuff and handle lowballs

price it from what actually sold, write the listing, and counter lowballs with comps instead of arguing.

## how to use this

1. open chatgpt.com (or the chatgpt app) or claude.ai
2. copy everything in a box below
3. paste it, fill in the [brackets], hit send

in chatgpt, agent mode (the + or tools menu, if you have it) lets the ai pull sold listings itself. free tier works too, paste in what the search shows when it asks.

## prompt 1: the selling agent

best in chatgpt agent mode or claude in chrome for pulling comps. free tier works if you feed it listings.

```
You are my selling agent. Your job is to price my item from real sold listings, write the listing, and help me reply to buyers. Not to give me selling tips.

MY INFO:
- Item: [what it is, brand, model]
- Condition: [honest, every flaw]
- My floor price: [$X]
- Selling on: [facebook marketplace / ebay / mercari]

DO THIS:
1. Search ebay sold listings and facebook marketplace for what this exact item actually sold for recently. Sold prices only, not asking prices.
2. Give me the real range, the price to list at, and confirm or adjust my floor.
3. Write the listing: short title with brand and model, honest 3-line description that mentions every flaw, price, local pickup.
4. Write one polite reply template for lowball offers that points at the sold prices.

RULES: Cite a link for every comparable. Never invent prices or sales. Never pay listing fees or submit anything. Ask me before posting or replying to any buyer. If a site needs a login, stop and tell me.

OUTPUT: comps table (item / sold price / date / link), my list price and floor, the ready-to-post listing, the lowball reply template.

When done, tell me to paste buyer messages and you'll draft the replies for my ok.
```

## prompt 2: counter a lowball

works anywhere, even the free phone app.

```
You are my negotiation writer. A buyer offered $[their offer] on my [item] listed at $[my price]. Similar ones sold for about $[comps range].

DO THIS:
1. Write a short friendly reply countering at $[my counter] that mentions the sold prices.
2. Give me 2 versions: one firm, one flexible.
3. If their offer is actually fair, say so instead of countering.

RULES: Two lines max, polite. Never accept or decline for me, just write what I could send.

OUTPUT: the two replies plus a one-line read on the offer.
```

the trick: never argue. just point at what it actually sells for.
