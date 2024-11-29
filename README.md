# Jewelry E-Commerce Website
## Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
pip install virtualenv
```

Create Virtual Environment

```
python -m venv venv
```

Activate Virtual Environment

```
venv/scripts/activate
```

**3. Install Requirements from 'requirements.txt'**
```python
pip install -r requirements.txt
```

**4. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Add [‘*’]. 
```python
ALLOWED_HOSTS = ['*']
```
*No need to change on Mac.*


**5. Now Run Server**

Command for PC:
```python
python manage.py runserver
```
**6. Login Credentials**

Create Super User (Admin)

```
python manage.py createsuperuser
```