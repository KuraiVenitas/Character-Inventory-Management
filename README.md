# Character-Inventory-Management
This program is a small-scale Python project that allows the user to create a character profile with a few elements: A name, level, and an inventory of items.
The character's information is then saved to a JSON file within the same folder and the program can be used to edit this file.

## Features
- Name changing
- Level changing
- Inventory adjustments which including adding or removing items and changing their names.

## Technologies Used
- Python 3.14.7
- Standard Library: json, sys, time
- Development Environment: Visual Studio Code(VS Code)
- Data Storage Format: JSON

## How It Works
- Download and extract the Character & Inventory Management.ZIP, then run the "Character & Inventory Management.py" file
- When the file runs, it will automatically load the character profile saved within the same folder as the python file.
- In the event a character profile does not exist, a new one will be created through running the program.

---The Main Menu---
- The user will be prompted to change the Name, Level, Inventory or to Quit the program.
- Each of these features can be accessed by typing the respective word (case-insensitive)
- Upon selecting an option, the user will need to type a valid input to adjust the appropriate field.
  
---Adjusting Name or Level---
- To adjust the name or level of the character, type "name" or "level", respectively. The program will ask the user for the updated field, then display the updated information once done.
- 
---Adjusting Inventory---
- To adjust the inventory of the character, type "inventory".
- From here, the user will be prompted to update an item in the character's inventory. If the item cannot be found, it will create a new entry.
- After the item is found or an entry is created, it will ask for a quantity. This will add the amount to the currently held items. For example, if I have 5 Potions and type "5", I will have 10 potions.
- Alternatively to remove items, subtract the amount you own by entering a negative integer. If I type "-10" for potions, I will have 0 potions.
- Item amounts less than or equal to 0 will automatically be removed from the character's inventory.

- Changes made to the character are saved upon quitting the program through the main menu
- If a file exists, but could not be loaded, it may be corrupted. It is recommended to delete the old file and create a new one through the program, though if the error is caused by improper formatting, the file can be adjusted manually to save it.
