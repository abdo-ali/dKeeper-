# 📝 DKeeper

**DKeeper** is a decentralized note-keeping application built on the **Internet Computer**.  
It allows users to securely **create, view, and delete notes** stored on-chain using **Motoko smart contracts**.

## Technologies Used

- 🧠 **Motoko** — Backend smart contracts on the Internet Computer
- ⚛️ **React.js** — Frontend user interface
- 🧩 **DFINITY SDK (dfx)** — Local development and deployment
- 💻 **Node.js** — Frontend build and dependency management

## 🧰 Getting Started

### ✅ Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [DFINITY SDK](https://internetcomputer.org/docs/current/developer-docs/getting-started/install/)
- [Git](https://git-scm.com/)

### ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/abdo-ali/dKeeper-.git
   cd dKeeper
   ```
2. **Install Node.js dependencies**
   ```bash
   npm install
   ```
3. **Start the local Internet Computer replica**
   ```bash
   dfx start --background
   ```
4. **Deploy the project locally**
   ```bash
   dfx deploy
   ```
5. **Run the frontend**
   ```bash
   npm start
   ```

### 💡 Usage

Once everything is running, open your browser at:  
👉 [http://localhost:8080](http://localhost:8080)
You can now:

- ✍️ Create new notes
- 📖 View existing notes
- ❌ Delete notes  
  All your data is stored **decentrally** on the Internet Computer!

## 🗂️ Project Structure

```
dkeeper/
│
├── src/
│   ├── dkeeper_assets/       # React frontend
│   ├── dkeeper/              # Motoko backend canister
│   └── declarations/         # Auto-generated files (frontend-backend link)
│
├── .dfx/                     # Local build outputs
├── dfx.json                  # DFINITY project configuration
├── package.json              # Node dependencies
├── README.md                 # Project documentation
└── webpack.config.js         # Webpack configuration for React
```

## 🖼️ Screenshot

> Add a preview of your app UI here!
> ![App Screenshot Placeholder](./images/dkeeper-screenshot.png)

## 🌐 Deployment to Mainnet (Optional)

To deploy your project on the **Internet Computer mainnet**, run:

```bash
dfx deploy --network ic
```

Make sure your **identity** is set up and you have enough **cycles** in your wallet.

## 🤝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss your proposal.

## 👤 Author

**Abdelrahman Ali**  
🔗 [GitHub](https://github.com/abdo-ali)  
🔗 [LinkedIn](https://www.linkedin.com/in/abdelrahman-ali-04664a185/)

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and share it.
