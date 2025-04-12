# BlockCare EHR – Decentralized Electronic Health Record System

**BlockCare EHR** is a secure, decentralized web application for managing electronic health records using blockchain technology. It ensures that medical data is tamper-proof, access-controlled, and transparently shared only with verified healthcare providers. The application uses **React.js** and **Tailwind CSS** on the frontend, and integrates **Ethereum smart contracts** for identity verification and access control.

---

## Features

- **Blockchain-Based Doctor Verification**
  - Doctors are validated on-chain to ensure trust and authenticity.
- **Decentralized Health Record Access**
  - Patients have full control over who accesses their records.
- **Tamper-Proof Medical Records**
  - Every record update is stored immutably via smart contracts.
- **Responsive UI**
  - Modern, clean interface built with React.js and Tailwind CSS.
- **Off-chain Data Storage (Optional)**
  - Medical files can be stored on IPFS with hash mapping on-chain.

---

## 🛠️ Tech Stack

| Layer            | Technology                            |
|------------------|----------------------------------------|
| Frontend         | React.js, Tailwind CSS                |
| Routing          | React Router (BrowseRouter.js)         |
| Blockchain       | Ethereum, Solidity, Web3.js            |
| Smart Contracts  | Role-based access control, verification |
| Testing          | Jest, React Testing Library            |
| Deployment       | (To be updated: Vercel / Netlify)      |


## Folder Structure
blockcare-ehr/ ├── public/ │ ├── favicon.ico │ ├── index.html │ ├── logo192.png │ ├── logo512.png │ ├── manifest.json │ ├── robots.txt

├── src/ │ ├── App.js │ ├── App.css │ ├── App.test.js │ ├── BrowseRouter.js # Routing logic │ ├── index.js │ ├── index.css │ ├── logo.svg │ ├── reportWebVitals.js │ ├── setupTests.js

├── package.json ├── package-lock.json ├── tailwind.config.js ├── truffle-config.js ├── README.md


---

## Modules Overview

- **Authentication**
  - MetaMask wallet connection
  - Role-based access via smart contracts
- **Doctor Registry**
  - Verified by an admin authority
- **Record Management**
  - Patients can upload/download encrypted records
- **Access Control**
  - Patients grant/revoke doctor access

---

## Use Cases

- Protect sensitive health records from tampering
- Ensure only verified professionals access patient data
- Let patients own and control their health information
- Build a global, interoperable medical data platform

---

## 🔮 Future Enhancements

- **Add IPFS integration** for decentralized storage of medical records
- **Integrate MongoDB** for storing metadata and user activity logs
- **Deploy Smart Contracts on Testnet/Mainnet** via Alchemy or Infura
- **Add QR-based doctor identity verification**
- **Implement user authentication** (e.g., MetaMask or Firebase login)
- **Create an admin dashboard** for hospital-level insights
- **Mobile responsiveness improvements**
- **Enable patient record versioning** and history tracking


## License

This project is licensed under the **MIT License**.  
Feel free to fork, enhance, and contribute — with credit.

---

## Contribution

Want to contribute? Open a pull request or raise an issue. We welcome feedback, bugs, and new ideas!

---

## 🧠 Maintainer

**Akshansh Tyagi**  
📧 Email: [akshanshtyagi2003@gmail.com](mailto:akshanshtyagi2003@gmail.com)  
🔗 LinkedIn: [www.linkedin.com/in/akshansh-tyagi-961691330](https://www.linkedin.com/in/akshansh-tyagi-961691330)

---




