# Possibility
Easily randomize values from a simple 50-50 percentage to more advanced percentages!

```ts
import possibility from "possibility"

possibility({
    heads: 50, //50%
    tails: 50
}) // "heads" | "tails"

possibility({
    bronze: 70, //70%
    silver: 20,
    gold: 10
}) // "bronze" | "silver" | "gold"

possibility({
    fail: 60.4, // 60.4
    succeed: 39.5, 
    jackpot: 0.1
}) "fail" | "scceed" | "jackpot"
```
