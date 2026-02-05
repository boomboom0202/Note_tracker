# Note_tracker

Note_tracker is a Django-based web application for managing and tracking notes.

## 🚀 Getting Started

Follow the steps below to set up and run the project locally.

### 1️⃣ Clone the repository

```bash
git clone <repository_url>
cd Note_tracker
```

### 2️⃣ Create a virtual environment

```bash
python -m venv env
```

### 3️⃣ Activate the virtual environment

* **Windows:**

  ```bash
  env\Scripts\activate
  ```

* **Linux / macOS:**

  ```bash
  source env/bin/activate
  ```

### 4️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Apply database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Create a superuser

```bash
python manage.py createsuperuser
```

Follow the prompts to set up admin credentials.

### 7️⃣ Run the development server

```bash
python manage.py runserver
```

The project will be available at:

```
http://127.0.0.1:8000/
```

## 🔐 Admin Panel

You can access the Django admin panel at:

```
http://127.0.0.1:8000/admin/
```

Log in using the superuser credentials you created earlier.

## 🛠 Tech Stack

* Python
* Django
* SQLite (default)

## 📌 Notes

* Make sure you are using **Python 3.x**
* Always activate the virtual environment before running the project

---

Happy c
