# Currency Converter

A web-based currency conversion application that allows users to convert amounts between multiple international currencies using real-time exchange rates. The application fetches live conversion data through the ExchangeRate API and provides accurate exchange rates and converted values instantly.

## Live Demo

**Application:** https://currency-converter-dusky-theta.vercel.app/

## Features

* Real-time currency conversion
* Supports multiple international currencies
* Dynamic currency list generation from API data
* Displays current exchange rate between selected currencies
* Instant conversion results
* Error handling for failed API requests
* Clean and responsive user interface

---

## Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

### API

* ExchangeRate API

### Deployment

* Vercel

---

### Currency Converter Interface

![Currency Converter](Images/currency-converter.png)


## How It Works

1. The application fetches available currencies from the ExchangeRate API.
2. Currency options are populated dynamically into both dropdown menus.
3. Users select source and target currencies.
4. Users enter an amount to convert.
5. The application requests the latest exchange rate from the API.
6. The converted amount and current exchange rate are displayed.

---

## API Endpoints Used

### Fetch Available Currencies

```http
GET https://v6.exchangerate-api.com/v6/{API_KEY}/latest/USD
```

Used to retrieve the list of supported currencies.

### Convert Currency

```http
GET https://v6.exchangerate-api.com/v6/{API_KEY}/pair/{FROM}/{TO}/{AMOUNT}
```

Used to calculate conversion rates and converted amounts.

---

## Project Structure

```text
Currency-Converter/
│
├── Images/
│   ├── currency-converter.png
│   └── search.jpg
│
├── index.html
├── style.css
└── README.md
```

---

## Installation

```bash
git clone <repository-url>

cd Currency-Converter
```

Open `index.html` in your browser.

---

## Author

### Atmika Nayak

GitHub: https://github.com/AtmikaNayak
