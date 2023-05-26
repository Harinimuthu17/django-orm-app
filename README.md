# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
clone the repository to theia idel.Start a new app inside the project folder

### STEP 2:
Type the appropriate code for your table and provide appropriate data types to the columns

### STEP 3:
create a report about your project in readme.in file and upload the django.orm.app folder to your remote repository


## PROGRAM
```
from django.db import models

# Create your models here.
from django.db import models
from django.contrib import admin

# Create your models here.
class Student (models.Model):
    referencenumber=models.CharField(primary_key=True,max_length=20,help_text="reference number")
    name=models.CharField(max_length=100)
    age=models.IntegerField()
    email=models.EmailField()
    phoneno=models.IntegerField()

class StudentAdmin(admin.ModelAdmin):
    list_display=('referencenumber','name','age','email','phoneno')
```

## OUTPUT


![harini](https://github.com/Harinimuthu17/django-orm-app/assets/130278614/84ee38ab-04f0-41d8-8caa-9481baf5102c)


## RESULT
Hence we develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).
