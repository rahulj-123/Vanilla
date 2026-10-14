---
mode: testing
target: emulator
app: ./app.apk
max_steps: 30
tags: [smoke, calculator]
---

# Basic arithmetic on the keypad

## Add two numbers
Wait for the calculator keypad to be shown.
Tap the "1", "2", "+", "3" and "0" buttons in that order, then tap the "=" button.
Verify the display shows the result 42.

## Respect operator precedence
Tap the "C" button to clear the display.
Tap the "2", "+", "3", "×" and "4" buttons in that order, then tap the "=" button.
Verify the display shows the result 14.

## Divide to a decimal result
Tap the "C" button to clear the display.
Tap the "9", "/" and "4" buttons in that order, then tap the "=" button.
Verify the display shows the result 2.25.
