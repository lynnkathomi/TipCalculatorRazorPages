# Tip Calculator

This is a simple Tip Calculator web application built using ASP.NET Core Razor Pages. The application allows users to enter the cost of a meal and the desired tip percentage to calculate the tip amount and total cost.

## Features

- Calculate tip amount based on meal cost and tip percentage
- Validate user input to ensure valid meal cost and tip percentage
- Display calculated tip amount and total cost
- Reset form to initial state

## Specifications

- When the app starts, it should display empty text boxes for meal cost and tip percentage, and tip amounts of $0.00.
- If the user enters a valid meal cost and clicks the calculate button, the app should calculate and display the tip amounts.
- If the user enters invalid data and clicks the calculate button, the app should display a summary of validation errors above the form and $0.00 for the tip amounts.
- The cost of the meal is required and must be a valid number that's greater than 0.
- If the user clicks the clear button, the app should reset the page to how it was when the app first started.
- Use the Razor Pages pattern. Create a page model class that stores the cost of the meal and includes a helper method for calculating the tip percentages.
- Use a Razor layout to store the `<html>`, `<head>`, and `<body>` elements.
- Use a custom CSS stylesheet to style the HTML elements for an aesthetic appearance.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/TipCalculatorRazorPages.git
    cd TipCalculatorRazorPages
    ```

2. Open the solution in Visual Studio:
    - Double-click the `TipCalculatorRazorPages.sln` file to open the solution in Visual Studio.

3. Build and run the application:
    - Press `F5` or click on the `Run` button in Visual Studio to build and run the application.

## Usage

1. Enter the meal cost in the `Meal Cost` text box.
2. Enter the desired tip percentage in the `Tip Percentage` text box.
3. Click the `Calculate` button to calculate the tip amount and total cost.
4. The calculated tip amount and total cost will be displayed below the form.
5. Click the `Clear` button to reset the form to its initial state.

## Project Structure

- `Pages/Index.cshtml`: The main page of the application with the form for meal cost and tip percentage input.
- `Pages/Index.cshtml.cs`: The page model containing the logic for calculating the tip and handling form submissions.
- `Models/TipCalculatorModel.cs`: The model class containing properties for meal cost and tip percentage, and methods for calculating the tip amount.
- `wwwroot/css/site.css`: The custom CSS stylesheet for styling the HTML elements.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For any questions or suggestions, please open an issue in this repository.
