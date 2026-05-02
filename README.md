# 📊 YouTube Data Analysis Dashboard

An interactive web application built with **Streamlit** that utilizes the **YouTube Data API v3** to visualize channel metrics, track engagement, and analyze video performance in real-time.

---

## 🚀 Features
*   **Real-Time KPI Tracking:** View total subscribers, lifetime views, and video counts.
*   **Top Video Performance:** Interactive bar charts showing the most viewed videos on a specific channel.
*   **Engagement Analysis:** Calculation of engagement rates (Likes/Comments vs. Views) to identify high-quality content.
*   **Data Exploration:** Dynamic filtering of video data based on tags, dates, or performance tiers.
*   **Clean UI:** Minimalist dashboard design with dark mode support via Plotly.

---

## 🛠️ Tech Stack
*   **Language:** Python 3.x
*   **Frontend/Dashboard:** [Streamlit](https://streamlit.io/)
*   **Data Manipulation:** [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/)
*   **Visualization:** [Plotly Express](https://plotly.com/python/)
*   **API:** [Google APIs Client Library for Python](https://github.com/googleapis/google-api-python-client)

---

## 📋 Prerequisites
Before running the dashboard, you will need:
1.  A **Google Cloud Console** account.
2.  An enabled **YouTube Data API v3**.
3.  An **API Key** (stored securely in a `.env` file or Streamlit secrets).

---

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/youtube-dashboard.git](https://github.com/yourusername/youtube-dashboard.git)
   cd youtube-dashboard
