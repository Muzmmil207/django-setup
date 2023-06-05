GETTING STARTED
---

1. Create a virtual environment
    `virtualenv venv`
    Or
    `python3.8 -m venv venv`

2. Activate it
    `source venv/bin/activate`

3. Install requirements
  pip install -r requirements.txt
 
4. Runserver on port 8000

    python manage.py runserver
    
    http://127.0.0.1:8000/
    
5. Create superuser
    python manage.py createsuperuser
    
---
The Project Tree
---
```
C:.
├───apps
│   └───<your apps goes here>   
├───core
│   └───settings
├───media
│   └───images
├───static
│   ├───css
│   ├───image
│   └───js
├───templates
│   └───apps
└───utils
```