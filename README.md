# golang-cart
GooCart is a high-performance e-commerce platform backend written in Go language. It is designed to handle a large number of requests and transactions efficiently, making it ideal for large-scale e-commerce operations!
# Table of Contents
Introduction
Full-stack Applications
E-commerce (shopping cart)
Server side implementations
Client side implementations
Blog/CMS
Server side implementations
Client side
The next come are
Simple CRUD(Create, Read, Update, Delete)
Server side implementations
Client side implementations
The next come are
CRUD + Pagination
Server side implementations
The next come are
Client side implementations
The next come are
Follow me
Introduction
This is one of my E-commerce API app implementations. It is written in Golang using go-gonic web framework.. This is not a finished project by any means, but it has a valid enough shape to be git cloned and studied if you are interested in this topic. If you are interested in this project take a look at my other server API implementations I have made with:

Full-stack Applications
E-commerce (shopping cart)
Server side implementations
Spring Boot + Spring Data Hibernate
Spring Boot + JAX-RS Jersey + Spring Data Hibernate
Node Js + Sequelize
Node Js + Bookshelf
Node Js + Mongoose
Python Django
Flask
Golang go gonic
Ruby on Rails
AspNet Core
Laravel
The next to come are:

Spring Boot + Spring Data Hibernate + Kotlin
Spring Boot + Jax-RS Jersey + Hibernate + Kotlin
Spring Boot + mybatis
Spring Boot + mybatis + Kotlin
Asp.Net Web Api v2
Elixir
Golang + Beego
Golang + Iris
Golang + Echo
Golang + Mux
Golang + Revel
Golang + Kit
Flask + Flask-Restful
AspNetCore + NHibernate
AspNetCore + Dapper
Client side implementations
This client side E-commerce application is also implemented using other client side technologies:

React Redux
React
Vue
Vue + Vuex
Angular
Blog/CMS
Server side implementations
Spring Boot + Spring Data Hibernate
Go + Gin Gonic
NodeJs + Mongoose
Laravel
Ruby on Rails + JBuilder
Django + Rest-Framework
Asp.Net Core
Flask + Flask-SQLAlchemy
The next to come are:

Spring Boot + Spring Data Hibernate + Kotlin
Spring Boot + Jax-RS Jersey + Hibernate + Kotlin
Spring Boot + mybatis
Spring Boot + mybatis + Kotlin
Asp.Net Web Api v2
Elixir
Golang + Beego
Golang + Iris
Golang + Echo
Golang + Mux
Golang + Revel
Golang + Kit
Flask + Flask-Restful
AspNetCore + NHibernate
AspNetCore + Dapper
Client side
Vue + Vuex
Vue
React + Redux
React
Angular
The next come are

Angular NgRx-Store
Angular + Material
React + Material
React + Redux + Material
Vue + Material
Vue + Vuex + Material
Ember
Simple CRUD(Create, Read, Update, Delete)
Server side implementations
Spring Boot + Spring Data Hibernate
Spring boot + Spring Data Reactive Mongo
Spring Boot + Spring Data Hibernate + Jersey
NodeJs Express + Mongoose
Nodejs Express + Bookshelf
Nodejs Express + Sequelize
Go + Gin-Gonic + Gorm
Ruby On Rails
Ruby On Rails + JBuilder
Laravel
AspNet Core
AspNet Web Api 2
Python + Flask
Python + Django
Python + Django + Rest Framework
Client side implementations
VueJs
The next come are
Angular NgRx-Store
Angular + Material
React + Material
React + Redux + Material
Vue + Material
Vue + Vuex + Material
Ember
Vanilla javascript
CRUD + Pagination
Server side implementations
Spring Boot + Spring Data + Jersey
Spring Boot + Spring Data
Spring Boot Reactive + Spring Data Reactive
Go with Gin Gonic
Laravel
Rails + JBuilder
Rails
NodeJs Express + Sequelize
NodeJs Express + Bookshelf
NodeJs Express + Mongoose
Python Django
Python Django + Rest Framework
Python Flask
AspNet Core
AspNet Web Api 2
The next come are
NodeJs Express + Knex
Flask + Flask-Restful
Laravel + Fractal
Laravel + ApiResources
Go with Mux
AspNet Web Api 2
Jersey
Elixir
Client side implementations
Angular
React-Redux
React
Vue + Vuex
Vue
The next come are
Angular NgRx-Store
Angular + Material
React + Material
React + Redux + Material
Vue + Material
Vue + Vuex + Material
Ember
Vanilla javascript
Social media links
Youtube Channel I publish videos mainly on programming
Blog Sometimes I publish the source code there before Github
Twitter I share tips on programming
WARNING
I have mass of projects to deal with so I make some copy/paste around, if something I say is missing or is wrong, then I apologize and you may let me know opening an issue.

Getting started
go get https://github.com/melardev/ApiEcomGoGonic
Change the .env.example as you need(see warning below)
Rename .env.example to .env
Seed the database passing "create seed" as arguments to the app(read main.go to understand what I mean)
WARNING
The recommended database to use is Postgresql, the other database backends may not work as expected. Unfortunately the MySQL does not work as expected, for example the BeforeSave Hook for User is not able to retrieve the Role model if using MySQL, the same code does work if SQLite, it is weird, because the SQL query generated is valid and it returns a row, but somehow the driver is not able to map it to the user.

Features
Authentication / Authorization
JWT middleware for authentication
Multi file upload
Database seed
Paging with Limit and Offset using GORM (Golang ORM framework)
CRUD operations on products, comments, tags, categories, orders
