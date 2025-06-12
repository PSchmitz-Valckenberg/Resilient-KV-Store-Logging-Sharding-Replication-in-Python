# Resilient KV Store: Logging, Sharding & Replication in Python

A hands-on database systems project implementing core reliability and availability mechanisms in Python. This educational project showcases a simplified, but conceptually rich key-value (KV) store featuring:

- ✅ Undo/Redo Logging  
- 🧠 File-based Recovery  
- ⚙️ Sharding for Availability  
- 🔁 Node Replication for Fault Tolerance  

---

## 🔍 Overview

This project was built as part of the **Database Systems** course at the **Technical University of Munich (TUM)**, exploring practical implementations of reliability and availability strategies used in modern database systems.

It is divided into two main parts:

---

## 🧱 Part 1 – Logging & Recovery

Simulates crash recovery in databases using a key-value store and logs:

- **Redo Logging:** Replaying committed transactions.
- **Undo Logging:** Rolling back uncommitted changes.
- **Recovery Mechanism:** Reconstructs the state from log files after a simulated failure.

### ✅ All 22/22 tests passing.

---

## 🛰️ Part 2 – Sharding & Replication

Explores high availability through sharding and data resilience through replication:

- **Sharded KV Store** using hashing.
- **Node failure simulation** and recovery testing.
- **Replica creation and usage** for recovering lost data.

### ✅ All functional components tested and verified.

---

## 📦 Technologies Used

- `Python 3.11+`
- `pickleDB` for persistent KV storage
- `File I/O` for simulating physical storage
- `Unit tests` for robustness verification

---

## 🧠 What I Learned

- Real-world mechanisms for **fault-tolerant** data systems
- Concepts like **ACID properties**, **consistency**, and **durability**
- How to simulate and recover from **node failures** and **crashes**
- The value of clean abstractions in building **resilient distributed systems**

---

## 🚀 Run Locally

1. Install dependencies:

```bash
pip install -r requirements.txt
