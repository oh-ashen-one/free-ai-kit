# split: roommate bill splitter

two files, pick one:

- [roommate-bills.xlsx](roommate-bills.xlsx) - open it in excel or import it into google sheets (file > import)
- [roommate-bills.csv](roommate-bills.csv) - the simplest version, same math, one sheet

## how it works

- people tab: put your roommates' names in
- expenses tab: log every bill, who paid it, and whether it's settled
- balances tab: shows each person's share vs what they paid, and counts their bills that are 30+ days late

every expense splits evenly across everyone. the flag column turns red on anything still unpaid after 30 days. there's fake example data in it so you can see it working, delete it and log real bills.

## make your own instead

```
build me a google sheet for splitting bills between [number] roommates: an expenses tab (date, who paid, amount, category, settled yes/no), a balances tab showing who owes who, and conditional formatting that turns a row red if it's unpaid for 30+ days. give me the exact formulas.
```

share the sheet with your roommates. nobody can say they didn't know.
