
# Hospital Search Mini Project

## 📌 Project Title
Smart Hospital Patient Flow and Bed Management System

## 👨‍💻 Developed By
- K. Mahesh (227Y1A1226)
- P. Nithish Reddy (227Y1A1235)
- T. Shiva Shashank (227Y1A1248)

## 🎓 Guide
P. Jyothi, Assistant Professor  
Academic Year: 2022-2026 | Regulation: R-22

---

## 📝 Description
Smart Hospital Patient Flow and Bed Management System using Python and Flask.  
It enables searching hospitals based on:
- Hospital Name
- City
- Admission of Patients

---

## 🛠️ Technologies Used
- Python
- Flask
- Pandas
- HTML (Jinja2 templating)

---

## 📂 Folder Structure

```
hospital_search_project/
│
├── app.py
├── hospitals_data.xlsx
├── README.md
└── templates/
    └── search.html
```

---

## ▶️ How to Run

1. Extract the zip.
2. Open terminal in the folder.
3. Install dependencies:
   ```
   pip install flask pandas openpyxl
   ```
4. Run the app:
   ```
   python app.py
   ```
5. Open your browser and go to:
   ```
   http://127.0.0.1:5000
   ```

---

## 📊 Dataset Fields
- Hospital Name
- OPD Doctors
- Beds
- Admissions of Patients
- (Optional) City

---

## 🧠 Queuing Logic (Optional Feature)
Patients can be prioritized by severity, if integrated with IoT sensors or triage logic.

---

## 📡 IoT Simulation (Optional Concept)
Static fields in the dataset can represent:
- Available Beds
- Ambulance Availability

Future versions could use sensor-based updates.
