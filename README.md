# ☕ Coffee Machine Simulation

A Python-based command-line simulation of a coffee vending machine. Users can choose from a menu, pay virtually, and receive drinks — with real-time resource and money tracking.

## 🧠 How It Works

- The machine offers drinks from a preset menu (e.g., espresso, latte, cappuccino).
- It checks whether enough ingredients are available.
- If sufficient, it processes virtual coins using a money machine system.
- After successful payment, it makes the coffee and updates the resources.

## 🧱 Project Structure

| File | Description |
|------|-------------|
| `main.py` | Core logic and user interaction loop. |
| `menu.py` | Contains `Menu` and `MenuItem` classes that manage drink data. |
| `coffee_maker.py` | Manages ingredient tracking and drink preparation. |
| `money_machine.py` | Handles payment input, cost checking, and money tracking. |

## 📦 Features

- Menu-driven input system.
- Ingredient sufficiency check before each transaction.
- Simulated coin input and
