# Mobile Switching Center (MSC)

MSC is the **heart of the GSM network**.  
Almost everything in the network passes through it.

Technically, the MSC is a **regular ISDN (Integrated Services Digital Network) exchange**,  
but it has additional responsibilities because users are mobile.

---

## 📞 Functions of MSC

- Performs all **telephony switching**
- Controls calls to and from other networks:
  - **PSTN (Public Switched Telephone Network)**
  - **PLMN (Public Land Mobile Network)**
- One MSC can handle **multiple BSCs**
- Two MSCs communicate using the **E-Interface**

---

## 📡 Mobility Management

Unlike a normal telephone exchange, MSC must handle moving users:

- **Location Registration**  
  → Tracks the current location of a user  

- **Handover (Handoff)**  
  → Transfers connection when a user moves out of range  
  → Handles:
  - Inter-BSC handover  
  - Inter-MSC handover  

---

## 🔗 MSC Connections

- An MSC connects to **one or more VLRs**
  - All mobile stations under that MSC are managed by the same VLR  

- Each MSC typically communicates with **one EIR**

---

## 🚀 MSC-S (MSC Server)

- A modern and more powerful version of MSC  
- Used in **high-capacity mobile core networks**
- Controls switching in circuit-switched networks  

---

## 🧠 Quick Summary

MSC is the central switching unit of the GSM network.  
It manages calls, mobility, and communication between different networks while working with databases like VLR and EIR.