# Stocks-Engine
---
# Requirements
* Python 3
* Colorama
* pip

# Installing dependencies

### Make sure you have pip3 installed!

You can check this by running `pip3 --version` in your command line or terminal.

Then install all pip dependencies with `pip3 install -r piprequirements.txt`


### Adding commands


As of 2/25/2024, these are the current commands:
* `buy` or `b`
  * Buys stocks.
* `sell` or `s`
  * Sells stocks.
* `inventory` or `i`
  * Lists all drugs and how many you own along with the current price.
* `price`
  * Check the price of a certain stock.
* `balance` or `bal`
  * Tells you how much money you have. 
* `clear` or `cls`
  * Clears the terminal.


To add more, use `user_input == command:` in `commands.py` right after `user_input == input(Fore.BLUE + "\nWhat would you like to do? " + {typing_colour).lower()` And define your logic.

### Adding stocks

Goto `stocktable.py` and add stocks to the `table` array.
After that, make `nametoid.py` match `stocktable.py`.
The first part of the list in `nametoid.py` is the name of the stock, the second part is the index of the stock in the array in `table`.

### Changing Colours
Change the colours in `colours.py`
E.g. if you want the input colour to be white, change `inputcolour = Fore.RED` to `inputcolour = Fore.WHITE`
