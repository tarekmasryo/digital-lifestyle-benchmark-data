# 📘 Data Dictionary — Digital Habits & Mental Health (2025)

**File:** `Data.csv`  
**Rows:** 3,500 **Columns:** 24 **Target:** `high_risk_flag`  
**Domain:** Digital Wellbeing · Behavioral Science · Mental Health  

| Column | Type | Description |
|:--------|:-----|:------------|
| participant_id | str | Unique anonymized respondent ID (no personally identifiable data). |
| age | int | Participant age in years (15–65). |
| gender | str | Gender identity: Male / Female / Other. |
| region | str | Participant’s region of residence (binned to protect privacy). |
| income_level | str | Self-reported income category: Low / Medium / High. |
| education_level | str | Highest completed education: High School / Bachelor / Master / Doctorate. |
| daily_screen_time | float | Average daily screen time in hours (phone + tablet + PC). |
| phone_unlocks | int | Number of times the phone is unlocked per day. |
| notifications_per_day | int | Average number of notifications received per day. |
| social_media_hours | float | Daily time spent on social media (subset of total screen time). |
| study_time | float | Daily time spent studying or learning (hours). |
| work_hours | float | Daily work or professional activity duration (hours). |
| sleep_hours | float | Average sleep duration in hours (3–12 typical range). |
| physical_activity | float | Hours per day spent on physical exercise or walking. |
| stress_level | int | Self-rated stress level (1–10; higher = more stress). |
| anxiety_level | int | Self-rated anxiety level (1–10; higher = more anxiety). |
| depression_level | int | Self-rated depression level (1–10; higher = more depression). |
| happiness_score | int | Self-rated happiness (1–10; higher = more positive affect). |
| focus_score | int | Ability to maintain focus (1–10; higher = better focus). |
| productivity_score | int | Self-rated productivity (1–10; higher = better performance). |
| emotional_stability | int | Overall emotional stability (1–10; higher = more stable). |
| screen_to_sleep_ratio | float | Ratio between screen time and sleep hours — indicator of balance. |
| social_work_ratio | float | Ratio of social media time to work hours — digital lifestyle index. |
| wellbeing_index | float | Composite index (0–100) summarizing wellbeing indicators. |
| high_risk_flag | int | **Target variable** — 1 = high wellbeing risk, 0 = low risk. |

---
 
