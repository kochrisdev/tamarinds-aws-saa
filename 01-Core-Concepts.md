# Core AWS Concepts

## 🌍 Global Infrastructure

- Region = geographical area
- AZ (Availability Zone) = data center
- Edge Locations = CDN (CloudFront)

👉 Exam Tip:
Always design for **Multi-AZ**, not single AZ.

---

## ⚙️ Shared Responsibility Model

| AWS | You |
|-----|----|
| Hardware | OS |
| Network | Apps |
| Data center | Data |

---

## 🧠 Key Principles

### 1. High Availability
- Multi-AZ
- Load balancing

### 2. Scalability
- Auto Scaling
- Serverless

### 3. Elasticity
- Scale up/down automatically

### 4. Fault Tolerance
- No single point of failure

---

## 🔥 Most Important Idea (Exam)

> Design systems that **fail gracefully**

---
