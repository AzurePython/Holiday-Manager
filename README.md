# Holiday-Manager

This python program scrapes a list of all Holidays from 2020 through 2024, and allows you to manage, view, add and delete holidays from the list using a simple menu. 

### Files in the repository:

* The holidays.json file is a starting format, and the scraped holidays are transformed into the same format. 
* The HolidaySaveFile.json is an example of the output that the HolidayManager will produce when you choose to save a file.
* The psuedocode file is psuedocode, giving an insight into the planning process
* The .gitignore file hides the config file (contains API key)


### How to run the holiday Manager:

Simply copy the repository, and run the HolidayManager.ipynb code. You may not be able to use the weather API unless you
go and grab another key. Everything should work smoothly regardless. If you would like to see the weather on the holidays
in the current week, go to https://rapidapi.com/community/api/open-weather-map and get a custom key.

### Information About the code:

Holidays are stored as objects in a Holiday class, and the overall list is wrapped in a Holiday list class. The main() function calls upon functions within the HolidayList Class to provide the user with a seamless experience.
