index.html
{% load static %}
<html>
    <head>
        <link rel="stylesheet"href="/Users/user/Downloads/bootstrap-4.0.0-dist">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <link rel="stylesheet" type="text/css" href=" {% static 'css/index.css' %} ">
  <a class="navbar-brand" href="index"><font style="color:maroon"><b>TAU VISION</b></font></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="home"><font style="color:maroon">Home</font></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="about"><font style="color:maroon">About Us</font></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="contact"><font style="color:maroon">Contact Us</font></a>
      </li>
    </ul>
  </div>
</nav>
</head>
  <style> 
  body{
    margin-top: 20px;
    background-color:white;
    background-size:contain; 
    background-repeat:no-repeat;
    background-position:center center;
    padding:50 px;
    margin-left:100 px;
    height: 50 px;
    }   
  </style>
  <body>
    <video loop autoplay muted id="myvideo">
      <source src="{%static 'video/taulogopromonew.mp4'%}" type="video/mp4">
    </video>
   
    </body>
</html>
home.html
{% load static %}
<html>
    <head>
        <link rel="stylesheet"href="/Users/user/Downloads/bootstrap-4.0.0-dist">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="index"><font style="color:maroon"><b>TAU VISION</b></font></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="home"><font style="color:maroon">Home</font></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about"><font style="color:maroon">About Us</font></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact"><font style="color:maroon">Contact Us</font></a>
        </li>
      </ul>
    </div>
  </nav>
        
    </head>
    <style>
     body{
    display: flex;
    flex-direction: column;
    background-image: url({% static 'image/logonew.png'%});
    background-color:white;
    background-size:contain; 
    background-repeat:no-repeat;
    background-position:center center;
    padding:50 px;
    height: 50 px;
     }
        £ wrapper-div
        {
            display:flex;
            flex-direction:column;
            width:60%;
            min-height:100px;
            margin: auto;
        }
        .row{
            display: flex;
            flex-direction: row;
            width: 100%;
            min-height: 200px;
            margin-top: 10px;
            justify-content: space-between;
        }
        .col
        {
            display: flex;
            flex-direction: row;
            flex-basis: 20%;
        }
        
    </style>
    <body>
        
        <h1 style="font-size: xx-large;"><center><B><font style="color:maroon">OUR PROGRAMMES</font></B></center>
            <br>
            <br>
            <br>
        <div id="wrapper-div">
        </div>
        <div class="row">
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/ExjTRkLYAco" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/Cr754rQVEaQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/DRT2gp84e2M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </div>
        <div class="row">
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/ZUJ9dWsbLU0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/L3-MJWtfBUg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/-Ak7O4Lnn5I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </div>
        <div class="row">
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/p6njwqdwQO4?start=2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/sl4x5N_zbOI?start=2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <div class="col">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/uGfwLDp6PgM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </div>
    </body>
    
</html>
  about.html
  {%load static %}
<html>
    <head>
    <link rel="stylesheet"href="/Users/user/Downloads/bootstrap-4.0.0-dist">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
   
    <link rel="stylesheet"href="about.css">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="index"><font style="color:maroon"><b>TAU VISION</b></font></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="home"><font style="color:maroon">Home</font></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about"><font style="color:maroon">About Us</font></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact"><font style="color:maroon">Contact Us</font></a>
          </li>
        </ul>
      </div>
    </nav>
  </head>
    <style>
     body{
          background-image: url({% static 'image/logonew.png'%});
           background-color:white;
           background-size:contain; 
           background-repeat:no-repeat;
           background-position:center center;
           padding:50 px;
           height: 50 px;
           }   
</style>
<body><center><h1 style="color:maroon"><u><font size="10">ABOUT US </font></h1></u></center><br>
    <br>
        <h1><center><u><b><font size="6">OUR VISION</font></center></b></u></h1>
        <p><center><font size="5">To inspire and sustain the day-to-day life in love, happiness and peace.</center></font></p>
        <br>
        <br>
        <h1><center><u><b><font size="6">OUR MISSION</u></b></font></center></h1>
        <P><center><font size="5">•To infuse the minds with the word of god,
            <br>
            <br>
            •Journey along ups and downs, 
