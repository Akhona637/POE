Instructions for Compiling and Running the Software
Prerequisites
.NET SDK (version 5.0 or higher)
Visual Studio (recommended) or any other C# IDE with WPF support
Steps to Compile and Run
Clone the Repository
git clone (https://github.com/Akhona637/POE.git)
cd recipe-app
Open the Project

Open Visual Studio.
Select File -> Open -> Project/Solution.
Navigate to the cloned repository folder and open the solution file (RecipeApp.sln).
Build the Project

In Visual Studio, select Build -> Build Solution or press Ctrl+Shift+B.
Run the Project

In Visual Studio, select Debug -> Start Debugging or press F5.
The application window should now open.

### GitHub Repository
[https://github.com/Akhona637/POE.git](https://github.com/Akhona637/POE.git)

### Description of Changes Based on Lecturer’s Feedback

In response to the feedback provided by the lecturer, the Recipe App has been updated from a console application to a Windows Presentation Foundation (WPF) application to provide a more user-friendly graphical interface. The core functionalities, such as adding recipes, displaying recipes, and filtering recipes based on various criteria (ingredient, food group, and calories), have been retained and enhanced within the new interface.

Key changes include:
- **Graphical User Interface (GUI)**: The transition from a command-line interface to a WPF-based GUI makes the application more accessible and visually appealing.
- **Filter Functionality**: A new window (`FilterRecipesWindow`) was added to allow users to filter recipes based on ingredients, food groups, and maximum calorie content.
- **Code Refactoring**: The code was refactored to separate concerns more effectively, with dedicated classes for managing recipes (`RecipeManager`), and handling ingredients (`Ingredient`) and recipes (`Recipe`). 
