# Problem

# Monty Hall Problem: A Probability Paradox

The **Monty Hall problem** is a probability paradox based on a TV show. The scenario is as follows:

1. There are three doors. Behind one door is a prize (like a car), and behind the other two are "zonks" (e.g., goats).
2. The participant chooses one door.
3. The host, who knows where the prize is, opens one of the remaining doors, always revealing a "zonk."
4. The participant then has the option to stick with their initial choice or switch to the other unopened door.

The paradox arises when it is discovered that the best strategy is **always to switch doors**, as this increases the probability of winning from **1/3 to 2/3**. This result, while mathematically correct, goes against most people's intuition.

---

## Objective

Here, we will simulate the Monty Hall problem in Python to validate, experimentally, that switching doors is the better strategy. Through this simulation, we can observe the probabilities and confirm that switching indeed improves the chances of winning.

---

## Steps

1. Simulate the Monty Hall game multiple times using Python.
2. Compare the success rates between **switching doors** and **sticking to the initial choice**.
3. Verify that switching provides a higher probability of winning.
