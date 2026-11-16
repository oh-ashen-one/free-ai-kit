# split: roommate bill splitter

no more "i'll venmo you later". two ready-made files, or make your own with the prompt.

## the easy way (2 minutes)

1. download [roommate-bills.xlsx](roommate-bills.xlsx) (or [roommate-bills.csv](roommate-bills.csv) for the simplest version)
2. open it in google sheets (sheets.google.com > file > import > upload) or excel
3. put your roommates' names on the people tab, start logging bills on the expenses tab
4. the balances tab shows who owes what, and anything unpaid for 30+ days turns red

there's fake example data in it so you can see it working. delete it and log real bills. share the sheet with your roommates so nobody can say they didn't know.

## or make your own

1. open chatgpt.com (or the chatgpt app) or claude.ai
2. copy the box below
3. paste it, fill in the [brackets], hit send

```
You are my spreadsheet builder. Your job is to design a working roommate bill splitter I can rebuild in google sheets, not to explain what a spreadsheet is.

MY INFO:
- Roommate names: [list them]
- Bills we split: [e.g. rent, wifi, groceries, electric]
- Split style: [even split, or describe]

DO THIS:
1. Design two tabs: an expenses tab with columns date, bill, category, who paid, amount, settled yes or no, days open, late flag. And a balances tab showing per person: total paid, share owed, net balance, late bill count.
2. Give me the exact formula for every computed cell, written so i can paste them straight into google sheets.
3. Give me the conditional formatting rule that turns a row red when it's unpaid for 30+ days.
4. Write it all as numbered steps, like "cell G2, paste this".

RULES: Formulas that actually work in google sheets, no invented functions. Even split unless i said otherwise. Check each formula against this example: 3 roommates, $1200 rent.

OUTPUT: the layout of each tab, the formula list cell by cell, the formatting rule, and a 3-row example so i can check it works.

When done, ask me if you should walk me through sharing the sheet with my roommates.
```
