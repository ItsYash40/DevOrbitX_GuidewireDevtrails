# 🚀 IncomeShield  
## AI-Powered Weekly Income Protection for Delivery Workers  

---

## 📌 Overview  
IncomeShield is an AI-powered platform designed to protect the weekly income of delivery workers from external disruptions such as bad weather, pollution, or curfews.  
Instead of traditional insurance focused on assets or health, IncomeShield focuses on a critical gap — loss of daily earnings.  

---

## ❗ Problem Statement  
Delivery partners in food, grocery, and e-commerce platforms rely on daily work for income.  

However, events like:  
- Heavy rainfall  
- Extreme heat  
- High pollution (AQI)  
- Floods or curfews  

can completely stop their ability to work.  

This leads to zero income for the day, creating financial instability for workers who live week-to-week.  

---

## 🎯 Target Persona  
We focus on food delivery partners working with platforms like Zomato and Swiggy.  

**Why this persona?**  
- Daily earning dependency  
- Highly affected by weather & restrictions  
- Easy to model for a focused MVP  

---

## 💡 Proposed Solution  
IncomeShield is a weekly income protection platform that:  

- Detects external disruptions using real-time data  
- Automatically verifies impact  
- Triggers instant compensation  

✅ No manual claims  
✅ No paperwork  
✅ Fully automated payouts  

---

## 🌍 Real-Life Scenario  
A delivery partner in Mumbai subscribes to a weekly plan.  

On a day of heavy rainfall:  
- He cannot complete deliveries  
- The system detects disruption  
- Verifies activity pattern  
- Automatically credits compensation  

---

# 🔄 System Workflow  

## 🧭 End-to-End User Journey  

![Workflow](docs/workflow.png)

---

## ⚙️ Technical Workflow  

![Architecture](docs/architecture.png)

---

## ⚙️ Application Workflow  

1. **Onboarding**  
   User enters location, platform, work area, and earnings  

2. **Risk Profiling**  
   AI calculates risk based on location, weather, and history  

3. **Plan Creation**  
   Weekly premium assigned  

4. **Monitoring**  
   Real-time tracking of weather, AQI, and disruptions  

5. **Trigger Detection**  
   Threshold crossed → policy activated  

6. **Claim Automation**  
   No manual claim required  

7. **Payout**  
   Compensation via UPI / wallet  

8. **Dashboard**  
   View coverage, payouts, and insights  

---

## 💰 Weekly Premium Model  

Designed to match gig workers’ earning cycles  

| Risk Level  | Weekly Premium |
|------------|---------------|
| Low Risk   | ₹20/week      |
| Medium Risk| ₹30/week      |
| High Risk  | ₹40–₹50/week  |

**Premium depends on:**  
- Location & delivery zone  
- Seasonal weather patterns  
- Historical disruptions  
- Average earnings  

---

## ⚡ Parametric Triggers  

Payouts are triggered only when measurable conditions exceed thresholds:  

- 🌧 Heavy rainfall  
- 🌡 Extreme heat  
- 🌫 High AQI  
- 🚫 Curfews / zone closures  
- 📉 App or delivery disruptions  

---

## 🤖 AI / ML Integration  

### 1. Risk-Based Pricing  
- ML model calculates risk score  
- Determines weekly premium  

### 2. Fraud Detection  
- Detects fake GPS  
- Flags duplicate claims  
- Identifies abnormal patterns  

### 3. Prediction & Alerts  
- Predicts high-risk days  
- Notifies workers in advance  

---

## 📱 Why Mobile-First?  

Delivery workers primarily use smartphones  

- Fast onboarding  
- Real-time alerts  
- Easy accessibility  

👉 Implemented as a PWA (Progressive Web App) for faster deployment  

---

## 🛠 Tech Stack  

**Frontend:**  
- React.js   

**Backend:**  
- Node.js   

**Database:**  
- PostgreSQL  

**AI/ML:**  
- Python, scikit-learn  

**APIs:**  
- Weather API  
- AQI API  
- Mock curfew API  

**Payments:**  
- Razorpay (test mode)  

**Deployment:**  
- Vercel  

---

## 📂 Project Structure  
IncomeShield/
│
├── frontend/
├── backend/
├── ai-model/
├── docs/
│ ├── architecture.png
│ ├── workflow.png
│
├── scripts/
├── README.md


---

## 🧪 Development Plan  

### Phase 1  
- Persona finalization  
- Workflow design  
- Concept validation  

### Phase 2  
- User onboarding  
- Policy creation  
- Premium calculation  
- Basic claim automation  

### Phase 3  
- Fraud detection  
- Payout simulation  
- Analytics dashboard  
- UI/UX improvements  

---

## ✅ Feasibility  

This solution is practical because:  

- Narrow and focused scope  
- Uses publicly available data  
- Simple weekly pricing model  
- Automated payout logic  
- Scalable AI integration  

---

## 📢 Future Scope  

- Integration with delivery platforms  
- Real-time GPS validation  
- Advanced ML risk prediction  
- Multi-city scaling  
