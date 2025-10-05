<a href="https://hizliresim.com/8fwyx57"><img src="https://i.hizliresim.com/8fwyx57.jpg"></a>

# Regmess
Our name “Regmess” comes from German. “Regen” means rain and “messen” means to measure in German. Regmess is a program that measures the probability to rain at the specified location and on the date and time according to the past 20 years’ rain data. It gives the hourly probability to rain and the temperature data within the 2 weeks of the given date. If the date is far from 2 weeks of the given date the program relies on AI to predict the chance of rain according to the past 20 years.

# How it Works?
**“REGMESS”** — predicts whether it will rain at a specific time in the future. It uses Open-Meteo (an open-source API for geocoding and weather forecasts) and uses Artificial Intelligence to produce a user-friendly JSON summary (e.g., condition + rain probability).

# Date-Specialized Forecasting
Our software can give accurate data about the weather including the chance of rain, temperature, wind speed and the condition of the weather. It gives you an accurate graph of the rain chance throughout the day, provided the specified date is within two weeks of searching.



## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
