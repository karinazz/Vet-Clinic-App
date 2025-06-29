# 🐾 Vet Clinic App – Fullstack Web Application for Veterinary Clinic Management

**Vet Clinic App** is a full-featured web application built from scratch as a Fullstack Developer project.  
It helps veterinary clinics manage animal records, employee schedules, services, and appointment bookings — all in one place.

---

## 🔧 Technologies Used

- **Backend:** Python, Django, Django ORM  
- **Database:** PostgreSQL  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap (CDN Icons)  
- **Rich Text Editor:** CKEditor5  
- **Image Processing:** Pillow  
- **APIs:** RandomUserGeneratorAPI for sample data  
- **Graphics:** GIMP  

---

## ✨ Features

### 🐕 Animal and Client Management
- Register and manage animal records  
- View animal details with images  

### 👩‍⚕️ Employee and Schedule Management
- Add/edit employee data  
- Manage and display work schedules  

### 🛠 Services and Appointments
- List and categorize veterinary services  
- Book and manage appointments through an interactive form  

### 📝 Blog and Content Management
- Create and edit blog posts with CKEditor5 rich text editor  
- Manage content easily through Django admin  

---

## 🗂 App Structure

| Folder / App       | Description                                   |
|-------------------|-----------------------------------------------|
| `app/`            | Main Django app with models, views, forms, templates, static files |
| `media/`          | Uploaded user files and animal photos          |
| `mysite/`         | Project configuration (settings, URLs, WSGI)  |
| `requirements.txt`| Python dependencies                            |
| `manage.py`       | Django management script                       |

---

## 📸 Screenshots

| View                      | Screenshot Path                    |
|---------------------------|----------------------------------|
| Homepage                  | ![](screenshots/homepage.png)       |
| Employee List             | ![](screenshots/employees.png)       |
| Services Overview         | ![](screenshots/services.png)        |
| Work Schedule             | ![](screenshots/schedule.png)        |
| Animal Database           | ![](screenshots/animals.png)         |
| Appointment Booking Form  | ![](screenshots/reservation_form.png)|
| Admin Panel               | ![](screenshots/admin_panel.png)     |

---

## 🚀 How to run?

Follow these steps to run the project locally:

```bash
# Clone the repository
git clone https://github.com/karinazz/Vet-Clinic-App.git
cd Vet-Clinic-App

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure PostgreSQL database in mysite/settings.py
# Example:
# DATABASES = {
#     'default': {
#         'ENGINE': 'django.db.backends.postgresql',
#         'NAME': 'your_db_name',
#         'USER': 'your_username',
#         'PASSWORD': 'your_password',
#         'HOST': 'localhost',
#         'PORT': '5432',
#     }
# }

# Apply migrations
python manage.py migrate

# Create superuser for admin access
python manage.py createsuperuser

# Run development server
python manage.py runserver
