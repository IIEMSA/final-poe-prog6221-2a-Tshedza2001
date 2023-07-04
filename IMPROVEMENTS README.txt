Recipe Application
The Recipe Application is a console-based program written in C#. It allows users to enter, scale, reset, and display recipes. Each recipe consists of a name, a list of ingredients, a list of steps, and a flag indicating whether the total calories of the recipe exceed a certain threshold.

Features
Enter a new recipe: Users can enter a new recipe by providing its name, ingredients, and steps. The total calories of the recipe are calculated and compared to a threshold of 300 calories. If the total calories exceed the threshold, a warning message is displayed. If the total calories are less than 150, a message indicating that the recipe is low in calories is shown. If the total calories are between 150 and 250, a message indicating a moderate calorie content is displayed.

Scale a recipe: Users can scale a recipe by providing its name and a scaling factor. The quantities of all ingredients in the recipe are multiplied by the scaling factor, allowing users to adjust the recipe for different serving sizes.

Reset a recipe: Users can reset a recipe by providing its name. This operation clears the ingredients and steps of the recipe, allowing users to start over or make modifications.

Clear all data: Users can clear all the stored recipes, removing them from memory.

Display all recipes: Users can view a list of all entered recipes. The recipes are displayed along with their ingredients and steps.

Improvements
Based on the provided code, the following improvements were made to enhance the functionality and usability of the Recipe Application:

Added a welcome message: A welcome message is displayed at the start of the application to provide users with a brief introduction to the program.

Implemented a menu system: A menu system was implemented using a while loop and switch case statements. This allows users to select the desired operation from a menu instead of manually entering commands.

Enhanced user input validation: The code includes validation checks to handle invalid user inputs gracefully. For example, when entering ingredient counts and step counts, the program verifies that the input is a valid integer.

Improved error handling: Error messages are displayed when a recipe is not found or when an invalid menu option is selected. This helps users understand what went wrong and how to correct it.

Formatted console output: The console output for displaying recipes and messages is formatted using different colors to improve readability and highlight important information. Green is used for low-calorie recipes, yellow for moderate-calorie recipes, and red for warnings.

Stored recipes in a list: The code now uses a list to store all the entered recipes. This allows for easy retrieval and manipulation of recipes throughout the application's execution.

Encapsulated recipe-related data: The Recipe class encapsulates the recipe's name, ingredients, steps, and total calorie status. This improves code organization and follows object-oriented principles.

Introduced a separate Ingredient class: The Ingredient class was created to represent the properties of an ingredient, such as its name, quantity, unit, calories, and food group. This improves code readability and facilitates future modifications or additions to ingredient-related functionality.

Usage
To use the Recipe Application, follow these steps:

Run the application.

Select one of the available options from the menu:

Enter a new recipe
Scale a recipe
Reset a recipe
Clear all data
Display all recipes
Quit
For entering a new recipe, provide the recipe's name, the number of ingredients, and the number of steps. Follow the prompts to enter the details of each ingredient and step.

After entering a recipe, the total calories of the recipe will be calculated and displayed. If the total calories exceed 300, a warning message will be shown. If the total calories are less than 150, a message indicating that the recipe is low in calories will be displayed. If the total calories are between 150 and 250, a message indicating a moderate calorie content will be shown.

To scale a recipe, provide the name of the recipe you want to scale and enter the scaling factor. The quantities of all ingredients in the recipe will be multiplied by the scaling factor, allowing you to adjust the recipe for different serving sizes.

To reset a recipe, provide the name of the recipe you want to reset. This will clear the ingredients and steps of the recipe, allowing you to start over or make modifications.

The "Clear all data" option allows you to remove all entered recipes from memory. Use this option with caution as it cannot be undone.

The "Display all recipes" option will show a list of all entered recipes, along with their ingredients and steps. Recipes are displayed with different colors to indicate their calorie content or any warnings.

The application will continue to run until you select the "Quit" option from the menu.

Getting Started
To run the Recipe Application on your local machine, follow these steps:

Ensure that you have the .NET Core SDK installed. If not, download and install it from the official Microsoft website.

Clone the repository or download the source code files.

Open a terminal or command prompt and navigate to the directory where the source code files are located.

Build the application by running the following command:

shell
Copy code
dotnet build
Run the application by executing the following command:

shell
Copy code
dotnet run
Follow the on-screen instructions to interact with the Recipe Application.

Contribution
Contributions to the Recipe Application are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository.

To contribute code changes:

Fork the repository on GitHub.

Create a new branch with a descriptive name for your feature or bug fix.

Make the necessary code changes and additions in your branch.

Write appropriate unit tests to cover the changes, ensuring that existing tests pass.

Commit your changes and push them to your forked repository.

Open a pull request on the original repository, describing the changes you have made.

Your pull request will be reviewed, and further adjustments may be requested.

License
The Recipe Application is released under the MIT License. Feel free to use, modify, and distribute the code for personal or commercial purposes.

Acknowledgements
The Recipe Application was developed by Tshedza Ramabulana. We would like to thank the open-source community for their valuable contributions and the Microsoft .NET team for providing the .NET Core platform.

If you have any questions or need further assistance, please contact ramabulanatshedza@gmail.com.

Enjoy using the Recipe Application!