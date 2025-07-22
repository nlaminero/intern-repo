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

## ✅ Suggested UX Improvement

**Idea:** Add a 1-screen interactive onboarding overlay/tutorial  
- Use tooltips or highlight features step-by-step  
- Keep language simple and benefits-focused  
- Add progress indicator (e.g., “Step 1 of 3”)

**Expected Impact:**  
Improves user understanding, increases motivation to complete onboarding, and clarifies how the app works right away.

---

## 🤝 Discussion with PM/Dev

- **Tracking method:** PostHog captures screen transitions and exits during onboarding.
- **Insight:** Users often skip before even trying the timer or first routine. Devs can tag specific steps to isolate where exactly the issue occurs (e.g., onboarding step 1 vs. 3).

---

## 📌 Summary

| Metric | Drop-off rate in onboarding |
|--------|-----------------------------|
| Problem | Users leave early, don’t complete setup |
| Root Causes | Lack of clarity, too many steps, low initial motivation |
| Suggested Fix | Add short interactive onboarding with benefits + tooltips |
| Team Involvement | Coordinate with PM + Dev for tracking updates and implementation |
