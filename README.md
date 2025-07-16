# 📚 Attendance Tracker & Reminder System

Yo fam ✨, this is a **Python-based attendance tracker and reminder system** for colleges. It automates the boring attendance reminders and saves your staff's time ⏰.

---

## 🚀 **Problem it solves**

In many colleges:
- Students forget how many leaves they’ve taken.
- Teachers spend **tons of time** checking records and sending reminders manually.
- Paperwork is tiring and inefficient.

---

## 💡 **What this project does**

✅ Takes an Excel sheet as input containing:
- Roll number
- Student mail ID
- Number of leaves taken in each subject

✅ Tracks leave count for each subject.

✅ **Sends email notifications:**
- If leave count reaches **2**, sends reminder to student (“Bro, only 1 leave left 👀”).
- If leave count exceeds **3**, sends emails to **both student and staff** about lack of attendance.

✅ Super easy – just enter:
- **Subject code**
- **Roll number**  
for the student absent that day, and the tracker updates everything for you.

---

## 📝 **Subject codes used**

| Subject                  | Code |
|---------------------------|------|

| Python                    | 1   |
| Data Mining (DM)          | 2   |

---

## 🛠️ **Python modules required**

Install these modules using pip:

```bash
pip install openpyxl
