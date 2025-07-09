# Period Tracking Data Analysis 🩸📊

This project analyzes personal period tracking data exported from a mobile app over multiple years. The data includes daily logs during period of symptoms, mood,energy level, flow, basal body temperature (BBT), sleep duration, and more.

---


## 📊 What This Project Does

- Loads and cleans non-relational health tracking data (JSON)
- Normalizes the structure into a tabular format using `pandas`
- Handles nested values like `{"option": "sad"}` and lists like `[{"option": "light"}]`
- Removes uninformative fields (e.g., `id`, constant values like `'collection_method': 'pad'`)
- Converts data to a "wide" format with each type as a column
- Prepares the data for further time-series analysis or visualization

---

## 🔍 Types of Data Analyzed

- **Flow**: light, medium, heavy
- **Symptoms**: cramps, headaches, fatigue, etc.
- **Mood/Feelings**: sad, sensitive, anxious, happy, etc.
- **Stool**: ok, diarrhea
- **Sleep Duration**: numeric in minutes
- **Temperature (BBT)**: Celsius values
- **Tags**: manually added labels

---

## 🧠 Skills & Tools Used

- Python 🐍
- pandas 📊
- JSON parsing
- Data wrangling (pivoting, cleaning, flattening nested structures)
- Git + GitHub for version control
- Jupyter notebooks

---

## 🚧 Future Work

- Trend visualization (e.g., flow vs mood, or sleep duration over time)
- Correlation analysis between symptoms and cycle events
- Time-series modeling

---

## ⚠️ Note

- This project uses **personal health data**. The dataset is kept private and is not shared publicly.
- The techniques used here are applicable to any structured or semi-structured health tracking dataset.

---

## 📬 Contact

Feel free to reach out if you're working on a similar project or want to collaborate!

