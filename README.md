# 🎓 Capstone Thesis Project

A Django-based system with REST API, role-based access, and payment integration.

---

## 📦 Python Packages to Install

Create a `requirements.txt` file and add the following:

```txt
# Core Django
Django==4.2.7

# Django REST Framework
djangorestframework==3.14.0
djangorestframework-simplejwt==5.3.0

# Database
psycopg2-binary==2.9.9

# CORS Headers
django-cors-headers==4.3.1

# Environment Variables
python-decouple==3.8

# Filtering
django-filter==23.5

# HTTP Requests (for PayMongo)
requests==2.31.0

# Image/File Handling
Pillow==10.1.0

# For PDF generation (optional)
reportlab==4.0.4

# For Excel export (optional)
openpyxl==3.1.2
