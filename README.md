# Shop Wizard Bot

**The Shop Wizard Bot** is a Telegram bot designed to help users manage their shopping lists, contacts, and stay informed 
about the weather in their city. It aims to provide convenience and efficiency in organizing shopping essentials and 
maintaining a contact book.

The purpose of the Shop Wizard Bot is to streamline the process of creating, editing, and removing shopping lists and 
items. It enables users to effortlessly create new shopping lists, add items to them, view the items in a list, and 
remove items when necessary. By automating these tasks, the bot simplifies the shopping list management process, 
saving users time and effort.

Additionally, the bot offers a contact book functionality, allowing users to store and manage their contacts. Users can 
add new contacts with their names and phone numbers, view the list of contacts, delete specific contacts, and get 
information about a particular contact. This feature helps users keep their important contact information organized and 
easily accessible.

Furthermore, the Shop Wizard Bot provides weather information for a given city. Users can retrieve current weather data 
for their city by using the /weather command followed by the city name. The bot uses the WeatherService to fetch the 
weather data, leveraging APIs and geolocation services to provide accurate and up-to-date information. By integrating 
weather updates, the bot helps users stay informed about the weather conditions in their location, assisting them in 
planning their activities accordingly.

Overall, the Shop Wizard Bot optimizes the shopping list management process, contact organization, and weather 
information retrieval. By centralizing these functionalities within a Telegram bot, it offers users a convenient and 
efficient way to handle their shopping lists, contacts, and stay updated with the weather, enhancing their productivity 
and organization.

**The list of commands of the Shop Wizard Bot:**  
/commands - See all available commands  

_**Show List Commands:_**  
    /create_list - Create a new shopping list. Usage: /create_list <list_name>.  
    /remove_list - Remove an existing shopping list. Usage: /remove_list <list_name>.  
    /edit_list - Rename a shopping list. Usage: /edit_list <old_list_name> <new_list_name>.  
    /add_item - Add an item to a shopping list. Usage: /add_item <list_name> <item_name>.  
    /show_items - Show items in a shopping list. Usage: /show_items <list_name>.  
    /remove_item - Remove an item from a shopping list. Usage: /remove_item <list_name> <item_name>. 

_**Weather Commands:_**  
    /weather - Get the weather for a city. Usage: /weather <your_city>  

_**Contact Book Commands:_**  
    /add - Add a new contact to your contact book. Usage: /add <first_name> <last_name> <contact_phone>  
    /status - Show amount of contacts in your contact book. Usage: /status  
    /show - Show the contact from your contact book. Usage: /show <first_name> <last_name>  
    /list - Show the list of all your contacts. Usage: /list  
    /delete - Delete a contact from a contact book. Usage: /delete <first_name> <last_name>   

Replace <list_name>, <item_name>, <your_city>, <first_name>, <last_name> with the actual names you want to use.  

**_Landing page_** - https://kvoroshylova.github.io/  

**_Link to the Bot_** - https://t.me/shopwizardbot

**_Backend part_** - https://github.com/kvoroshylova/shop_wizard_bot
