# blockchain-voting-system
A menu-driven Python application that implements a secure voting management system using a simple blockchain, allowing candidate and voter registration, vote casting, and blockchain validation.
# 🗳️ Blockchain Voting Management System

## 📌 Description
This project is a menu-driven console application developed in Python that simulates a secure voting system using a simple blockchain. It allows administrators to register candidates and voters, enables voters to cast votes, and stores each vote as a block in the blockchain to ensure transparency and security.

---

## 🎯 Features

### 👤 Candidate Management
- Add new candidates
- Prevent duplicate candidate IDs

### 🧑‍🤝‍🧑 Voter Management
- Register voters with unique IDs
- Prevent duplicate voter IDs
- Track whether a voter has voted

### 🗳️ Voting System
- Cast vote for a candidate
- Prevent double voting
- Store each vote as a blockchain transaction

### 🔗 Blockchain Functionality
- Each vote is stored in a block
- Blocks are linked using hashes
- Ensures data integrity and immutability

### ✅ Validation
- Validate blockchain integrity
- Detect tampering in the chain

---

## 🛠️ Technologies Used
- Python
- hashlib (for SHA-256 hashing)
- time module (for timestamps)

---

## 👨‍💻 Author
Varad B Kamat
