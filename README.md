
# 📊 Excel Project : Advanced Power Query Transformations

## 🚀 Overview
This project simulates a real-world scenario in the hospitality industry. The objective was to transform messy booking and room data into clean, structured, and insightful datasets using **Excel Power Query**.

---

## 📁 Datasets

### 1. `bookings_data.csv`
- Includes property name, type, city + city code, room IDs, successful bookings, and capacity.

### 2. `rooms_data.csv`
- Contains `room_id` and `room_class` for classifying rooms (Standard, Premium, Deluxe).

📸 **Add Screenshot Here**  
*Screenshot showing a preview of both raw datasets.*

```markdown
![Raw Datasets](images/raw-datasets-preview.png)
```

---

## 🧼 Step 1: Data Cleaning
Tasks performed in Power Query:
- Changed `property_id` to text
- Fixed names like `"Atliq bay"` to `"Atliq Bay"`
- Trimmed whitespace in `property_type`
- Split `city|city_code` column


![](https://github.com/bharadwajdubbaka/Advanced-Power-Query-Transformations/blob/9d1bf876a88f6198e6328e0e66c41a8d7814be49/data%20cleaning%20screenshot.png)



## 🔄 Step 2: Data Transformation
Transformations included:
- Created `Availability Status` column: Sold Out vs. Vacant
- Added `occ%`: bookings ÷ capacity
- Merged with `rooms_data` to add `room_class`
- Reordered columns

![](https://github.com/bharadwajdubbaka/Advanced-Power-Query-Transformations/blob/9d1bf876a88f6198e6328e0e66c41a8d7814be49/data%20transformation%20screenshot.png)

## 📈 Step 3: Extracting Insights
- Extracted `Month Name` from the date
- Identified seasonal booking trends
- Found high occupancy properties using `occ%`

![](https://github.com/bharadwajdubbaka/Advanced-Power-Query-Transformations/blob/9d1bf876a88f6198e6328e0e66c41a8d7814be49/insights%20screenshot.png)

## 💼 Outcome
- Clean, structured dataset ready for business use
- Practical Power Query skills demonstrated
- Foundational project for analyst-level data transformation

📸 **Add Screenshot Here**  
*Final dataset preview showing cleaned + transformed results.*

```markdown
![Final Dataset](images/final-dataset-overview.png)
```

---

## 🧠 Skills Applied
- ✅ Data Cleaning
- ✅ Data Transformation
- ✅ Power Query (Excel)
- ✅ Analytical Thinking
- ✅ Real-world Dataset Simulation

---

## 📎 Project Files
- `Excel_Project_3_Professional_Storytelling.pptx` — With speaker notes
- `bookings_data.csv` and `rooms_data.csv`
- Cleaned data exported (optional)

## 📽 Presentation Preview

[![Presentation Cover](images/ppt-cover-slide.png)](Excel_Project_3_Professional_Storytelling.pptx)


## 📂 Files
- `Insights/`: [file contains Insights](https://github.com/bharadwajdubbaka/Advanced-Power-Query-Transformations/blob/main/insights.xlsx)
- `Presentation/`: [Slide deck used to present insights.](https://github.com/bharadwajdubbaka/Advanced-Power-Query-Transformations/blob/main/Excel_Project_3_Presentation_f.pdf)
- `Video/`: [link to a video presentation.](https://youtu.be/bTCS9tXR11U)

## 💼 Outcome
A structured dataset ready for business reporting and analysis, demonstrating essential skills in Excel-based data processing.

**Author**: Bharadwaj Dubbaka 
**LinkedIn**: [linkedlin profile](https://www.linkedin.com/in/bharadwaj-dubbaka-a6b974172/)  
**Status**: Completed ✅
