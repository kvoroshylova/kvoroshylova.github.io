# Shop Wizard Bot

**The Shop Wizard Bot** is a Telegram bot designed to help users manage their shopping lists, contacts, and stay informed 
about the weather in their city. It aims to provide convenience and efficiency in organizing shopping essentials and 
maintaining a contact book.

The purpose of the Shop Wizard Bot is to streamline the process of creating, editing, and removing shopping lists and 
items. By automating these tasks, the bot simplifies the shopping list management process, 
saving users time and effort.

Additionally, the bot offers a contact book functionality, allowing users to store and manage their contacts.
This feature helps users keep their important contact information organized and 
easily accessible.

Furthermore, the Shop Wizard Bot provides weather information for a given city. Users can retrieve current weather data 
for their city by using the /weather command followed by the city name. By integrating weather updates, the bot helps 
users stay informed about the weather conditions in their location, assisting them in planning their activities accordingly.

**The list of commands of the Shop Wizard Bot:**  
/commands - See all available commands  

_Show List Commands:_  
    /create_list - Create a new shopping list. Usage: /create_list <list_name>.  
    /remove_list - Remove an existing shopping list. Usage: /remove_list <list_name>.  
    /edit_list - Rename a shopping list. Usage: /edit_list <old_list_name> <new_list_name>.  
    /add_item - Add an item to a shopping list. Usage: /add_item <list_name> <item_name>.  
    /show_items - Show items in a shopping list. Usage: /show_items <list_name>.  
    /remove_item - Remove an item from a shopping list. Usage: /remove_item <list_name> <item_name>. 

_Weather Commands:_  
    /weather - Get the weather for a city. Usage: /weather <your_city>  

_Contact Book Commands:_  
    /add - Add a new contact to your contact book. Usage: /add <first_name> <last_name> <contact_phone>  
    /status - Show amount of contacts in your contact book. Usage: /status  
    /show - Show the contact from your contact book. Usage: /show <first_name> <last_name>  
    /list - Show the list of all your contacts. Usage: /list  
    /delete - Delete a contact from a contact book. Usage: /delete <first_name> <last_name>   

Replace <list_name>, <item_name>, <your_city>, <first_name>, <last_name> with the actual names you want to use.  

**Landing page** - https://kvoroshylova.github.io/  

**Link to the Bot** - https://t.me/shopwizardbot

**Backend part** - https://github.com/kvoroshylova/shop_wizard_bot. There you can see more information about the bot 
from the technical side.
