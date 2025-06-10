# ComplaintRegistry-Dapp
# VoiceChain – Decentralized Complaint Ledger

> A transparent, decentralized public complaint management system built on the Ethereum blockchain.

## 🚀 Overview

**VoiceChain** is a decentralized application (DApp) that empowers citizens to file complaints, ensures transparency through blockchain immutability, and provides government officials and auditors a secure platform to manage and review these grievances. Built using modern web technologies and Ethereum's Proof-of-Stake consensus model, VoiceChain fosters transparent governance and accountability.

---

## 🏗️ Architecture

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Blockchain:** Ethereum (Sepolia Testnet)
- **Web3 Library:** Ethers.js v6.7.1
- **Wallet Integration:** MetaMask
- **Storage:** 
  - LocalStorage (user data, sessions)
  - Ethereum Blockchain (complaint records)

---

## 🔐 Smart Contract

- **Network:** Ethereum Sepolia Testnet
- **Contract Address:** `0x89f50918c4a1F4C2a5341E36b194bAACAE7d2E0B`
- **Consensus Mechanism:** Proof of Stake (Ethereum 2.0)
- **Language:** Solidity

### Functions:
- `submitComplaint()`
- `updateComplaintStatus()`
- `getComplaint()`
- `getUserComplaints()`
- `complaintCounter` (public variable)

---

## 👥 User Roles

- **Citizens:** Submit and track their complaints
- **Government Officials:** Update status and respond to complaints
- **Auditors:** View all complaints for oversight

---

## 🔑 Authentication System

- Registration: Name, Email, Password, Phone, Address, User Type
- Login: Email/Password with role-based access
- Session Management: Persistent via LocalStorage

---

## 📝 Complaint Lifecycle

- **Statuses:**
  - Pending
  - In Progress
  - Resolved
  - Rejected

- **Categories:**
  - Roads & Infrastructure
  - Water Supply
  - Electricity
  - Sanitation
  - Healthcare
  - Education
  - Corruption
  - Other

---

## 💻 Features

### 🧩 Citizen Features
- Submit complaints with title, category, description, and location
- Real-time blockchain confirmation and tracking
- View personal complaint history

### 🏛 Government Official Features
- View all complaints
- Update status and add responses
- Perform bulk operations

### 🔍 Auditing and Oversight
- Read-only access to all complaints
- Track status and official responses

---

## ⚙️ Advanced Features

- MetaMask Wallet Detection and Integration
- Real-time blockchain syncing
- CSV Export (role-based)
- Search, Filter, and Sort by status/category/title
- Keyboard Shortcuts:
  - `Ctrl + N` – New Complaint
  - `Ctrl + F` – Focus Search
  - `Ctrl + S` – Sync with Blockchain
- Notifications for transaction statuses and system messages

---

## 🔒 Security

- Ethereum PoS-based finality and slashing protection
- Role-based access control
- Wallet verification (via MetaMask)
- Secure password and form validations

---

## 📈 Performance

- Lazy loading for large datasets
- Optimized complaint retrieval and sync
- Offline cache with real-time verification

---

## 🌐 Network Configuration

| Network      | Chain ID | Currency     | Consensus       |
|--------------|----------|--------------|-----------------|
| Sepolia Testnet | 11155111 | SepoliaETH | Proof of Stake  |
| Ethereum Mainnet | 1     | ETH          | Proof of Stake  |