<br>
<br>
•	Motivating and strengthening,
<br>
<br>
•	Offering varieties of single platform that are unique, 
<br>
<br>
•	Innovative and transforming,
<br>
<br>
•	Touching the world but not “worldly”.</font></center> </P>
    </body>
</html>
  contact.html
  {% load static %}
<html>
<head>
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
   <link rel="stylesheet"href="/Users/user/Downloads/bootstrap-4.0.0-dist">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
   <link rel="stylesheet" type="text/css" href=" {% static 'css/contact.css' %} ">
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="index"><font style="color:maroon"><b>TAU VISION</b></font></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="home"><font style="color:maroon">Home</font></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about"><font style="color:maroon">About Us</font></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact"><font style="color:maroon">Contact Us</font></a>
        </li>
      </ul>
    </div>
  </nav>
   <style>
         body{
           background-image: url({% static 'image/logonew.png' %});
           background-color:white;
           background-size:contain; 
           background-repeat:no-repeat;
           background-position:center center;
           padding:50 px;
           margin-left:0 px;
           height: 50 px;
           }   
        </style>
</head>
<body> 
  <br>
  <br>
  <br>
  <h1 style="color:maroon"><u><center>Connect With Us</center></u></h1>
  <br>
  <br>
  <center>
    <p style="position: relative;">
        Leave your message and we'll get back to you shortly.
        </p>
    </center>
    <br>
    <br>
    <br>
    <section id="contact">
  
        
        <div class="contact-wrapper">
        
        <!-- Left contact page --> 
          
        <form id="contact-form" class="form-vertical" role="form">

             
            <div class="form-group">
              <div class="col-sm-12">
                <label>Your Name</label>
                <input type="text" placeholder="your name" name="name" value="" required>
              </div>
            </div>
            <br>
            <div class="form-group">
              <div class="col-sm-12">
                <label>Email id</label>
                <input type="email" placeholder="your email address" name="email" value="" required>
              </div>
            </div>
            <br>
            <textarea rows="10" cols="50" placeholder="Write something here..."value=""required></textarea>
     </textarea>
            <button class="btn btn-primary send-button" id="submit" type="submit" value="SEND">
              <div class="alt-send-button">
                <i class="fa fa-paper-plane"></i><span class="send-text">SEND</span>
              </div>
            
            </button>
            
          </form>
          
        <!-- Left contact page --> 
          
            <div class="direct-contact-container">
      
              <ul class="contact-list">
                <li class="list-item"><i class="fa fa-map-marker fa-2x"style="color:black"><span class="contact-text place"><b><p align="center"><font style="color:maroon">Tau vision,Gagultha Retreat Centre,Kurumal,PO Thalakkottukkara</font></p></b></span></i></li>
                
                <li class="list-item"><i class="fa fa-phone fa-2x"style="color:black"><span class="contact-text phone"><a href="tel:+91 6238599788" title="Give me a call"><b>6238599788</a></span></i></li>
                
                <li class="list-item"><i class="fa fa-envelope fa-2x"style="color:black"><span class="contact-text gmail"><a href="mailto:#" title="Send me an email"><b>tauvisionwebtv@gmail.com</b></a></span></i></li>  

              <li class="list-item"><i class="fa fa-facebook fa-2x" style="color:blue"><span class="facebook"title="Hi"><b><font size="5px">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp tauvision</font></b></span></i></li>
                
              <li class="list-item"><i class="fa fa-whatsapp fa-2x" style="color:green"><span class="whatsapp"><b><font size="5px">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 6238599788</font></b></a></span></i></li>
                
              <li class="list-item"><i class="fa fa-instagram fa-2x" style="color:maroon"><span class="insta"><b><font size="5px">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp tauvision</font></b></a></span></i></li>  
            </div>
          </section>
          <footer class="footer">
            <div class="footerContainer">
                <p class="copyright"><center><b>© All rights are reserved</b></p></center></p>
            </div>
          </footer>          
</html>
tauvision urls.py
from django.contrib import admin
from django.urls import path,include

