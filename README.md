# ABSTARCT
This project is designed by taking Amazon Prime-like websites as a base. In Amazon Prime User will be subscribed with some amount for some fixed duration, with that amount the user can access the videos like web series, movies etc. But if the user didn’t watch during that duration then his subscription amount will be wasted and after that duration he can’t watch any videos, so again the user should subscribe with some amount to continue to watch. 

# REQUIREMENT ANALYSIS:
* Basic understanding of the web site (Working, How to use..Etc)
* A customer can purchase a movie and get a life time access.
* Customer can get offer based on usage.
* Movie can be accessed from multiple devices simultaneously up to 10 devices.

# MODULE DESCRIPTION:
In this project we used the following modules
* **Website Module:** 
It contains Customer, Admin, Purchase_C ,Releases , Movies are some of the entities.
* **Payment Module:**
It Includes Purchase, Purchase_C  Entities.

# LIST OF ENTITIES USED :
* ADMIN
* LIST OF MOVIES
* COMEDY 
* HORROR
* FICTION
* DISTRIBUTOR
* CUSTOMER
* MOVIES

# LIST OF RELATIONSHIPS USED :
* **COLLECT** (Admin collect reviews from list of movies released ) :
  It has many to many relationships.
* **PURCHASE**(Admin  purchase  movies from distributor) :
 It has one to many relationship.
* **Releases** (Admin Releases purchased movies into web site):
It has one to many relationship 
* **PURCHASE_CUSTOMER**(Customer purchases movies from web site):
 It is a one to many relationship.

# ER Model 
![1](https://user-images.githubusercontent.com/53647653/180639322-e2a9cf9c-9bcd-4749-aa8e-81894be05908.png)
