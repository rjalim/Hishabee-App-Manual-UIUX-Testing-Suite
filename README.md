# Hishabee-App-Manual-UIUX-Testing-Suite
This repository contains manually written UI/UX and functional test cases for the Hishabee mobile application. It includes detailed test scenarios, test cases, and documented bug reports focused on modules like Sell, Purchase, and Payment.

# 📱 Hishabee App - Manual UI/UX Testing Suite

This repository contains a comprehensive manual testing suite for the **Hishabee Mobile Application**, focusing on **UI/UX**, **functional**, and **input validation** test cases. It includes real-world scenarios, bug reports, and detailed documentation that showcase testing efforts across key modules of the app.

---

## 🔍 Modules Covered

- ✅ **Sell Module**
- ✅ **Purchase Module**
- 🔜 [Optional] Payment / Stock / Report (can be added later)

---

## 🧪 Test Coverage

| Test Type           | Description                                                       |
|---------------------|-------------------------------------------------------------------|
| Functional Testing  | Verifies that app features work as expected under valid/invalid inputs |
| UI/UX Testing       | Checks responsiveness, alignment, and visual feedback             |
| Input Validation    | Ensures fields accept only valid input formats                    |
| Security Testing    | Prevents unauthorized access or misuse of app modules             |

---

## 📋 Sample Test Cases

### ✅ TC_Sell_003 – Verify selling more than stock quantity is restricted

- **Type:** Functional
- **Expected Result:** System should prevent selling more than available stock and show a warning
- **Priority:** High
- **Test Data:** Product Quantity: 2, Stock Available: 1

---

### ✅ TC_Purchase_010 – Verify negative price is restricted

- **Type:** Functional
- **Expected Result:** App should not allow negative values in buying/selling price fields
- **Test Data:** Buying Price: -50, Selling Price: -100

---

## 🐞 Sample Bug Reports

### ❌ Bug_Sell_001 – Selling with discount greater than selling price allowed

- **Description:** App allows 300 BDT discount on a product priced at 200 BDT
- **Expected:** Should validate and prevent discount greater than price
- **Status:** Open
- **Severity:** High

---

## ✅ Files Included

- `Sell_Module_TestCases.xlsx` – All UI/UX & functional test cases for the Sell module  
- `Purchase_Module_TestCases.xlsx` – Test scenarios for purchase logic and input validation  
- `BugReports_Hishabee.xlsx` – Documented real-world bugs with steps to reproduce  
- 📸 **Bug Screenshots** (folder) – Visuals supporting reported bugs (optional)

---

## 💡 Purpose of This Project

This project demonstrates practical QA knowledge in:

- Manual test case design
- Real-world mobile app testing
- Bug documentation with severity/prioritization
- QA-focused portfolio building

---

## 🧑‍💻 Author

**MD. Abdul Alim**  
🔗 [GitHub](https://github.com/rjabdulalim)  
🔗 [LinkedIn](https://linkedin.com/in/rjalim)  
📧 rjabdulalim@gmail.com  

---

## 📌 License

This project is shared for educational and professional portfolio use. All product names/logos belong to their respective owners.

---

