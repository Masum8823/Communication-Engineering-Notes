# Authentication Centre (AuC)

AuC is the **security unit** of the GSM network. It is always integrated with the HLR — they work together as the same unit.

---

## 📌 What does AuC store for each subscriber?

• The IMSI number  
• The individual authentication key Ki  
• A version of A3 and A8 algorithms  

---

## 🔑 What is Ki?

Ki is the **Subscriber Authentication Key**. It is given to each subscriber along with their IMSI. The same Ki is stored both in the AuC and inside the SIM card.

---

## 🔄 How does AuC produce a Triplet?

AuC follows these 3 steps to create one triplet:

1. A random number is generated called RAND.  
2. RAND and Ki are used together to calculate two things — the Signed Response (SRES) and the Ciphering Key (Kc).  
3. All three values — RAND, SRES, and Kc — are delivered together to the HLR as one triplet.  

The HLR then delivers these triplets to the MSC/VLR when needed. The VLR always keeps at least one triplet ready for authentication.

---

## 🧠 One word answer:

AuC generates a secret challenge (triplet) to verify a subscriber's identity before entering a user inside the network.