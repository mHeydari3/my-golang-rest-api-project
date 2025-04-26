# Project: REST API
## _Building a REST API with Go_

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

A webserver that serves data, receives data, stores data.


- Planning the project
- Building the REST API step by step
- ✨Magic ✨

---



## 📘 Project Description

**A Go-powered “Event Booking” REST API**

---

## 🧩 API Endpoints

| Description                    | Endpoint                     | Method |
|-------------------------------|------------------------------|--------|
| Get a list of available events| `/events/`                   | GET    |
| Get a list of available events| `/events/<id>`               | GET    |
| Create a new bookable event   | `/events/`                   | POST   |
| Update an event               | `/events/<id>`               | PUT    |
| Delete an event               | `/events/<id>`               | DELETE |
| Create new user               | `/signup/`                   | POST   |
| Authenticate user             | `/login/`                    | POST   |
| Register user for event       | `/events/<id>/register/`     | POST   |
| Cancel registration           | `/events/<id>/register/`     | DELETE |
