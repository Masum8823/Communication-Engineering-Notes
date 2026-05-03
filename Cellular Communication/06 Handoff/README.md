# Handoff (Handover)

When you are on a call and moving away from your current Base Station (BS), the signal becomes weak. Then, your Mobile Station (MS) needs to connect to a nearby BS. This switching process is called handoff (handover).

---

## 📌 Process:

First, your phone (MS) is connected to BSᵢ  

• As you move, signal from BSᵢ becomes weaker  
• At the same time, signal from BSⱼ becomes stronger  
• The area between X3 and X4 is called the handoff area  
• Ideally, switching happens at X5, where both signals are equal  

---

## ⚠️ Ping-Pong Problem:

If handoff happens too fast, your phone may keep switching again and again between two BSs continuously (back and forth). This is called the ping-pong problem.

---

## ✅ Solution of Ping-Pong Problem:

To avoid this, handoff is not done immediately.  

It only happens when the signal from BSⱼ becomes stronger than BSᵢ by Threshold  a fixed amount (threshold E, shown as X_th).  

So, not only signal strength, but also your movement (speed and direction) is important for smooth handoff.