# 👤 Smart Profile Builder (Python)

🎯 **A terminal-based program to collect, clean, and summarize user profile data for internship applications — could be implemented in a youth empowerment center.**

This project helps users generate digital profiles by collecting their full name, age, email, and interests. It cleans the data, analyzes their age group, and displays a neat, formatted profile — all using only Python basics.

---

## 🚀 Features

| Feature                                  | Description                                                                 |
|------------------------------------------|-----------------------------------------------------------------------------|
| 📝 Input Collection                      | Collects full name, age, email, and interests                              |
| 🧹 Data Cleaning                         | Strips spaces, capitalizes names, lowers emails, removes duplicates        |
| 🔎 Age Group Classification              | Categorizes users as **Teen**, **Young Adult**, or **Other**               |
| 📚 Interest Analysis                     | Shows interest count, first & last, sorted alphabetically                  |
| 🔁 Multiple Profile Entries              | Allows users to enter more than one profile in a session                   |
| ✅ Internship Eligibility Check          | Tells if user is eligible (age ≥ 18)                                       |
| 🎨 Profile Formatting                    | Uses both `f-strings` and `.format()` for clear output formatting          |

---

## 📁 Folder Structure

```
smart-profile-builder/
│
├── smart_profile_builder.py   # Main Python script
└── README.md                  # Project documentation
```

---

## 🧾 Pseudocode (Planning)

```text
START

Ask user for: full name, age, email, interests
Ensure age is a number
Clean all inputs:
  - Strip whitespace
  - Capitalize name
  - Lowercase email
Split interests into list → remove duplicates → sort
Classify age group:
  - 13–17 → Teen
  - 18–25 → Young Adult
  - Else → Other
Display:
  - Name reversed and uppercased
  - Age group
  - Interest count
  - First and last interest
  - Sorted list of interests
  - Internship eligibility message

Ask: Add another profile? If yes → repeat, else → exit

END
```

---

## 📌 Example Output

```
Enter your full name: Peace Agbaji
Enter your age: 20
Enter your email address: peace@neocloud.com
Enter 3 interests (comma-separated): Art, Coding, Coding

📄 Profile Summary
Name (reversed & uppercase): IJABGA ECAPE
Age Group: Young Adult
Number of Interests: 2
First Interest: Art
Last Interest: Coding
Sorted Interests: Art, Coding
✅ You are eligible for internship.
```

---

## 🛠️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/PeaceDS/smart-profile-builder.git
   ```

2. Navigate into the folder:
   ```bash
   cd smart-profile-builder
   ```

3. Run the script:
   ```bash
   python smart_profile_builder.py
   ```

---

## 📚 Concepts Practiced

- String methods (`strip`, `title`, `lower`)
- Lists and sets
- Conditional logic (`if`, `elif`, `else`)
- Loops (`while`, `for`)
- Data cleaning and user input
- Formatting

---

## 👩🏽‍💻 Author

**Peace Chinecherem Agbaji**  
📧 peace.agbaji.243407@unn.edu.ng  
🔗 [LinkedIn](https://www.linkedin.com/in/peace-chinecherem-agbaji-773299257)

---

> ⭐ If this project helped you learn or build, please star the repo and share it with others!
