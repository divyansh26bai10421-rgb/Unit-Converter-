# Unit Converter

This is a basic unit converter that I made in python for my first semester project. You choose a conversion from the menu, type a value and it prints the answer.

I made it using only basic python, so there are no functions and no modules in it.

## What it does

- Shows a menu again and again until you choose Quit
- Length: kilometres to miles and miles to kilometres
- Weight: kilograms to pounds and pounds to kilograms
- Temperature: celsius to fahrenheit and fahrenheit to celsius
- Works with decimals and negative numbers
- If you type something wrong it shows a message and doesnt crash

## How to run

1. Open the notebook (unit_converter.ipynb) in jupyter or vscode
2. Run the first cell, it has the conversion values
3. Run the second cell, this starts the menu
4. Type your choice in the box and press enter, then type the value
5. Choose 7 to quit

If you change something in the first cell, run it again before the second one.

## Menu

```
UNIT CONVERTER
1) Kilometres to Miles
2) Miles to Kilometres
3) Kilograms to Pounds
4) Pounds to Kilograms
5) Celsius to Fahrenheit
6) Fahrenheit to Celsius
7) Quit
```

## Formulas used

- km to miles = km * 0.621371
- miles to km = miles * 1.60934
- kg to pounds = kg * 2.20462
- pounds to kg = pounds * 0.453592
- C to F = C * 9 / 5 + 32
- F to C = (F - 32) * 5 / 9

## Example

```
Enter your choice: 1
Enter the value: 10
10.0 km = 6.21 miles

Enter your choice: 5
Enter the value: -40
-40.0 C = -40.0 F
```

## What I used

variables, while loop, if/elif/else, break and continue, input(), isdigit(), int(), float(), try and except, round()

## Problems / things to add later

- Only 6 conversions right now
- The answers are rounded to 2 decimal places
- Can add more units like litres, metres and inches
- Can use functions to make the code shorter once we learn them
