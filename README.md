# Birthday Reminder and Contact Bot

A console menu app with two tools: a weekly birthday reminder and a simple contact bot.

## Features

- Loads users with birthdays from `users.json` and lists whose birthdays fall within the next 7 days, grouped by weekday (weekend birthdays shift to the following Monday)
- A command-line contact bot storing name/phone pairs in memory for the session

## Commands

Menu options:
- `1` — show upcoming birthdays for the next week
- `2` — launch the contact bot
- `0` — exit

Contact bot commands:
- `add [name] [phone number]`
- `change [name] [phone number]`
- `phone [name]`
- `all`
- `hello`
- `close` / `exit`

## Technology

- Python 3 (standard library only)

## Running

```
python main.py
```
