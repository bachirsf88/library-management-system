# 📚 Java Library Management System
**By Bachir SOUFiA**  
📧 bachirsf4@gmail.com

![Java](https://img.shields.io/badge/Java-17-blue)
![OOP](https://img.shields.io/badge/OOP-4Pillars-green)

## ✨ Distinct Features
- **Advanced Book Catalog** (Paper/eBooks)
- **Borrower Analytics**
- **Loan History Tracking**
- **Custom Search Algorithms**

```bash
# Clone & Run
git clone https://github.com/bachirsf4/java-library-oop-system.git
cd java-library-oop-system
javac -d out src/**/*.java src/*.java
java -cp out Main
```

## 🏛️ Architecture
```mermaid
classDiagram
    Book <|-- EBook
    Book <|-- PaperBook
    Book "1" -- "1..*" BorrowRecord
    Borrower "1" -- "1..*" BorrowRecord
```
## 📂 Project Structure
```bash
.
├── src/
│   ├── models/       # Book, Borrower classes
│   ├── services/     # Business logic
│   └── utils/        # Helpers
└── README.md
```

