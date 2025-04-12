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

## Tech Stack

| Layer         | Technology                        |
|---------------|-----------------------------------|
| Frontend      | React.js, Tailwind CSS, FontAwesome |
| Blockchain    | Ethereum, Solidity, Web3.js / Ethers.js |
| Smart Contracts | Role-based access control, Doctor Verification |
| Optional Storage | IPFS / MongoDB / Firebase |
| Deployment    | Vercel / Netlify (Frontend), Alchemy / Infura (Node)

---

## Folder Structure
blockcare-ehr/
├── public/
│   ├── index.html
│   └── favicon.ico

├── src/
│   ├── assets/                  # Images, icons, logos
│   ├── components/              # Reusable UI components (Navbar, Cards, Forms)
│   ├── pages/                   # Main pages (Dashboard, Login, RecordUpload)
│   ├── contracts/               # Compiled and raw smart contracts
│   │   ├── AccessControl.sol
│   │   ├── DoctorRegistry.sol
│   │   └── artifacts/           # Truffle/Hardhat output (if used)
│   ├── context/                 # React Context for auth, wallet, user role
│   ├── hooks/                   # Custom React hooks (e.g. useWallet, useRecords)
│   ├── utils/                   # Helper functions (e.g. IPFS, formatting, validations)
│   ├── styles/                  # Tailwind config or custom CSS
│   ├── App.js
│   ├── index.js
│   └── config.js                # App-wide configs (contract addresses, constants)

├── smart-contracts/            # Source and deployment scripts for smart contracts
│   ├── contracts/
│   ├── migrations/
│   ├── test/
│   ├── truffle-config.js       # or hardhat.config.js

├── .env                        # API keys, Infura/Alchemy keys
├── .gitignore
├── README.md
├── package.json
└── hardhat.config.js / truffle-config.js


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

## Future Enhancements

- IPFS/Filecoin integration for fully decentralized file storage
- Zero Knowledge Proofs for privacy-preserving verification
- Cross-chain EHR record interoperability
- AI integration for medical data analytics

---

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




