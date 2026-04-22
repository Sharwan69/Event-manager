# 🎓 EduEvents – School Event Management System

EduEvents is a **full-stack school event management website** designed to manage and showcase school events in a modern and user-friendly way.

This project includes:

* **Admin Dashboard** → for event management and participant CRUD
* **Public User Portal** → for students/visitors to browse and register for events
* **Backend API** → built with Node.js, Express, and MongoDB

---

## ✨ Features

### 👨‍💼 Admin Panel

The admin side allows complete event and participant management.

#### Event CRUD

* ➕ Create new events
* ✏️ Update event details
* ❌ Delete events
* 👀 View all events
* 🔍 Search and filter events
* 📅 Filter by date range
* 🖼️ Upload event banner preview

#### Participant Management

* ➕ Register participants
* ✏️ Edit participant details
* ❌ Remove participants
* 📋 View participants table
* 📊 Track total registrations

#### Dashboard

* 📈 Total events
* ⏳ Upcoming events
* 👨‍🎓 Registered students
* ✅ Completed events

---

## 🌐 User Portal

This is the public-facing website for students and visitors.

### Main Features

* 🏠 Hero landing page
* 📢 Live event ticker
* 🔍 Search and filter events
* 🗓️ Event cards with banners
* 📋 Detailed event modal
* ✍️ Event registration form
* 📊 Seat availability and progress bar
* 📱 Fully responsive design

Students can:

* browse upcoming events
* check event details
* register online
* view seats remaining

---

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Express.js
* MongoDB

### Storage

* localStorage (frontend demo mode)
* MongoDB (backend mode)

---

## 📂 Project Structure

```text
EduEvents/
│
├── EduEvents-Frontend.html
├── EduEvents-UserPortal.html
│
├── school-events/
│   ├── index.html
│   ├── server.js
│   ├── package.json
│   └── README.md
```

---

## 🚀 How to Run

### Frontend Only

Simply open:

```text
EduEvents-Frontend.html
```

and

```text
EduEvents-UserPortal.html
```

in your browser.

No server required.

---

## ⚙️ Backend Setup

Go to backend folder:

```bash
cd school-events
```

Install dependencies:

```bash
npm install
```

Run server:

```bash
npm start
```

Server runs at:

```text
http://localhost:5000
```

---

## 🔗 API Endpoints

### Events

* `GET /api/events`
* `POST /api/events`
* `PUT /api/events/:id`
* `DELETE /api/events/:id`

### Participants

* `GET /api/participants`
* `POST /api/participants`
* `PUT /api/participants/:id`
* `DELETE /api/participants/:id`

### Stats

* `GET /api/stats`

---

## 🎯 Project Objective

The objective of this project is to provide a centralized platform for schools to:

* manage events efficiently
* increase student participation
* simplify registration
* improve event visibility

---

## 📸 Screens Included

* Admin dashboard
* Event management page
* Student registration
* Public event portal

---

## 👨‍💻 Developed By

**Sharwan**
