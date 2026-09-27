# Number Guessing Game 🎮

Hey! This is a little number guessing game I made in Python for one of my projects. Basically you type in a max number, the computer picks a random secret number, and then you have to guess it. It tells you if you're too high or too low until you get it right lol.

This was honestly a pretty fun beginner project so I figured I'd write up how to run it in case someone else wants to try it out.

## What you need before starting

- Just **Python** installed (I used Python 3, should work on 3.6+ probably)
- Thats literally it, I didn't use any external libraries or anything fancy, just the built in `random` module

## How do I know if I have python??

Open up your terminal / command prompt and type:

```bash
python3 --version
```

if it says "command not found" try this instead:

```bash
python --version
```

If BOTH of those don't work then you probably don't have python installed, go download it here: https://www.python.org/downloads/ and then come back and try again lol

## Setting it up

1. Download this project or clone it, whatever works for you
2. Open your terminal and cd into the folder, like:

```bash
cd path/to/wherever/you/put/it
```

3. My game file is called `main.py` — if you saved it as something else just change the filename when you run it below

4. No need to install anything else, no pip install, no virtual environment needed (you COULD make one if you want but it's not required since theres no dependencies)

5. No config files or api keys or anything like that either, its literally just one python file lol

## How to actually run it

```bash
python3 main.py
```

if python3 doesnt work (this happens on windows sometimes) just do:

```bash
python main.py
```

## How to play

1. It'll ask you to type a number — this is like the max number it could pick (I usually just put 100)
2. Then it secretly picks a random number somewhere in that range
3. You start guessing! It'll tell you if your guess was too high or too low
4. keep guessing until you get it right, then it tells you how many tries it took you

heres kind of what it looks like when you run it:

```
Type a number for an upper bound: 50

Please type a number between 1 and 50: 25
Your guess is too high. Try again.

Please type a number between 1 and 50: 12
Your guess is too low. Try again.

Please type a number between 1 and 50: 18

You got it!
It took you 3 guess/guesses!
```

## Stuff that might go wrong

- if it says command not found for python3, just try python instead, or you might need to actually install python first
- if you type letters instead of a number it just kicks you out of the game lol, so make sure to type an actual number
- if nothing is happening it's probably just waiting for you to type something and press enter, its not frozen dont worry

## License

idk i didnt really think about a license for this, its just a school project lol, feel free to use it tho
