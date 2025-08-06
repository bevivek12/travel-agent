# 🌍 Travel Agent –AI Travel Planner

![Image](https://github.com/user-attachments/assets/e9e355de-3b2c-4785-af27-4953eba51348)

---

## 🧠 Problem Statement

Travel planning involves multiple steps — booking flights, reserving hotels, designing itineraries, managing budget, current weather at destination and handling schedules. Doing this manually is tedious and fragmented across different platforms.

**Can we automate the complete travel planning process using collaborative AI agents?**

---

## 🎯 Project Goal

To build a **multi-agent system** using`LangChain` that automates the end-to-end travel planning experience through intelligent, role-based agents working together.

---

## ✅ Task Delegation (Agent Roles)

| 👤 **Agent**       | 🎯 **Responsibility**                                              |
|--------------------|--------------------------------------------------------------------|
| 🛫 Travel Planner  | Designs the full travel itinerary based on the user's preferences |
| 🏨 Hotel Agent     | Suggests hotel options tailored to location and budget            |
| 💸 Budget Advisor  | Estimates total travel cost including stay, commute, etc.         |
| 🗺️ Local Guide     | Recommends attractions, restaurants, and activities               |
| 📅 Scheduler       | Aligns itinerary events into a feasible and smooth timeline       |

---

## ⚙️ Technologies Used

- 🧠 **LangChain** – Agent memory and context handling   
- 🔗 **LLMs** – Language reasoning and task execution  
- 🐍 **Python** – Main orchestration language  
- 🌐 **Streamlit (optional)** – For UI interface  

---

## 🚀 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/bevivek12/travel-agent.git
cd travel-agent

# 2. Create a virtual environment
python -m venv venv
# Activate it:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the application
python app.py





