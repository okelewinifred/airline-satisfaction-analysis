# ✈️ Airline Passenger Satisfaction Analysis

A data analysis project exploring what drives passenger satisfaction across 129,880 airline records — uncovering key service gaps, segment disparities, and actionable recommendations for improvement.

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Tools Used](#tools-used)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Author](#author)

---

## Project Overview

This project analyses airline passenger satisfaction survey data to identify:
- Which passenger segments are most and least satisfied
- Which service dimensions have the greatest impact on satisfaction
- Where the airline should focus improvement efforts

The analysis covers 14 service dimensions including seat comfort, in-flight Wi-Fi, online boarding, food & drink, baggage handling, and more.

---

## Dataset

| Property | Detail |
|----------|--------|
| **File** | `Airline_data.xlsx` |
| **Records** | 129,880 passengers |
| **Features** | 24 columns |
| **Target variable** | Satisfaction (Satisfied / Neutral or Dissatisfied) |

### Features include:
- **Demographics:** Gender, Age
- **Travel info:** Customer Type, Type of Travel, Class, Flight Distance
- **Operational:** Departure Delay, Arrival Delay
- **Service ratings (1–5):** Online Boarding, Seat Comfort, In-flight Wi-Fi, Food & Drink, Cleanliness, Leg Room, Baggage Handling, In-flight Entertainment, and more

---

## Key Findings

### Overall Satisfaction
| Outcome | Count | Percentage |
|--------|-------|------------|
| Neutral or Dissatisfied | 73,452 | 56.6% |
| Satisfied | 56,428 | 43.4% |

### Satisfaction by Segment
| Segment | Satisfied |
|---------|-----------|
| Business class | 69.4% |
| Economy Plus class | 24.6% |
| Economy class | 18.8% |
| Business travel purpose | 58.4% |
| Personal travel purpose | 10.1% |
| Returning customers | 47.8% |
| First-time customers | 24.0% |

### Top & Bottom Service Ratings (avg out of 5)
| Rank | Service | Avg Rating |
|------|---------|------------|
| 🏆 Best | In-flight Service | 3.64 |
| 🏆 Best | Baggage Handling | 3.63 |
| ⚠️ Worst | In-flight Wi-Fi | 2.73 |
| ⚠️ Worst | Ease of Online Booking | 2.76 |

### Biggest Satisfaction Driver
Online Boarding shows the largest gap between satisfied (4.03) and dissatisfied (2.66) passengers — a difference of **1.37 points**, making it the single highest-leverage service to improve.

---

## Recommendations

1. **Fix Economy class experience** — 58,309 economy passengers with only 18.8% satisfaction is the highest-impact area. Focus on seat comfort, leg room, and cleanliness.

2. **Overhaul the digital product** — In-flight Wi-Fi (2.73) and online booking (2.76) are the two lowest-rated services. Modern travellers expect seamless digital experiences.

3. **Build a first-time passenger strategy** — 76% of first-time passengers leave dissatisfied. A better onboarding experience can convert them into loyal returning customers.

4. **Target the leisure/personal travel segment** — With only 10.1% satisfaction, personal travellers are almost entirely underserved. Tailored offerings and better value are needed.

5. **Improve short-haul experience** — Dissatisfied passengers flew an average of 930 miles vs 1,530 for satisfied ones. Short-haul comfort and convenience need attention.

6. **Protect existing strengths** — In-flight service and baggage handling are genuine bright spots. Maintain these standards and highlight them in marketing.

---

## Tools Used

- **Microsoft Excel** — data storage and initial exploration
- **Python (pandas)** — data analysis and statistical summaries
- **Claude AI** — insight generation and dashboard visualisation

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/okalewinifred/<your-repo-name>.git
   ```

2. Open the dataset:
   ```
   Airline_data.xlsx
   ```

3. Run the analysis script (if applicable):
   ```bash
   python analysis.py
   ```

---

## Project Structure

```
📦 airline-satisfaction-analysis
 ┣ 📄 README.md               ← You are here
 ┣ 📊 Airline_data.xlsx        ← Raw dataset
 ┣ 📓 analysis.py              ← Analysis script (optional)
 ┗ 📁 outputs/                 ← Charts and reports
```

---

## Author

**okalewinifred**
- GitHub: [@okalewinifred](https://github.com/okalewinifred)

---

*This project was completed as part of a data analysis portfolio.*
