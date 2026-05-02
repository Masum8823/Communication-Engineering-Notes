# Capacity of a Cell — Traffic Load

The traffic load (how busy a cell is) is measured using two things:

---

## 📌 Parameters:

- **λ (lambda)** = Average arrival rate — how many calls arrive per second on average  
- **T** = Average holding time — how long each call lasts on average  

---

## 📊 Offered Traffic Load Formula:

a = λ × T  

👉 The unit of traffic load is **Erlang**.  
👉 One Erlang means one channel is kept completely busy for one full hour.

---

## 📌 Example from the slides:

A cell has 100 MSs. On average, 30 calls are made per hour, and each call lasts 360 seconds (6 minutes).

---

### Step 1:

λ = 30 / 3600 = 0.00833 calls/sec  
T = 360 seconds  

---

### Step 2:

a = (30/3600) × 360 = 3 Erlangs  

---

## 🧠 Final Meaning:

This means the cell carries a traffic load of **3 Erlangs** — equivalent to **3 channels being fully busy for the entire hour**.