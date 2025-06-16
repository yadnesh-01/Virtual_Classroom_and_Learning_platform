# 🧑‍🏫 AWS-hosted Virtual Classroom and Learning Platform

### Cloud-Native Education Portal Built with Flask & AWS

---

## 📌 Project Description

In the evolving landscape of digital education, creating an efficient, scalable, and secure virtual learning environment is essential. The **AWS-hosted Virtual Classroom and Learning Platform** project addresses this need by developing a cloud-native platform that integrates key AWS services to deliver a seamless educational experience.

The platform leverages **Flask** for backend development and is hosted on **AWS EC2**, ensuring customizable and scalable deployment. **Amazon S3** is used for storing course content and data, while **Amazon RDS (MySQL)** is employed for managing user registration, login data, and other relevant information.

---

## 🖼 Output Screenshots

### Homepage
![Homepage](https://drive.google.com/uc?export=view&id=1M66NdBFaUQpdWlF2EBYr5av4AfFGPBaM)

### Login Page
![Login](https://drive.google.com/uc?export=view&id=1coTZ9tva_uPiD7HRM5uLY8nqYRUFhczP)

### Register Page
![Register](https://drive.google.com/uc?export=view&id=1BXvlK4uMbcFVJbLHWVsQNJTkD87_zUGn)

---

## 🛠 *Technologies Used*

- **Python 3.10+**
- **Flask** – Backend Web Framework
- **HTML / CSS / Bootstrap** – Frontend UI
- **AWS EC2** – Hosting Flask App
- **AWS S3** – File storage (courses & content)
- **AWS RDS (MySQL)** – Database for login and user data
- **boto3** – AWS SDK for Python
- **pymysql** – MySQL DB connector
- **werkzeug.security** – Password hashing
- **Session & Flash (Flask)** – User authentication and messaging

---

## 📁 *Project Directory Structure*

```bash
AWS-HOSTED-VIRTUAL-CLASSROOM/
├── aws_env/                             # Python virtual environment
├── static/                              # Static CSS, JS, or images
├── templates/                           # Flask HTML templates
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   └── content.html
├── app.py                               # Flask application entry point
├── Final report.pdf                     # Documentation
└── requirements.txt                     # Project dependencies
```

---

## ⚙ *Installation & Setup*

### Using Conda (Recommended)

```bash
conda create -n cyber_ids python=3.10
conda activate cyber_ids
cd CYBER_PROJECT
pip install -r requirment.txt
```

### Using Python venv

```bash
python -m venv aws_env

# Windows:
aws_env\Scripts\activate

# macOS/Linux:
source aws_env/bin/activate

pip install -r requirements.txt

```
---

## *Running the Application*

```bash
python app.py

```

Open your browser and go to:  
  [http://127.0.0.1:5000/]

---


## *Conclusion*

This project demonstrates how cloud-native architectures can transform traditional education platforms. By integrating AWS EC2, S3, and RDS with Flask, this solution provides a scalable, secure, and user-friendly virtual classroom experience.

```
```
## 📚 *References*

AWS EC2 Setup: https://www.youtube.com/results?search_query=aws+ec2+oneshot

Flask Integration: https://www.youtube.com/results?search_query=flask+tutorial

AWS RDS: https://www.youtube.com/results?search_query=rds+oneshot

S3 Bucket: https://www.youtube.com/results?search_query=s3+bucket+setup

GitHub Deployment: https://www.youtube.com/results?search_query=clone+github+repository 

```
