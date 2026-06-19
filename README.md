# Currency Converter

A simple web-based Currency Converter that allows users to convert amounts between different currencies using real-time exchange rates. The application fetches live currency data from the ExchangeRate API and displays both the current conversion rate and the converted amount.

## Features

* Real-time currency conversion
* Supports multiple international currencies
* Dynamic currency dropdowns
* Displays current exchange rate
* Instant conversion results
* Error handling for failed requests
* Clean and responsive user interface

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### API

* ExchangeRate API

## Project Structure

```text
Currency-Converter/
│
├── Images/
│   └── currency-converter.png
│   └── search.png
│
├── README.md
├── index.html
└── style.css
```

## How It Works

1. The application fetches the list of available currencies from the ExchangeRate API.
2. Users select the source and target currencies.
3. Users enter an amount to convert.
4. The application retrieves the latest exchange rate.
5. The converted amount and current exchange rate are displayed.

## Screenshot

![Currency Converter](Images/currency-converter.png)

## Installation

```bash
git clone <repository-url>

cd Currency-Converter
```

Open `index.html` in your browser.

## Future Improvements

* Currency swap button
* Conversion history
* Dark mode
* Country flags for currencies
* Offline caching of recent rates

## Author

Atmika Nayak
