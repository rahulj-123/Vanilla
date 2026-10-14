---
mode: testing
target: emulator
app: ./app.apk
max_steps: 30
tags: [smoke, history]
---

# Calculations are saved to history

## Calculate a result
Wait for the calculator keypad to be shown.
Tap the "7", "×" and "6" buttons in that order, then tap the "=" button.
Verify the display shows the result 42.

## Open the history
Swipe down on the drag handle at the top of the calculator panel to reveal the history behind it.
Verify the history lists the calculation "7×6" with the result 42.
