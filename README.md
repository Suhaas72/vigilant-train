# Automated Vehicle Traffic Rule Simulation (C Project)

This project is a **traffic rule simulator for autonomous vehicles**, implemented in the **C programming language**. It demonstrates the basic logic of how an automated vehicle responds to real-world traffic signals — RED, YELLOW, and GREEN — by taking appropriate actions like stopping, slowing down, or moving forward.

---

## 📊 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [System Design](#system-design)
- [How to Use](#how-to-use)
- [Use Cases](#use-cases)
- [Sample Output](#sample-output)
- [Future Enhancements](#future-enhancements)
- [Contribution](#contribution)
- [License](#license)

---

*##📈 Overview*

As self-driving cars and smart transportation systems become the norm, it's important to simulate the core logic that governs vehicle behavior under traffic rules. This project simulates one such component — the reaction of a vehicle to a traffic signal.


---

*##🛡⚒ Features*

- Console interface for inputting traffic light signals.
- Displays real-time vehicle decisions based on signal.
- Modular and beginner-friendly code structure.
- Easy to integrate into hardware (Arduino, 8051, etc.).
- Supports continuous simulation loop with exit option.

---
### 👥Contributors
- Suhaas P
- Santhosh Kumar K
- Sundar K

## 🧠 System Design

### Input
- User input simulating traffic lights:
  - `0` = RED
  - `1` = YELLOW
  - `2` = GREEN

### Process
- Decision-making logic using `switch-case`.
- Traffic light enum for better readability.

### Output
- Prints the vehicle's behavior in response to the signal.

```c
// Example logic:
if (signal == RED)
    Stop vehicle;
else if (signal == YELLOW)
    Slow down;
else
    Move forward;

