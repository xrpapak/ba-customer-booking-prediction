# British Airways Virtual Internship – Customer Booking Prediction

This project is part of the **British Airways Data Science Virtual Experience** on Forage. The objective was to analyze customer booking behavior and build a predictive model that can determine whether a user will complete their booking.

---

## 🎯 Project Objective

- Predict whether a customer will complete a flight booking based on behavioral, demographic, and transactional data.
- Utilize machine learning to extract actionable insights and enhance the optimization of marketing and retention strategies.

---

## Dataset Overview

The dataset contains >50,000 anonymized booking records with features such as:

- **Customer behavior**: wants_extra_baggage, wants_meals, preferred_seat
- **Booking details**: trip_type, sales_channel, booking_origin
- **Flight context**: route, flight_duration, flight_hour, day of week
- **Target**: `booking_complete` (1 = completed, 0 = not completed)

---

## Methodology

1. **Data Preprocessing**
   - Label Encoding for categorical features
   - Null check and structure validation

2. **Model Training**
   - Random Forest Classifier (scikit-learn)
   - 80/20 train/test split with stratification

3. **Evaluation**
   - Classification Report (Precision, Recall, F1)
   - Confusion Matrix
   - Feature Importance Analysis

---

## Results

- **Accuracy**: 85%
- **Precision (Booking = 1)**: 56%
- **Recall (Booking = 1)**: 52%
- **Top Features**:
  - Purchase Lead Time
  - Length of Stay
  - Flight Duration
  - Ancillary preferences (e.g. baggage, meals)
  - Sales Channel

---

## Business Insights

- **Customers booking in advance** are more likely to complete the booking – suggest targeted offers for short-lead users.
- **Ancillary services** (such as baggage and meals) signal high booking intent, making them ideal for upselling.
- **Longer trips** and **holiday profiles** show higher conversion than short business trips.
- **Digital channel (Internet)** is dominant, optimizing the online funnel is critical.

---

## Deliverables

| File | Description |
|------|-------------|
| `British_Airways_Virtual_Internship.ipynb` | Full Python notebook (EDA, modeling, evaluation) |
| `BA - Task 2 - Presentation.pptx` | PowerPoint with methodology, charts, and recommendations |
| `British_Airways_Virtual_Internship.ipynb - Colab.pdf` | PDF export of the full notebook |

---

## Tools Used

- **Python 3** – pandas, scikit-learn, seaborn, matplotlib
- **Google Colab** – notebook environment
- **PowerPoint / HTML** – business presentations

---

## Acknowledgements

This project is part of the **British Airways Data Science Virtual Internship** hosted on [Forage](https://www.theforage.com/). It is a simulated experience and is not affiliated with British Airways' internal systems.

---

## Let's Connect

If you're interested in collaborating or have any questions, feel free to connect via [LinkedIn](https://linkedin.com/in/your-profile) or check more of my work on [GitHub](https://github.com/your-profile).
