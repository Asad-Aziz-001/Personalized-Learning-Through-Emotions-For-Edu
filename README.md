
# 📘 **Sentellect — Personalized Learning for Education**

Sentellect is a **personalized learning platform** designed for **HSSC Part 2 students**.
It uses **machine learning (joblib model)** and a **Flask + HTML** framework to provide
customized learning recommendations and user-specific insights.

The project includes a backend model, a structured Flask environment,
and a database instance containing user records.

# **Demo Link**

<p align="center">
  <a href="https://your-sentellect-app.up.railway.app/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo_–_Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white&labelColor=0B0D0E&color=0B0D0E&borderWidth=2&borderColor=4A90E2" alt="Live Demo on Railway" style="height: 65px; border-radius: 12px; cursor: pointer; transition: all 0.3s ease; box-shadow: 0 4px 8px rgba(0,0,0,0.3);" onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 6px 12px rgba(0,0,0,0.4)'" onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 4px 8px rgba(0,0,0,0.3)'">
  </a>
</p>


---

## 🚀 **Features**

* 🎓 Personalized study recommendations
* 🤖 Machine Learning model integrated using `.joblib`
* 🌐 Flask backend with clean HTML templates
* 👤 User database stored inside the `instances/` folder
* 📊 Dynamic content based on user inputs
* 🖥 Simple and lightweight interface for student usage

---

## 🧱 **Project Structure**

```
sentellect/
├── app.py
├── templates/
├── model.joblib
├── requirements.txt
├── instances/
│   ├── database.sqlite3 (example)
│   └── user_records/
```

---

## 🔧 **Installation Instructions**

Follow these steps to set up and run the project.

---

### **1️⃣ Clone the Repository**

```
git clone https://github.com/your-username/sentellect.git
cd sentellect
```

---

### **2️⃣ Create Virtual Environment**

```
python -m venv venv
```

Activate it:

#### **Windows**

```
venv\Scripts\activate
```

#### **PowerShell**

```
venv\Scripts\Activate.ps1
```

---

### **3️⃣ Install Dependencies**

Install all required packages:

```
pip install -r requirements.txt
```

---

### **4️⃣ Run Django Server**

Since your project includes `app.py`, run:

```
python app.py
```



## 🤖 **Machine Learning Model**

The project uses a `.joblib` ML model located at:

```
model.joblib
```

 Google Drive link here:

**Model Download:**
https://drive.google.com/file/d/1JqUMN4wUUzcHNXjbS4sl4cakNZ_dy6DP/view?usp=sharing

---

## 🗄️ **Database (instances folder)**

The `instances/` directory contains your user database and other stored files.

This allows:

* saving user details
* tracking progress
* storing personalized recommendations

Make sure **NOT** to delete this folder.

---

## 📄 **License**

This project is for educational and academic use.

---

## 🤝 **Contributing**

Pull requests and suggestions are welcome.


Just tell me!

