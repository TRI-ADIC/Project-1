# Usability Testing Tool (Streamlit App)

This is a Python-based Streamlit application developed to automate usability testing. It collects participant consent, demographic data, task performance metrics, and post-test feedback, and then aggregates the results into a report.

---

## 📦 Features

- **Consent Form**: Presents a digital agreement for participation.
- **Demographic Questionnaire**: Collects user information including name, age, occupation, and familiarity with usability tools.
- **Task Page**: Allows participants to perform a task, tracks completion time, success, and notes.
- **Exit Questionnaire**: Collects satisfaction and difficulty ratings, plus open-ended feedback.
- **Report Page**: Displays all submitted data and provides simple statistical summaries.

All data is stored in CSV files inside the `/data` folder.

---

## 🚀 How to Run the Program

### Prerequisites

Make sure you have Python 3.8+ installed, along with `streamlit` and `pandas`. To install the required packages:

```bash
pip install streamlit pandas