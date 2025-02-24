# Currency Converter

This is a web-based currency converter application that allows users to convert an amount from one currency to another using real-time exchange rates. The application fetches exchange rate data from the ExchangeRate API and displays the results dynamically.

## Features

✅ Real-time exchange rate data

✅ Dropdowns for currency selection

✅ Displays national flags for selected currencies

✅ Input validation for the amount field

✅ Responsive and user-friendly interface

## Technologies Used

HTML: Markup structure of the application

CSS: Styling for UI components

JavaScript: Fetching data and updating UI dynamically

ExchangeRate API: Source of real-time exchange rate data

## Setup Instructions

1. **Clone this repository** :
   ```
  git clone https://github.com/deepak-jha-2003/Currency-Converter
    
2. Include the required codes.js file in your project. This file contains the countryList object with currency codes and corresponding country codes for flag display.
3. Open the project folder in your code editor.
4. Run the application locally by opening the index.html file in a web

📁File Structure

├── index.html          # Main HTML file

├── style.css           # Styles for the application

├── app.js              # JavaScript file with application logic

├── codes.js            # JavaScript file containing countryList variable

└── README.md           # Documentation

## How to Use

1. Open the application in a web browser.
2. Select currencies from the dropdown menus for "From" and "To."
3. Enter the amount to be converted.
4. Click the "Convert" button to get the result.
5. View the converted amount and exchange rate.

## API Information

Base URL: https://open.er-api.com/v6/latest
The API provides the latest exchange rates for a base currency.

## Notes
Ensure you have an active internet connection to fetch exchange rates.

Check the browser console for errors if the application doesn't work.


