# 🩸 Blood Cancer Management System  LINK : https://asset-hub--av954416.replit.app/login

A full-stack web application designed to manage and analyze blood cancer patient data. This system helps hospitals and researchers track diagnosis, treatment, survival, and cost data in a centralized database.


LINK : https://asset-hub--av954416.replit.app/login

---

## 🚀 Features

### 🔐 Authentication

* Login system with roles:

  * Admin
  * Doctor
  * Researcher

### 👨‍⚕️ Patient Management

* Add / Edit / Delete patients
* Store:

  * Name, Age, Gender, Contact
  * Cancer Type & Subtype

### 🧪 Diagnosis Module

* Store lab reports:

  * WBC, RBC, Platelets, Hemoglobin
* Upload reports (optional)

### 💊 Treatment Tracking

* Chemotherapy
* Radiation Therapy
* Bone Marrow Transplant

### 📊 Survival Tracking

* Diagnosis date
* Follow-ups
* Survival status
* Auto survival duration

### 💰 Cost Tracking

* Medicine cost
* Hospital cost
* Total expenditure

### 📈 Dashboard & Analytics

* Total patients
* Cancer distribution
* Age & gender analysis

### 🤖 AI Prediction (Leukemia Risk)

* Input:

  * WBC, Platelets, etc.
* Output:

  * High Risk
  * Medium Risk
  * Low Risk

---

## 🧠 AI Model Logic

```js
if (wbc > 10000 && platelets < 150000) {
  return "High Risk";
} else if (wbc > 8000 || platelets < 200000) {
  return "Medium Risk";
} else {
  return "Low Risk";
}
```

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js, Express
* **Database:** SQLite
* **Authentication:** bcrypt
* **API:** REST

---

## 📁 Project Structure

```
blood-cancer-system/
│
├── backend/
├── frontend/
├── package.json
├── README.md
├── .gitignore
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/blood-cancer-system.git
cd blood-cancer-system
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Server

```bash
npm start
```

Server runs at:
👉 http://localhost:3000

---

## 🔑 Demo Credentials

| Role       | Email                                                     | Password    |
| ---------- | --------------------------------------------------------- | ----------- |
| Admin      | [admin@registry.com](mailto:admin@registry.com)           | password123 |
| Doctor     | [doctor@registry.com](mailto:doctor@registry.com)         | password123 |
| Researcher | [researcher@registry.com](mailto:researcher@registry.com) | password123 |

---

## 🔒 Security Features

* Password hashing using bcrypt
* Role-based access control

---

## 📌 Future Enhancements

* 🔥 Machine Learning model integration
* 📊 Advanced dashboards (Chart.js)
* 📄 PDF report generation
* ☁️ Cloud deployment

---

## 🎯 Project Objective

To solve real-world healthcare challenges:

* Centralized cancer registry
* Integrated diagnosis & treatment tracking
* Survival and cost analysis
* Research-ready dataset

---

## 📜 License

This project is for educational purposes.

---

## 🙌 Author
....

---


