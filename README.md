
***

# Daily-Tracker

**Daily-Tracker** is a productivity web app for tracking and visualizing your daily execution as a learner, developer, or professional. This project is designed for anyone who wants to log their daily tasks, monitor execution streaks, and get motivational feedback—all in one interactive dashboard.

## ✨ Key Features

- **Daily Task Logging:** Enter daily progress across multiple domains: DSA, GenAI, Data Analysis, journaling, and reading.
- **Streak Tracking:** Visualize your ongoing productivity streak using a color code (🟢/🟡/🔴).
- **Motivation:** Get motivational feedback based on your tracked results.
- **Progress Visualization:** Instantly view your performance chart to stay accountable and motivated.
- **CSV Data Backend:** All logs and stats are stored in a CSV file, making it easy to export or analyze your data further.
- **Streamlit UI:** Modern, easy-to-use web interface built with Streamlit.

## 📁 Project Structure

```
Daily-Tracker/
└── Daily-tracker/
    ├── app/
    │   ├── streamlit_ui.py         # Main Streamlit application/UI
    │   └── data_handler.py         # Utility for CSV data operations
    ├── agents/
    │   ├── streak_monitor_agent.py # Logic for streak analysis and visualization
    │   └── motivation_agent.py     # Provides motivational messages
    ├── config/                     # Configuration files and constants
    ├── data/                       # (Optional) Storage for daily logs
    ├── gemini_api_wrapper.py       # (Optional) Integration with external APIs
    ├── requirements.txt            # Python dependencies
    └── ... (other supporting scripts)
```

## 🚀 Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://github.com/pprotonn/Daily-Tracker.git
   cd Daily-Tracker/Daily-tracker
   ```

2. **Install requirements:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app:**
   ```bash
   streamlit run app/streamlit_ui.py
   ```

4. **Start Logging:**
   - Fill in your daily tasks in the Streamlit web UI and visualize your streaks and progress instantly!

## 📝 Example UI Fields

- ✅ **DSA Task** – Record today’s data structures & algorithms progress
- 🤖 **GenAI Task** – Log experiments/learning in Generative AI
- 📊 **Data Analyst Task** – Capture analytics, project, or coursework
- 📝 **Journal Entry** – Mark whether you journaled (Y/N)
- 📚 **Reading Done** – Did you read today? (Y/N)
- 🔥 **Streak Type** – Color code your day: 🟢 great, 🟡 so-so, 🔴 needs improvement
- 🧠 **Notes** – Additional details

## 🙌 Why Use Daily-Tracker?

- Build and maintain strong daily execution habits
- Track progress objectively with quick visual feedback
- Get instant motivation tailored to your performance trends
- Export your habits data for further analysis

## 📄 License

MIT License

***

*Level up your productivity and consistency—track, visualize, and win your daily streak!*

[1](https://github.com/pprotonn/Daily-Tracker/new/main?filename=README.md)
