```
# 🎮 exponentGame
- A fun interactive integer and string exponent game/calculator.
- This game combines user input, exception handling/input validation and Unicode-converted ASCII art

## 📦 Notes
- This is part of a growing set of small programs documenting my Python learning journey.
- This integrates the functionality and calculations from my StringExponentiation.py program in a neighboring repository ⚙️✨
- The chaos is partially due to creatively forcing Python to exponentiate a string which is not a behavior that is natively supported

## 🧠 How It Works
- Prompts the user to enter the number they would like to exponentiate
- If user enters a non-integer, user is redirected to a function which exponentiates their error code output by 10
- If user does activate the error function -> The function recursively redirects back to the main function expoGame() and begins again
- If an integer is entered into the main prompt, the program pushes a second prompt to ask for the exponent value
- Once the exponent's value has been entered, the result is displayed along with an ASCII Wizard 🧙✨


## 🧪 Example Output

Enter the number you would like exponentiated. UNLEASH YOUR POWER: 
f
Error message: invalid literal for int() with base 10: 'f'
YOU HAVE INPUT NON-MAGIC INTEGER CHAOS STRINGS HEATHEN. ACCEPT YOUR FATE: 

YOUR STRING CHAOS WILL BE EXPONENTIATED BY 10: 

YOUR CHAOS STRING: 
 invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'invalid literal for int() with base 10: 'f'
Try again, Mortal: 

Enter the number you would like exponentiated. UNLEASH YOUR POWER: 
4
Enter the exponent you would like your power MULTIPLIED BY: 
3
2 to the power of 3 is 64
     ⠀⠀⢀⣀⣀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣴⠞⠛⠉⠉⠛⠻⢷⣦⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⠃⠀⠀⠀⠀⠀⠀⠰⡍⠻⣷⣄⠀⢀⣄⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⠇⠀⠀⠀⠀⠀⠀⠀⠀⠘⣷⣌⡛⠷⣯⣽⣧⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣸⡏⣀⣀⣀⠀⠀⠀⠀⢀⣀⣀⢹⣿⢿⣾⠟⠙⢿⣦⡀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣿⠋⠉⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⣿⡄⠀⠀⠀⠀⠉⠉⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⣀⣠⣼⡧⠶⠖⠚⠛⠛⠉⠉⠙⠛⠛⠲⠶⢾⣧⣄⣀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⣀⣤⡶⠟⠛⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠻⢶⣤⣀⠀⠀⠀⠀
        ⠀⣠⣶⣿⣿⣥⣤⣤⣤⣤⣄⣀⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣀⣠⣤⣤⣤⣤⣬⣽⣿⣶⣄⠀
        ⠐⣿⣻⣿⣿⣿⡿⠀⢠⡏⠙⡟⠻⣭⣍⣙⣛⣿⣿⣛⣋⣩⣭⠟⢻⠏⢹⡆⠀⢿⣿⣿⣿⡟⣿⠃
        ⠀⠙⢿⣯⣟⡷⠦⣤⡾⢀⣤⡇⠈⠙⠯⣽⣿⡇⢸⣿⣯⠽⠋⠁⢸⡆⡀⢿⣤⠴⢾⣻⣽⡾⠋⠀
        ⠀⠀⠀⠈⠛⠛⠿⡾⢡⠏⢸⡄⠀⠀⠉⣉⣼⠁⠈⢧⣈⠉⠀⠀⢀⣇⠹⡌⢷⡿⠟⠛⠁⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⡼⣡⡟⢠⡿⣷⣄⢀⣰⣁⣭⣀⣀⣬⣈⣧⡀⣠⢾⢿⣄⢹⣌⢧⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠰⢿⡟⢠⢿⡄⠙⠓⠛⠛⠁⠀⢠⣄⠀⠈⠙⠛⠛⠋⢀⡿⡄⢻⡿⠇⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⣾⣡⡎⠈⢷⣤⣀⣀⡠⠤⠚⠉⠉⠓⠦⢄⣀⣀⣤⡞⠁⠹⣌⣷⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠙⣿⢠⠂⢸⡆⠀⠹⡶⠟⠉⠁⠈⠉⠻⢶⠏⠀⢠⡇⠀⡄⣿⠋⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⢿⢿⢰⡏⣷⣠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣄⣾⣹⣇⡿⡿⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠈⠈⢿⠻⣿⠿⣧⡄⠀⠀⠀⠀⠀⠀⢠⣴⠿⢿⠟⢿⠃⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⢳⣾⡄⠀⠀⢀⣶⡿⠛⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⢿⣄⣠⡾⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀

Process finished with exit code 0

## 🛠️ Tech Stack
- Python 3.10.0
- PyCharm IDE
- Unicode + ASCII Art
```











