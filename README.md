# ☕ Coffee Machine Simulator

A **Python-based terminal simulation** of a simple coffee vending machine.  
Users can buy drinks, pay with virtual coins, and the machine tracks resources and profit.

---

## 🛠️ Features

- Choose from: **espresso**, **latte**, or **cappuccino**  
- Ingredient availability checks (water, milk, coffee)  
- Simulated coin input (quarters, dimes, nickels, pennies)  
- Calculates change and handles insufficient funds  
- Tracks total profit  
- `report` command shows current resources and profit  
- `off` command turns off the machine  

---

## 🧾 Example Interaction

What would you like? (espresso/latte/cappuccino): latte

-Please insert coins.

-how many quarters?: 10
-how many dimes?: 0
-how many nickles?: 0
-how many pennies?: 0

-Here is $0.0 in change.

-Here is your latte. Enjoy!


---

## 🧰 Technologies Used

- Python 3  
- Standard input/output  

---

## 📋 Commands

| Command      | Description                        |
|--------------|----------------------------------|
| `espresso`   | Buy an espresso                  |
| `latte`      | Buy a latte                      |
| `cappuccino` | Buy a cappuccino                 |
| `report`     | Print current resources and profit |
| `off`        | Turn off the machine             |
