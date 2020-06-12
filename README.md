
# CSTU information system
``` bash
[CSTU_AIS]/
├── [CSTU_AIS]/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
├── [Auth]/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── [Course]/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── [Staff]/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── [Staff]/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── dome.png
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── [Static]/
│   ├── jumbotron
│   ├── course-xlxs-example.png
│   ├── dome.png
│   ├── enrollment-xlxs-example.png
│   ├── gprofile.png
│   ├── pre_req-xlxs-example.png
│   ├── student-xlxs-example.png
│   ├── student.css
│   ├── teacher-xlxs-example.png
│   ├── user-xlxs-example.png
├── [Student]/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── dome.png
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── [Teacher]/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── dome.png
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── [templates]/
│   ├── registration/
│   |   ├── login.html 
│   ├── base.html
│   ├── create_student.html
│   ├── dashboard1_teacher.html
│   ├── dashboard2_teacher.html
│   ├── edit_teacher.html
│   ├── enrollment_upload.html
│   ├── home.html
│   ├── login_ict.html
│   ├── profile_teacher.html
│   ├── staff_course_upload.html
│   ├── staff_create_user.html
│   ├── staff_dashboard1.html
│   ├── staff_dashboard2.html
│   ├── staff_page.html
│   ├── staff_search_student.html
│   ├── staffbase.html
│   ├── student_add_enrollment.html
│   ├── student_ent_score56.html
│   ├── student_ent_score61.html
│   ├── student_page.html
│   ├── student_profile.html
│   ├── student_update.html
│   ├── student_upload.html
│   ├── student_view_enrollment.html
│   ├── studentbase.html
│   ├── teacher_page.html
│   ├── teacher_upload.html
│   ├── teacherbase.html
├── manage.py
```
# Getting started
CSTU Informatioin System work with Python3.
  
To get started with CSTU Informatioin System, run the following in a virtual environment:

``` bash
pip install django
pip install psycopg2
pip install requests
pip install openpyxl
python manage.py migrate
python manage.py runserver
```
Then go to the browser and enter the url http://127.0.0.1:8000/

