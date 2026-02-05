# 📊 WhatsApp Chat Analysis & Visualization

This project performs **end-to-end analysis and visualization of WhatsApp group chat data** using Python.  
Raw WhatsApp `.txt` exports are converted into a **clean, structured DataFrame**, followed by **advanced visualizations** to understand user behavior, activity patterns, and engagement trends.

This project is suitable for:
- College Mini / Major Projects
- Data Analytics Demonstrations
- Internship & Placement Portfolios
- Python + Pandas Practice

---

## 🚀 Project Features

### 📂 Data Handling
- Reads raw WhatsApp `.txt` chat exports
- Handles WhatsApp-specific formatting issues
- Supports 12-hour time format with `am/pm`
- Cleans hidden Unicode characters

### 🧹 Preprocessing
- Separates date, user, and message content
- Handles group notifications safely
- Converts message timestamps into `datetime`
- Extracts:
  - Year
  - Month
  - Day
  - Hour
  - Minute

### 📊 Visualizations
- Top active users
- Monthly message distribution
- Hourly activity pattern
- User-specific analysis
- **Day vs Hour activity heatmap**
- Daily messaging timeline
- Emoji usage analysis

### 🛡️ Defensive Coding
- Prevents crashes for empty user selections
- Safely handles missing or malformed data
- Clean error handling for visualization steps

---

## 🧠 Technologies Used

- **Python 3**
- **Pandas** – Data manipulation
- **Regex (re)** – Text extraction
- **Matplotlib** – Data visualization
- **Seaborn** – Heatmaps and advanced plots
- **Emoji** – Emoji detection and analysis

---
## ⚙️ Working of the Project

The WhatsApp Chat Analysis project follows a systematic data analysis pipeline to convert raw chat data into meaningful insights.

### 1️⃣ Data Input
- The project takes a WhatsApp group chat exported in `.txt` format.
- The raw file contains unstructured text with timestamps, usernames, and messages.

### 2️⃣ Data Preprocessing
- The chat file is read using UTF-8 encoding.
- Regular Expressions (Regex) are used to extract:
  - Message date and time
  - User name
  - Message content
- Hidden Unicode characters and formatting issues specific to WhatsApp exports are cleaned.
- Group notifications are handled separately.
- The timestamp is converted into a `datetime` object.

### 3️⃣ Feature Extraction
From the message timestamp, the following features are extracted:
- Year
- Month
- Day
- Hour
- Minute

These features enable time-based analysis and visualization.

### 4️⃣ User-Specific Filtering
- The dataset can be filtered by selecting a particular user.
- Defensive checks are added to ensure that visualizations are generated only when data exists.

### 5️⃣ Data Visualization
- The processed dataset is visualized using multiple plots to analyze user behavior and chat activity patterns.

---

## 📊 Visualizations Included

### 🔹 Overall Group Analysis
- **Top Active Users** – Identifies the most active participants in the group.
- **Monthly Message Distribution** – Shows how chat activity varies across months.
- **Hourly Activity Pattern** – Displays the most active hours of the day.

### 🔹 User-Specific Analysis
- **Monthly Messages per User** – Tracks individual user activity over months.
- **Daily Message Timeline** – Shows message frequency over time.
- **Day vs Hour Heatmap** – Visualizes user activity intensity across days and hours.
- **Emoji Usage Analysis** – Highlights the most frequently used emojis by a user.

These visualizations help in understanding:
- User engagement levels
- Peak activity periods
- Behavioral patterns in group conversations

---

## ✅ Outcome

The project successfully transforms raw WhatsApp chat data into structured insights, making it easy to analyze messaging behavior, identify trends, and visualize communication patterns effectively.

## 🔗 Project Link

You can view and run this project directly on **Google Colab** without any local setup:

🔗 **Google Colab Notebook:**  
https://colab.research.google.com/drive/1u8x__g9r2008vtn_XJ2dkeSpLXCvzn9K?usp=sharing

The notebook contains:
- Complete data preprocessing
- User-specific filtering
- All visualizations
- Defensive error handling

Simply open the link and run the cells sequentially.


