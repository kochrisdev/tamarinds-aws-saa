# VPC (Virtual Private Cloud)

## 🧠 What is VPC?
Your private network in AWS.

---

## 🔑 Components

- Subnets (Public / Private)
- Route Tables
- Internet Gateway
- NAT Gateway

---

## 🌐 Public vs Private

| Type | Access |
|------|------|
| Public | Internet |
| Private | Internal |

---

## 🔥 Key Patterns

### Public Subnet
- Load Balancer
- Bastion Host

### Private Subnet
- App servers
- Databases

---

## 🚪 NAT Gateway

- Allows private instances → internet
- No inbound traffic

---

## ⚠️ Exam Traps

- DB should NEVER be public
- NAT is for outbound only

---

## 🧪 Architecture
