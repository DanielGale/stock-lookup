# 📈 Stock Viewer - Finnhub API

A simple single-page HTML app that allows you to:

- Enter a stock ticker and view its **current price**
- Display **5-day**, **1-year**, and **3-year** historical charts
- Use the **Finnhub API** by entering and saving your API key
- Track recently used tickers for quick access

> ⚠️ No frameworks or server-side code — just HTML, JavaScript, and Chart.js!

---

## 🚀 Getting Started

1. **Clone or Download this Project**

```bash
git clone https://github.com/yourusername/stock-viewer-finnhub.git
cd stock-viewer-finnhub
```

2. **Open index.html in your browser**

You can also deploy it to a static host (e.g., GitHub Pages, Netlify, Vercel, etc.)

🔑 API Key Setup
This app uses the Finnhub Stock API. To get started:

1. Go to https://finnhub.io/register
2. Sign up for a free account
3. Get your API Key
4. Enter your API key into the form at the top of the page and click Save API Key

The key will be stored in a browser cookie for reuse across sessions.

💡 Features
✅ API Key Management
- Store your Finnhub API key in a cookie
- Display the status of the key (saved, missing)
- Clear the key with a button

📊 Stock Data Viewer
- View real-time quote data (current price)
- Render historical charts for:
  - Last 5 days (hourly)
  - Last 1 year (daily)
  - Last 3 years (weekly)

🕘 Ticker History
- Automatically saves a list of recently used tickers in a cookie
- Quickly reselect a recent ticker from a dropdown menu

🧱 Technologies Used
- HTML5
- JavaScript
- Chart.js for rendering charts
- Cookies for storing API key and ticker history

📂 File Structure

```bash
stock-viewer/
├── index.html          # Main app
└── README.md           # You're reading it
```

🔐 Notes on Privacy
- All data is stored locally in your browser using cookies.
- No sensitive data is sent or stored anywhere outside of Finnhub's API.

🛠 Troubleshooting
🔹 Charts not loading?
- Make sure your API key is correct.
- You might have hit your rate limit on Finnhub's free tier.

🔹 “Invalid ticker”?
- Ensure the ticker is valid and listed on a major exchange.
- Example tickers: AAPL, MSFT, GOOGL, TSLA

🙋 FAQ
Q: Can I use this on mobile?
A: Yes, it's mobile-friendly and responsive.

Q: How many tickers are stored in history?
A: Up to 10 recent tickers are saved in your browser.

Q: Can I add technical indicators?
A: Not yet — but feel free to extend it! Chart.js supports plugins.

🧩 Ideas for Improvement
- Add autocomplete for tickers using an external API
- Add technical indicators like RSI, MACD
- Add favorite tickers with edit/delete
- Store data in localStorage instead of cookies
- Dark mode 🌙

📄 License
MIT License © 2025 YourName

🙌 Credits
- Finnhub.io for financial data
- Chart.js for chart rendering
