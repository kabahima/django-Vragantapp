# django_resfulapp_WithvragantMongodb
Django app developed with vagrant and mongo db as the database it is fully a backend project with endpoints

### What is Vargant
Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past.

Vagrant will isolate dependencies and their configuration within a single disposable, consistent environment, without sacrificing any of the tools you are used to working with (editors, browsers, debuggers, etc.)

#### mongodb and Django
MongoDB provides open-sourced database software. This is very helpful to early-stage startups looking to launch while being constrained by tight budgets. A review of Google search trends for MongoDB revealed a steady increase in interest.

But MongoDB goes around calling itself a “non-relational” database system, and has been making tall claims about its approach to store data. So, what exactly is the BIG deal here?

SQL had become the de-facto language for working with any database (DB) software, proprietary or open source. Then MongoDB came along and decided to show utter disregard to this ancient language of power and introduced query syntax of its own.

 In this project i choose to use mongodb but suprisingly its so simple to setup in Django with only one line of Code and you are good to go

 ```
 DATABASES = 
    {   
        ‘default’: { 
            ‘ENGINE’: ‘djongo’,
            ‘NAME’: ‘your-db-name’, 
        }
    }
 ```
 for you to achive this all need is to install
 ```
 pip install Djongo
 ```
 then 

 ``` 
 makemigrations 
```
and also 
```
migrate
```

that so simple and its only done once

for more info find out here  [Djongo](https://www.djongomapper.com/)

