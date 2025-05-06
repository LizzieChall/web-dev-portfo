# Flask Portfolio Website Template

This is a **portfolio website** built using Python and Flask, designed to be **easily customized** by anyone who wants to showcase their work, projects, or resume online. It includes a working contact form that stores submissions to a `.csv` file, basic routing, and is fully deployable on services like [PythonAnywhere](https://www.pythonanywhere.com/).

> 🌐 Live Demo: [lizzchallenger.pythonanywhere.com](https://lizzchallenger.pythonanywhere.com/)

---

## 🚀 Features

- ✅ Minimal, clean HTML/CSS template (based on [Mashup Template](http://www.mashup-template.com/))
- ✅ Flask-powered backend with dynamic routing
- ✅ Working contact form with data saved to `.csv`
- ✅ Ready-to-deploy on PythonAnywhere or similar hosts
- ✅ Modular and beginner-friendly code

---

## ⚙️ Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/flask-portfolio-template.git
cd flask-portfolio-template
```
---

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python3 -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```
---

### 3. Install Dependencies

 ```bash
pip install flask
```
---

### 4. Run Locally

```bash
python server.py
```
---

## 📬 Contact Form Setup

Form submissions are automatically written to:

database.csv — structured and easy to read.

database.txt — raw backup.

You can customize this behavior in server.py under the write_to_csv() and write_to_file() functions.

---

## 🌐 Deployment (PythonAnywhere)

Create a free account at pythonanywhere.com

Upload your project files

Configure the WSGI file to point to your server.py app

Make sure to install Flask in your virtual environment

---

## 🛠 Customization Tips

Update the content in templates/*.html to match your brand or personal details.

Replace profile images and favicon in the /static/assets/ folder.

Want a blog or project gallery? Just add a new HTML file and route in server.py.

---

### ✨ Credits

Template design: Mashup Template by Orson.io

Hosting: PythonAnywhere
