# 🐨 Aussie Wildlife Alert & Sightings Assistant

An interactive, real-time dashboard that maps wildlife sightings across Australia using public data from the Atlas of Living Australia (ALA). The app covers all types of wildlife — from venomous snakes to harmless birds — and uses GPT to provide natural language safety tips, summaries, and insights.

---

## 📍 Features

- 🔁 **Live Sightings**: Fetches up-to-date wildlife data via ALA API
- 🐍 **All Risk Levels**: Includes high-risk (snakes, spiders) and low-risk (birds, insects, mammals) species
- 🗺️ **Interactive Map**: Explore species sightings across Australia
- 📊 **Data Analysis**: View trends by species, region, and season
- 🧠 **GPT Assistant**: Ask about local wildlife, safety tips, and recent trends

---

## ⚙️ Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend  | Streamlit |
| Mapping   | Folium, Leaflet |
| Backend   | Python, Requests, Pandas |
| AI        | OpenAI GPT (via API) |
| Data      | Atlas of Living Australia (ALA) API |

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/aussie-wildlife-alerts.git
   cd aussie-wildlife-alerts
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set your OpenAI key in `.streamlit/secrets.toml`:
   ```toml
   OPENAI_API_KEY = "your-api-key-here"
   ```

4. Run the app:
   ```bash
   streamlit run app/main.py
   ```

---

## 🔐 Important: API Key Safety

Do **not** share or commit your OpenAI API key publicly.

- Store your key securely in `.streamlit/secrets.toml`
- Never upload this file to GitHub
- Add the following line to your `.gitignore` to keep it private:
  ```gitignore
  .streamlit/secrets.toml
  ```

If your key is accidentally exposed, delete it and generate a new one immediately via your [OpenAI API dashboard](https://platform.openai.com/account/api-keys).

---

## 📊 Example Use Cases

- 🔍 “What dangerous animals were sighted near Melbourne this week?”
- 🚨 “Is it snake season in Queensland?”
- 🧭 “What to do if I see a funnel-web spider?”

---

## 📌 Disclaimer

This tool is for educational and public awareness purposes only. Sightings are based on publicly available data and may not reflect all wildlife activity.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

**Vaibhav Nohria**  
[LinkedIn](https://linkedin.com/in/vaibhav-nohria-70549416b/) • [GitHub](https://github.com/vaibhavnohria01)
