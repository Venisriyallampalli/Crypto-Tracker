Real-Time Crypto Price Tracker

A responsive cryptocurrency price tracker app built with **React** and **Redux Toolkit**, simulating real-time updates similar to CoinMarketCap. Features dynamic 7-day trend charts, color-coded performance indicators, and a fully managed Redux state architecture.

![Demo Screenshot](./assets/demo-screenshot.jp) <![image](https://github.com/user-attachments/assets/c3ec955a-dc29-4895-9308-becb1994ccd7)


---

## 🚀 Features

- 🔄 Simulated real-time updates (price, volume, % changes)
- 📊 Dynamic, responsive table with sorting-ready columns
- 📈 Static sparkline-style charts for 7-day trends
- 🟢🔴 Color-coded % change indicators
- ⭐ Favorite cryptocurrencies (bonus feature optional)
- ⚡ State management fully handled by Redux Toolkit
- 🎨 Clean and responsive UI with Tailwind CSS

---

## 🧱 Tech Stack

- **Frontend:** React, Tailwind CSS
- **State Management:** Redux Toolkit (createSlice, configureStore)
- **Tooling:** Vite, ESLint, Lucide Icons

---

## 🧠 Architecture

### 🔧 Redux Store

All data for cryptocurrencies is stored and updated via the Redux store. The app simulates real-time updates every 1–2 seconds using setInterval, triggering Redux actions that mutate the global state.

js
setInterval(() => {
  dispatch(updateRandomCryptoMetrics());
}, 1500);
🪄 Components Breakdown
CryptoTable: Renders the main table of cryptos.

CryptoRow: Displays each row with current data.

Header/Footer: Basic layout structure.

WebSocketSimulator: A mock utility simulating real-time data.

🛠 Setup Instructions
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/crypto-tracker.git
cd crypto-tracker
2. Install Dependencies
bash
Copy
Edit
npm install
3. Run the App
bash
Copy
Edit
npm run dev
Visit http://localhost:5173 to view the app in your browser.

🧪 Available Scripts
npm run dev — Start local development server

npm run build — Generate production build

npm run preview — Preview the production build

npm run lint — Run linting using ESLint

📸 Demo GIF / Video
🎥 Watch the full walkthrough of the app below:



Replace YOUR_VIDEO_ID with your actual YouTube or Loom video ID.

📁 Example Data Table Preview
Here's a sample of how the table might look:

<!-- Replace with actual image -->

📄 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Made by Your Name
GitHub: @your-username

📬 Feedback
Feel free to open issues or pull requests to improve this project. Happy tracking!

yaml
Copy
Edit

---

### ✅ Next Steps

- Replace placeholders with real links or images:
  - `demo-screenshot.jpg` and `sample-output.jpg`
  - `https://youtu.be/YOUR_VIDEO_ID`
- Push this `README.md` to the root of your GitHub repo.
- Record your 2–5 min walkthrough video and upload it to YouTube, Loom,or GitHub.
