# 🎓 Workshop Booking System

> This website is for coordinators to book workshop(s). They can book workshops based on instructor posts or propose workshop dates based on their convenience.

---

## Features

### Statistics

#### Instructors Only
- Monthly Workshop Count
- Instructor/Coordinator Profile Stats
- Upcoming Workshops
- View/Post comments on Coordinator Profiles

#### Open to All
- Workshops displayed on Map of India
- Pie chart showing distribution of Workshop Types

---

### Workshop Related Features

- Coordinators can:
  - Book available workshops
  - Propose workshop dates

- Instructors can:
  - Accept / Reject workshop requests
  - Delete workshops
  - Postpone workshops based on coordinator requests

---

## UI/UX Enhancements

- Modern and responsive UI design
- Improved user experience across:
  - Login / Register pages
  - Dashboard
  - Profile page
  - Workshop pages
  - Statistics page
  - Forms (clean and centered layout)
- Consistent color theme and spacing
- Mobile-friendly interface

---

## Tech Stack

- Backend: Django 4.2
- Frontend: HTML, CSS, Bootstrap
- Libraries:
  - django-recurrence
  - pandas
  - python-decouple

---

## Installation

```bash
cd workshop_booking
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver




What design principles guided your improvements?

I followed simplicity, consistency, and usability. The interface was designed using clean layouts, proper spacing, and a consistent color theme to make it easy to understand and visually appealing.

How did you ensure responsiveness across devices?

I used Bootstrap grid system and flexible layouts so that the UI adjusts properly on mobile, tablet, and desktop screens.

What trade-offs did you make between the design and performance?

I avoided heavy animations and large libraries to keep the application fast. I focused on lightweight CSS and minimal JavaScript for better performance.

What was the most challenging part of the task and how did you approach it?

The most challenging part was maintaining consistent UI across all pages. I solved this by using a common design style in the base template and applying it everywhere.