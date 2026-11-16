# cheap: one shelf photo, the real cheapest

the unit price is the tiny print on the shelf tag. the big pack is not always cheaper, that's the whole trick.

## how to use this

1. open chatgpt.com (or the chatgpt app) or gemini.google.com
2. take a clear pic of the shelf where the price tags are readable
3. attach the pic, paste the box, fill in the [brackets], hit send

works on free tiers. if the tags are blurry the math will be wrong, so get close.

## prompt 1: rank the tags

works anywhere you can attach a photo, including the free phone app.

```
You are my grocery-price agent. Your job is to read the shelf tags in my photo and find the actual cheapest option, not to give me shopping advice.

MY INFO:
- Photo of the shelf: [attached, price tags readable]
- What I'm buying: [e.g. peanut butter]

DO THIS:
1. Read every price tag in my photo: brand, size, price, and the small unit price if it's printed.
2. Rank every item by price per ounce or per unit. Show the math.
3. Flag any item where the bigger pack costs more per unit than the smaller one.
4. If a tag is blurry or missing, say which one instead of guessing.

RULES: Only numbers you can actually read in the photo. Never invent a price. If the unit price isn't printed, calculate it from size and price and say so.

OUTPUT: a ranked table: item / size / price / price per ounce / verdict. Then one line naming the actual cheapest.

When done, ask me if I want a week of cheap meals built from the winners.
```

## prompt 2: a week of meals from your cart

works anywhere, even the free phone app. attach a pic of your cart or list it.

```
You are my broke meal planner. Your job is to make me 7 days of cheap meals mostly from what's already in my cart.

MY INFO:
- My cart: [list it or attach a photo]
- Budget for extras: [$X]
- Stuff I won't eat: [list, or "nothing"]

DO THIS:
1. Build 7 days of breakfasts, lunches and dinners using mostly my cart items.
2. Add a short shopping list of only the extras needed, with rough prices.
3. Keep prep under 20 minutes a meal and repeat cheap staples so nothing goes bad.

RULES: Only real foods and realistic prices, no fancy ingredients. If a price is a guess, mark it.

OUTPUT: a day-by-day table (breakfast / lunch / dinner) plus the extras list with prices and a total.

When done, ask me if any meals should swap for stuff I already own.
```
