
#  Currency Converter Web App

A simple and interactive **Currency Converter** web application built with **HTML**, **CSS**, and **JavaScript**.
It allows users to convert currency values between different countries using real-time exchange rates fetched from an external API.



## Features

**Live currency conversion** using [Fawaz Ahmed’s Free Currency API](https://github.com/fawazahmed0/currency-api)
**Automatic flag updates** for selected countries
**Default selection** of USD → INR
**Responsive and clean design**
**User-friendly interface**

---

##  Tech Stack

* **HTML5** – Page structure
* **CSS3** – Styling and layout
* **JavaScript (Vanilla JS)** – API calls, DOM manipulation, and event handling
* **Font Awesome** – Icons
* **FlagsAPI** – For country flag images

---

##  Project Structure

currency-converter/
│
├── index.html          # Main HTML file
├── stylec.css          # CSS file for styling
├── appc.js             # Core JavaScript logic (API calls, event handling)
├── codes.js            # Contains the countryList mapping
└── README.md           # Documentation file


##  How It Works

1. The app loads a list of currency codes (like USD, INR, EUR) and populates the dropdown menus.
2. The user enters an amount and selects “From” and “To” currencies.
3. When the user clicks **Get Exchange Rate**, the app:

   * Fetches the latest exchange rates from the Currency API.
   * Calculates the converted amount.
   * Displays the result (e.g., `100 USD = 8320 INR`).
4. Flags update dynamically when you change a currency.

---

## API Used

* **Base URL:**

  https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api@1/latest/currencies

* Example endpoint:

  https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api@1/latest/currencies/usd.json
  

  This returns exchange rates for USD against all other currencies.




##  Example Usage

1. Open `index.html` in your browser.
2. Enter the amount (default: 100).
3. Choose currencies (e.g., USD → EUR).
4. Click **Get Exchange Rate**.
5. See the converted value displayed below the button.



##  Future Improvements

* Add currency symbols (₹, $, €, etc.)
* Add a dark mode toggle
* Improve error handling for API failures
* Cache rates locally for offline access
* Add a feature to swap “From” and “To” currencies instantly


Would you like me to include a **demo GIF / screenshot section** or **GitHub Pages deployment instructions** in the README as well?
