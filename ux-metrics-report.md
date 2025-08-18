#  UX Metrics Report

##  Goal

To analyze a key UX metric from Focus Bear and suggest an improvement based on data trends.

---

##  Selected UX Metric: **Drop-off Rate in Onboarding**

**Why this metric matters:**  
Onboarding is the first impression of the app. If users drop off early, they may never return. A high drop-off rate signals confusion, lack of value clarity, or overwhelming steps.

---

## 📈 Data Analysis (via PostHog)

- **Current trend:** Drop-off rate during onboarding has remained high (over 40%) across the past month.
- **Where users drop:** Most users exit after setting the first habit or before starting the first focus session.
- **Possible causes:**
  - The onboarding process lacks clear guidance.
  - Too many steps too soon.
  - Users don’t yet understand how the app benefits them.

---

## 📝 Reflection

### 1. If a UX metric shows poor user engagement, how would you determine the cause?
I'd start by combining **quantitative data** (e.g., click maps, session time, drop-off points) with **qualitative insights** (e.g., user interviews, comments). Watching session recordings can reveal if users are confused, misclicking, or abandoning due to friction.

### 2. What are the risks of relying too much on numbers instead of qualitative feedback?
Numbers don’t explain *why* a problem happens. You might miss context like emotional friction, unclear copy, or accessibility issues. Relying purely on data can lead to fixing the wrong things or prioritizing surface-level wins.

### 3. How can UX designers use metrics to convince stakeholders?
By connecting metrics to **user impact** and **business outcomes**. For example: “Reducing onboarding drop-off by 10% can lead to a 15% increase in active users.” Data makes the case for investing in usability stronger.

---

##  Data Analysis (via PostHog)
<img width="1243" height="781" alt="Screenshot 2025-08-18 at 2 23 06 pm" src="https://github.com/user-attachments/assets/e4b548ad-266f-42d8-a300-ede8d946fa0e" />




- **Current trend (last 7 days):** Total conversion rate = **3.59%**, with an average time to convert of ~13h 43m.
- **Where users drop:** 
  - From **Login → Complete Morning Routine**, 82.63% drop off (138 out of 167 users).
  - From **Complete Morning Routine → Start Focus Session**, 79.31% drop off (23 out of 29 users).
- **Possible causes:**
  - Morning routine setup may feel too complex or time-consuming.
  - Users don’t clearly understand the link between completing routines and starting a focus session.
  - Lack of motivation/value communication early on may cause users to abandon before experiencing the app’s main benefit.


##  Suggested UX Improvement

- **Simplify morning routine setup**: Offer a default “starter routine” instead of requiring full customization.
- **Early focus session prompt**: Encourage users to try a focus session *before* completing a full routine, so they immediately see the app’s value.
- **Progress feedback**: Show a simple message like *“Nice work! You’re one step away from starting your first focus session.”* to guide users through.

##  Discussion with PM/Dev

- **Tracking method**: PostHog currently tracks `login`, `complete-morning-routine`, and `start-focus-session-manual`. These events allow us to see where onboarding fails.
- **Insights**: The data shows onboarding is heavily front-loaded, with too many users dropping at the “morning routine” stage.
- **Next step**: Discuss running an A/B test with a shorter onboarding flow, where users can launch a focus session earlier to reduce initial friction.




