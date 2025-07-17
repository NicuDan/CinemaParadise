# 🎬 Cinema Paradise

Welcome to **Cinema Paradise** – a modern and interactive cinema website where users can explore movies currently running, view trailers, book seats, and purchase tickets. Admins can also access a full dashboard with detailed business insights.

---

## 🏠 Homepage Overview

The main page includes:

- 🎞️ **Movies Listing** – See all movies currently in theaters.
- 🔍 **Filters** – Filter movies by:
  - Genre
  - Name
- 📊 **Sorting System** – Sort movies by:
  - Name
  - Duration
  - Rating
- 📍 **Cinema Location Display** – Shows where each movie is playing.

<img width="1904" height="923" alt="image" src="https://github.com/user-attachments/assets/635635e3-6e0c-45e3-8a5f-9cd73ab3f270" />


---

## 🔐 Authentication

The site features:

- 🧑‍💻 **Login/Register System**
  - Two types of users: **User** and **Admin**
  - Secure authentication flow



---

## 🛠️ Admin Dashboard

Admins have access to a custom dashboard showing:

- 💰 Total movie revenue
- 📈 Profits & insights
- 🎟️ Ticket sales breakdown



---

## 🎥 Movie Details Page

When clicking on a movie from the list, users are taken to a detailed movie page which includes:

- 🎞️ **Trailer**
- 🕒 **Airing Times & Locations**
- ⭐ **Rating**
- 📝 **Title & Description**
- 🧑‍🏫 **User Reviews** – View and add ratings/comments (if logged in)



---

## 🪑 Seat Selection & Payment Flow

Logged-in users can:

1. 🛒 Click **Buy Now**
2. 🕒 Select the **time and location**
3. 🎭 Get redirected to the **Hall View** to select seats (based on a dynamic seat array)
4. 💳 Proceed to **Stripe Payment Gateway** with all details (movie, time, seat, location)
5. ✅ If successful:
   - Redirected back to website
   - Ticket(s) shown and available in user account
   - Option to **Print Tickets**



---

## 🗃️ Tech Stack

- **Frontend:** React 
- **Backend:** .NET 
- **Database:** SQL Server
- **Payment:** Stripe API

---

