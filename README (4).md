# 💱 Currency Converter

A clean, responsive currency converter built with vanilla HTML, CSS, and JavaScript. Fetches live exchange rates and converts between currencies in real time.

**🔗 Live Demo:** [https://negin-mohammadshahi.github.io/currency-converter/](https://negin-mohammadshahi.github.io/currency-converter/)

---

## Features

- **Live exchange rates** — fetches real-time rates from [ExchangeRate-API](https://www.exchangerate-api.com/)
- **Swap currencies** — one click to flip "From" and "To" currencies
- **Auto-convert while typing** — debounced input, no need to click a button every time
- **Remembers your last selection** — saved locally via `localStorage`
- **Copy result** — copy the converted amount to your clipboard in one click
- **Error handling** — clear feedback if the amount is missing or the API request fails
- **Fully responsive** — works on desktop and mobile

## Supported Currencies

USD · EUR · GBP · RUB · IRR

> **Note:** Exchange rates for IRR (Iranian Rial) reflect the official rate provided by the API, which can differ significantly from Iran's free-market rate. The app displays a notice when IRR is selected to make this clear.

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, Google Fonts)
- Vanilla JavaScript (async/await, Fetch API, localStorage)
- [ExchangeRate-API](https://www.exchangerate-api.com/) (Open Access endpoint) for live exchange rate data

## Project Structure

```
currency-converter/
├── index.html      # All markup, styles, and logic in a single file
└── README.md
```

## Running Locally

No build tools or dependencies required.

1. Clone the repository:
   ```bash
   git clone https://github.com/negin-mohammadshahi/currency-converter.git
   ```
2. Open `index.html` directly in your browser.

That's it — no `npm install`, no build step.

## Deployment

This project is deployed with **GitHub Pages** directly from the `main` branch. Any push to `main` updates the live demo automatically.

## Possible Future Improvements

- Add more currencies
- Show a short historical rate chart
- Add a dark/light theme toggle
- Cache exchange rates to reduce API calls

## Attribution

Exchange rate data provided by [ExchangeRate-API](https://www.exchangerate-api.com/) (free, open access, no API key required).

## License

This project is open source and available under the [MIT License](LICENSE).

---

Built as a front-end practice project to work with async JavaScript, third-party APIs, and clean UI design.
