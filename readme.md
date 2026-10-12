# A2SL – Audio and Text to Indian Sign Language Converter

A2SL (Audio and Text to Indian Sign Language) is a Django-based web application that converts **typed or spoken English sentences into Indian Sign Language animations**.

## 🛠️ Technologies Used

* Python
* Django
* NLTK
* SQLite
* HTML
* CSS
* JavaScript
* Web Speech API

## 📋 Prerequisites

Make sure you have the following installed:

* Python 3.x
* pip
* Git

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Anuhya-7/A2SL.git
```

Go into the project folder:

```bash
cd A2SL
```

### 2. Create a Virtual Environment

Create a virtual environment:

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows – Git Bash:**

```bash
source venv/Scripts/activate
```

**Windows – Command Prompt:**

```cmd
venv\Scripts\activate
```

After activation, you should see `(venv)` in your terminal.

### 4. Install the Required Packages

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not included in the repository, install the required packages manually according to the project's dependencies.

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Start the Django Development Server

```bash
python manage.py runserver
```

### 7. Open the Application

Open your browser and go to:

```text
http://127.0.0.1:8000/
```

The A2SL application should now be running.

## 🎤 Features

* Convert typed English text into sign language animations
* Convert spoken English using the Web Speech API
* NLP-based text processing using NLTK
* User login and signup
* Django-based web application
* SQLite database for data storage

## 📁 Project Structure

```text
A2SL/
│
├── A2SL/
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   └── ...
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── signup.html
│   └── animation.html
│
├── manage.py
├── README.md
└── requirements.txt
```

## 👩‍💻 Author

**Anuhya**

B.Sc. (Honors) Computer Science
Osmania University, Hyderabad
