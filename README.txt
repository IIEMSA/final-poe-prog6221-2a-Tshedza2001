Recipe Application


The Recipe Application is a Windows desktop application built using the WPF (Windows Presentation Foundation) framework. It allows users to enter recipes, including their ingredients and steps, and calculates the total calories of each recipe.

Getting Started
To run the Recipe Application, follow these steps:

Clone or download the repository to your local machine.
Open the solution file (RecipeApplication.sln) in Visual Studio.
Build the solution to restore NuGet packages and compile the application.
Prerequisites
Windows operating system
.NET Framework 4.7.2 or later
Visual Studio 2019 or later
Running the Application
Build the solution in Visual Studio to ensure all dependencies are resolved.
Set the RecipeApplication project as the startup project.
Press the "Start" button or hit F5 to run the application.
The Recipe Application window will appear, allowing you to enter recipe details.
Usage
Enter Recipe
In the "Enter Recipe" section, fill in the recipe details:

Recipe Name: Enter the name of the recipe.
Ingredient Count: Specify the number of ingredients in the recipe.
Step Count: Specify the number of steps in the recipe.
For each ingredient, provide the following information:

Ingredient Name: Enter the name of the ingredient.
Ingredient Quantity: Specify the quantity of the ingredient.
Ingredient Unit: Enter the unit of measurement for the ingredient.
Ingredient Food Group: Select the food group to which the ingredient belongs.
Ingredient Calories: Enter the number of calories for the ingredient.
For each step, provide a description of the step.

Click the "Add Ingredient" button to add more ingredients if needed.

Click the "Add Step" button to add more steps if needed.

Once all the details are entered, click the "Enter Recipe" button to save the recipe.

Recipe Output
The "Recipe Output" section will display the entered recipes, along with their ingredients, steps, and total calories.
View Recipes
Clicking the "View Recipes" button will open a new window displaying a list of all the entered recipes.
Customization
You can customize the Recipe Application by modifying the XAML code (MainWindow.xaml) and the C# code-behind file (MainWindow.xaml.cs). Add or modify UI elements, validation logic, or additional features as per your requirements.

Authors
Tshedza Ramabulana
License
This project is licensed under the MIT License.