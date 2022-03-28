# Wordle Solver - Python3

To run: `python3 wordle_solver.py`
To stop: `control + c`

## How to use
1. Make your first guess in wordle
2. Provide each letter, color, and position when asked to do so in the program
  y = yellow
  g = green
  b = black
3. Make the next guess using the new possible word list
4. Repeat until you find the word of the day!

## Example

```
❯ python3 wordle_solver.py

What letter do you know: o
What color is the letter (y, g, b): g
What position is the letter in (1 - 5): 2
would
 words
 ...
 ...
 ...
 roble

What letter do you know: d
What color is the letter (y, g, b): g
What position is the letter in (1 - 5): 5
would
 could
 ...
 ...
 ...
 xored

What letter do you know: f
What color is the letter (y, g, b): g
What position is the letter in (1 - 5): 1
found
 foxed

What letter do you know: ^CTraceback (most recent call last):
  File "/Users/raz/Desktop/wordle-solver/wordle_solver.py", line 35, in <module>
    letter = input("What letter do you know: ")
KeyboardInterrupt
```

### ✅ Answer: FOUND