urlpatterns = [
    path('admin/', admin.site.urls),
    path('',include('tau.urls')),
]
tau urls.py
from django.urls import path
from . import views

urlpatterns=[
path('index',views.index),
path('home',views.home),
path('about',views.about),
path('contact',views.contact),
]
views.py
from django.shortcuts import render
# Create your views here.
from django.http import HttpResponse
from . models import contact_table

def index(request):
    return render (request,"index.html")
def home(request):
    return render(request,"home.html")
def about(request):
    return render(request,"about.html")
def contact(request):
    if request.method=='POST':
        nam=request.post.get['name']
        ema=request.post.get['email']
        sgs=request.POST.get['suggestions']
        Contact=contact.object.create(name=nam,email=ema,suggestions=sgs)
        sgs.success(request,'we will improve it!Thank you')
        Contact.save()
        return render(request,"contact.html")
    else:
        return render(request,"contact.html")


models.py
from django.db import models

# Create your models here.
class contact_table(models.Model):
    name=models.CharField(max_length=20)
    email=models.EmailField()
    suggestions=models.TextField(max_length=150)
   admin.py
   from django.contrib import admin

# Register your models here.
from.models import contact_table
admin.site.register(contact_table)
settings.py
from pathlib import Path
import os

# Build paths inside the project like this: BASE_DIR / 'subdir'.
BASE_DIR = Path(__file__).resolve().parent.parent


# Quick-start development settings - unsuitable for production
# See https://docs.djangoproject.com/en/4.1/howto/deployment/checklist/

# SECURITY WARNING: keep the secret key used in production secret!
SECRET_KEY = 'django-insecure-t_0s0(=85*am44@w^v3e8uw&#a$+*xod(5rsq3g#_g%c^&!87g'

# SECURITY WARNING: don't run with debug turned on in production!
DEBUG = True

ALLOWED_HOSTS = []


# Application definition

INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'tau',
]

MIDDLEWARE = [
    'django.middleware.security.SecurityMiddleware',
    'django.contrib.sessions.middleware.SessionMiddleware',
    'django.middleware.common.CommonMiddleware',
    'django.middleware.csrf.CsrfViewMiddleware',
    'django.contrib.auth.middleware.AuthenticationMiddleware',
    'django.contrib.messages.middleware.MessageMiddleware',
    'django.middleware.clickjacking.XFrameOptionsMiddleware',
]

ROOT_URLCONF = 'Tauvision.urls'

TEMPLATES = [
    {
        'BACKEND': 'django.template.backends.django.DjangoTemplates',
        'DIRS': [os.path.join(BASE_DIR,'template')],
        'APP_DIRS': True,
        'OPTIONS': {
            'context_processors': [
                'django.template.context_processors.debug',
                'django.template.context_processors.request',
                'django.contrib.auth.context_processors.auth',
                'django.contrib.messages.context_processors.messages',
            ],
        },
    },
]

WSGI_APPLICATION = 'Tauvision.wsgi.application'


# Database
# https://docs.djangoproject.com/en/4.1/ref/settings/#databases

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / 'db.sqlite3',
    }
}


# Password validation
# https://docs.djangoproject.com/en/4.1/ref/settings/#auth-password-validators

AUTH_PASSWORD_VALIDATORS = [
    {
        'NAME': 'django.contrib.auth.password_validation.UserAttributeSimilarityValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.MinimumLengthValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.CommonPasswordValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.NumericPasswordValidator',
    },
]


# Internationalization
# https://docs.djangoproject.com/en/4.1/topics/i18n/

LANGUAGE_CODE = 'en-us'

TIME_ZONE = 'UTC'

USE_I18N = True

USE_TZ = True


# Static files (CSS, JavaScript, Images)
# https://docs.djangoproject.com/en/4.1/howto/static-files/

STATIC_URL = 'static/'
STATICFILES_DIRS =(os.path.join(BASE_DIR,'static')),

# Default primary key field type
# https://docs.djangoproject.com/en/4.1/ref/settings/#default-auto-field

DEFAULT_AUTO_FIELD = 'django.db.models.BigAutoField'
