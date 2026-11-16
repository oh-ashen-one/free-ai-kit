# cheap: one shelf photo, the real cheapest

take a pic in the aisle where the price tags are readable, then:

## prompt 1: rank the tags

```
read every price tag in this photo and rank the items by price per ounce (or per unit). flag any where the bigger pack is worse.
```

it reads the tiny unit price on each tag and does the math. the big pack is not always cheaper, that's the whole trick.

## prompt 2: a week of meals from your cart

```
here's what's in my cart: [list or photo]. make me 7 days of cheap meals using mostly these, plus a short list of anything else i need to buy.
```

works on free chatgpt or gemini. if the tags are blurry the numbers will be wrong, so get close.
