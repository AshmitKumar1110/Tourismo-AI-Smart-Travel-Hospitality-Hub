# 🧭 Tourismo AI – Explore India Tourism Dashboard

Welcome to **Tourismo AI**, a smart and interactive tourism dashboard built with Streamlit. Whether you're planning a solo adventure or a family trip across India, this app is your one-stop destination for exploring places, checking weather, booking hotels, and planning your perfect trip.

🔗 **Live App:** [Click here to explore](https://travelapp-eck5qjayxhx2zyqnpz7f5o.streamlit.app/)

---

## ✨ Features

- 🗺️ **Interactive Map:** Explore destinations across India with dynamic Folium maps.
- 📍 **Destination Explorer:** Browse through top travel spots with details and visuals.
- 📅 **Travel Planner:** Plan itineraries with travel duration, estimated costs, and suggestions.
- 🏨 **Hotel Booking (Simulated):** Secure your accommodation using PayPal (demo integration).
- 🌦️ **Weather Forecast:** Real-time weather updates using the OpenWeatherMap API.
- 💬 **User Reviews:** Share and read reviews from fellow travelers.
- 🤖 **Chatbot Support:** (Optional) Add personalized assistant for smart travel help.

---

## 🛠️ Tech Stack

| Layer         | Technology                         |
|---------------|-------------------------------------|
| Frontend      | [Streamlit](https://streamlit.io)   |
| Maps          | [Folium](https://python-visualization.github.io/folium/) |
| Data Handling | [Pandas](https://pandas.pydata.org) |
| Payments      | [PayPal SDK](https://github.com/paypal/PayPal-Python-SDK) |
| API Access    | [OpenWeatherMap](https://openweathermap.org/api) |
| Deployment    | [Streamlit Cloud](https://streamlit.io/cloud) |

---

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/tourismo-ai.git
   cd tourismo-ai
   ```

2. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app:**

   ```bash
   streamlit run boom.py
   ```

4. **Visit in browser:**

   Go to `http://localhost:8501` in your browser.

---

## 📁 Project Structure

```
tourismo-ai/
├── boom.py              # Main Streamlit application file
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 📃 Requirements

All packages are listed in `requirements.txt`:

```
streamlit==1.39.0
streamlit_folium==0.23.2
folium==0.19.2
pandas==2.2.3
paypalrestsdk==1.13.3
Requests==2.32.3
```

---

## 🌐 Live Demo

Experience the dashboard here:  
🔗 [https://travelapp-eck5qjayxhx2zyqnpz7f5o.streamlit.app](https://travelapp-eck5qjayxhx2zyqnpz7f5o.streamlit.app)

---

## 🔮 Future Scope

- 🔊 Multilingual voice input
- 🧭 Smart route planning and optimization
- 🧠 AI-powered itinerary suggestions
- 🕶️ AR/VR previews of attractions
- 🔐 Blockchain-based secure bookings
- 🌍 Integration with real-time transport APIs

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo, open issues, or create pull requests for improvements and features.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Made with ❤️ using Streamlit – making travel smart, seamless, and fun!
