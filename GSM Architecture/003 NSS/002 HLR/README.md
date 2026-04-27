# Home Location Register (HLR)

HLR is the **permanent, central database** of the GSM network.  
It works as the **master file for all subscribers**.

---

## 📂 What Does HLR Store?

- Details of every **SIM card**
- Each SIM has a unique ID:
  - **IMSI (International Mobile Subscriber Identity)**  
  → Acts as the **primary key** of each HLR record
- GSM services subscribed by the user
- **GPRS settings** for packet data access
- Current location of the subscriber
- Call divert settings for each:
  - **MSISDN (user’s phone number)**

---

## ⚙️ Responsibilities of HLR

- Manages **service profiles**
- Maps **subscriber identities**
- Handles:
  - Call barring  
  - Call forwarding  
- Passes subscription records to the **VLR** when needed
- Receives and processes **MAP (Mobile Application Part) messages**
  - Example: location update when the user moves

---

## 🧠 Key Concept

HLR contains **permanent (static) subscriber data**.  
It knows everything about a user as a registered subscriber in the network.

---

## 🧠 Quick Summary

HLR is the master database of GSM that stores all subscriber-related information and supports mobility management by interacting with other network components like VLR.