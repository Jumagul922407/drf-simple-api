DRF Simple API

Бул Django REST Framework (DRF) негизинде жасалган жөнөкөй API долбоору.

🔧 Колдонулган технологиялар:

- Python 3
- Django
- Django REST Framework

---

📁 Түзүм:


drf-simple-api/
├── drf_api/          # Негизги Django проект
│   └── urls.py       # Жалпы URL'дер
├── api/              # API колдонмосу
│   ├── views.py      # API логикасы
│   ├── urls.py       # API URL'дери
├── manage.py         # Башкаруу скрипти


---

📌 API'нин мүмкүнчүлүгү:

- GET /api/hello/ – "Hello, World!" деген JSON жооп берет.

---

🚀 Иштетүү үчүн:

1. Виртуалдык чөйрөнү түз:
   bash
   python -m venv venv
   source venv/bin/activate  # же Windows'то: venv\Scripts\activate
   

2. Талаптарды орнот:
   bash
   pip install django djangorestframework
   

3. Серверди иштет:
   bash
   python manage.py runserver
   

4. Браузерге кир:
   
   http://127.0.0.1:8000/api/hello/
   

