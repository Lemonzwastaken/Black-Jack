# 🃏 Blackjack

A terminal-based Blackjack game built as part of my **100 Days of Code** journey. This project focused on practising **functions, game logic, and ASCII art** in Python.

> 📚 Day project from [100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) by Dr. Angela Yu.

## How it works

- You and the computer are each dealt 2 cards
- Choose to draw more cards or hold
- The computer automatically draws until it hits 17 or above
- Closest to 21 without going over wins

## Rules

- Aces are worth 11 (automatically adjusted to 1 if it would bust you)
- Face cards (Jack, Queen, King) are worth 10
- Going over 21 is a bust — instant loss
- Blackjack (exactly 21) beats everything except the house's blackjack

## How to Run

```bash
python main.py
```

No external dependencies needed — just Python's built-in `random`, `os`, and `time` modules.

## License

This project is open source and available under the [MIT License](LICENSE).
