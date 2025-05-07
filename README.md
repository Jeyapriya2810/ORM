# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM



## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
 admin.py

from django.contrib import admin from .models import Employee,EmployeeAdmin admin.site.register(Employee,EmployeeAdmin)

modles.py

from django.db import models from django.contrib import admin class Employee (models.Model): eid=models.CharField(max_length=20,help_text="Employee") name=models.CharField(max_length=100) salary=models.IntegerField() age=models.IntegerField() email=models.EmailField()

class EmployeeAdmin(admin.ModelAdmin): list_display=('eid','name','salary','age','email') 
```


## OUTPUT
![Screenshot 2025-05-07 112355](https://github.com/user-attachments/assets/4c38d9e3-5926-407f-9449-2f7408553741)



## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
