# FX-AI Nexus 💸

FX-AI Nexus is a next-generation currency exchange web dashboard built with Streamlit and LangChain. It features a live market rates grid, a manual exchange panel, and an autonomous AI Conversion Assistant powered by Chat LLMs and the ExchangeRate-API.

## Features

- **📊 Live Converter Dashboard**: Real-time currency conversions with automated market rates and interactive currency swapping.
- **🔥 Live Market Grid**: Tracks popular global currency pairings (USD, EUR, GBP, INR, JPY, AUD, CAD, SGD) dynamically.
- **💬 Autonomous Agent Workspace**: An AI assistant that uses LangChain tools to answer conversion questions, explain conversion calculations, and summarize market trends.
- **✨ Pro Aesthetics**: Features a premium glassmorphic dark-mode design, smooth hover transitions, and responsive components.

## Project Structure

```
FX-AI-Nexus/
├── app.py              # Main Streamlit Application
├── requirements.txt    # Project Dependencies
├── .gitignore          # Git exclusion rules
└── README.md           # Project Documentation
```

## Setup & Running Locally

1. Clone or copy these files into your local directory.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root directory and add your API keys:
   ```env
   GROQ_API_KEY=your_groq_api_key
   EXCHANGERATE_API_KEY=your_exchangerate_api_key
   ```
4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Deploying to Streamlit Community Cloud

1. Push these files to a brand-new, public GitHub repository.
2. Sign in to [share.streamlit.io](https://share.streamlit.io) using your GitHub account.
3. Click **Deploy an app**, select your new repository, set the main file path to `app.py`, and click **Deploy**.
4. Configure your API keys (`GROQ_API_KEY` and `EXCHANGERATE_API_KEY`) securely under the **Secrets** tab in the App settings.
