# 📘 Zen Class MongoDB Project

This project contains MongoDB shell scripts and use-case queries related to the Zen Class program by GUVI. It includes sample data for collections like `users`, `codekata`, `topics`, `tasks`, `attendance`, `company_drives`, and `mentors`. The project demonstrates inserting data, running queries, and extracting useful insights using MongoDB.

---

## 📄 Contents

- ✅ Data Insertion using `insertMany()`
- ✅ Real-world queries using `find()` and `aggregate()`
- ✅ Sample output based on inserted data
- ✅ PDF report included with all commands, sample data, and final query results

---

## 📂 Collections Used

- `users` – List of Zen Class students
- `codekata` – Problems solved by users
- `topics` – Topics taught during the course
- `tasks` – Tasks assigned/submitted by students
- `attendance` – Attendance logs
- `company_drives` – Company placement drives
- `mentors` – Mentor details
- `mentor_assignment` – Mentee-mentor mapping
- `drive_participation` – Who appeared for which company drive

---

## ❓ Problem Statements & Queries

1. 📌 Find all the topics and tasks taught in the month of **October**
2. 📌 Find all the company drives between **15-Oct-2020 to 31-Oct-2020**
3. 📌 Find all the company drives and students who appeared for placements
4. 📌 Find the number of Codekata problems solved by each user
5. 📌 Find all mentors with mentee count **greater than 15**
6. 📌 Find the number of users **absent** and **task not submitted** between 15-Oct-2020 and 31-Oct-2020

All these queries are available in the **PDF file** included in this repo.

---

## 📦 Run Locally

### 1. Start MongoDB shell

```bash
mongosh
