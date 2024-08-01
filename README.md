# [Store module] Crash
Crash module for Store: Bet credits on a rising multiplier. Cash out before it crashes to win, or lose your bet if it crashes first.

# Config
Config will be auto generated. Default:
```json
{
  "min_bet": 10,
  "max_bet": 1000,
  "min_multiplier": 1.1,
  "max_multiplier": 9.9,
  "multiplier_increment": 0.01,
  "crash_commands": [
    "crash"
  ],
  "multiplier_ranges": [
    {
      "start": 1.0,
      "end": 2.0,
      "chance": 55
    },
    {
      "start": 2.0,
      "end": 3.0,
      "chance": 25
    },
    {
      "start": 3.0,
      "end": 4.0,
      "chance": 10
    },
    {
      "start": 4.0,
      "end": 5.0,
      "chance": 7
    },
    {
      "start": 5.0,
      "end": 15.0,
      "chance": 3
    }
  ]
}

```
