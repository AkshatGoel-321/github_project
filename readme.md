
# 🔧 Installation Guide

Follow the steps below to install and run the project on your local machine.

---

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-project.git
```

---

### 2. Navigate into the project folder

```bash
cd your-project
```

---

### 3. Set up a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

---

### 4. Install the dependencies

```bash
pip install -r requirements.txt
```

---

### 5. Set environment variables

Create a `.env` file and add:

```env
API_KEY=your-api-key-here
DEBUG=True
```

---

### 6. Run database migrations

```bash
python manage.py migrate
```

---

### 7. Start the development server

```bash
python manage.py runserver
```

---

### 8. Open the app in your browser

Go to:
```
http://127.0.0.1:8000
```

---

### 9. (Optional) Create a superuser

```bash
python manage.py createsuperuser
```

---

You're all set! 🚀
