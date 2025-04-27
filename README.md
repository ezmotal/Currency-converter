Currency Converter
A simple and responsive web-based Currency Converter that fetches real-time exchange rates and displays country flags for selected currencies.

🛠️ Built With
HTML

CSS

JavaScript

Currency API (for real-time exchange rates)

Flags API (for country flags)

📂 Project Structure
pgsql
Copy
Edit
├── index.html        // Main HTML structure
├── style.css         // Styling for the converter
├── codes.js          // Currency codes and country mapping
├── app.js            // Core JavaScript logic (API call, flag update, conversion logic)
✨ Features
Real-time currency conversion.

Country flags update automatically when currency changes.

Default conversion from USD to INR.

Responsive and clean UI.

Error handling for invalid amounts.

📸 Screenshot

(Replace with actual screenshot if you want)

🚀 How to Run
Clone the repository or download the files.

Open the index.html file in your browser.

Enter the amount, select currencies, and click "Get Exchange Rate."

⚙️ How it Works
Dropdown Menus: Populated dynamically from countryList (in codes.js).

Currency Rates: Fetched live from the Currency API.

Flag Updates: Based on the selected currency, using Flags API.

Exchange Rate: Calculated and displayed after the button click.

📢 Acknowledgements
fawazahmed0/currency-api

FlagsAPI

Font Awesome
