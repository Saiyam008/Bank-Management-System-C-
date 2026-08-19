# 🏦 Bank Management System (C++)

A console-based Banking & Account Management System written in standard modern **C++** utilizing Object-Oriented Programming (OOP) and persistent binary file streams (`account.dat`).

---

## 🌟 Key Features

- **💳 Account Lifecycle Management**: Create, view, modify, and close Savings (`S`) and Current (`C`) accounts with minimum balance enforcement.
- **💰 Financial Transactions**: Real-time deposit and withdrawal operations with overdraft / minimum balance validation checks.
- **💾 Disk Persistence**: Seamless state saving and retrieval using binary streams (`fstream`).
- **📊 Ledger & Audit Reports**: Generates tabular summaries of all active accounts, holder names, account types, and balance states.
- **🔍 Fast Search**: Instant account lookup by Account Number.

---

## 📁 Repository Structure

```
├── Source Code      # C++ core application source code
└── README.md
```

---

## 🛠️ Compilation & Execution

```bash
# Compile with modern C++ (g++ / clang++)
g++ -std=c++11 -o bank_system "Source Code"

# Run the executable
./bank_system
```

---

## 📄 License

This repository is released under the [MIT License](LICENSE).
