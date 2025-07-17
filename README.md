# 🎬 Cinema Paradise

Welcome to **Cinema Paradise** – a modern and interactive cinema website where users can explore movies currently running, view trailers, book seats, and purchase tickets. Admins can also access a full dashboard with detailed business insights.

---


https://github.com/user-attachments/assets/ba3bb78e-a9ed-46f4-ae6e-47d31d9a5324


---

## 🏠 Homepage Overview

The main page includes:

- 🎞️ **Movies Listing** – See all movies currently in theaters.
- 🔍 **Filters** – Filter movies by:
  - *Genre*
  <img width="1909" height="920" alt="image" src="https://github.com/user-attachments/assets/b546b904-e727-4103-9613-8367d12eb960" />

  - *Name*
  <img width="1907" height="918" alt="image" src="https://github.com/user-attachments/assets/3e444d29-af47-4bdd-81d7-6ed60445fca0" />

- 📊 **Sorting System** – Sort movies by:
  - Name
  - Duration
  - Rating
  <img width="1397" height="911" alt="image" src="https://github.com/user-attachments/assets/30517af0-ee3f-4672-b565-1e7109e5f8e0" />

- 📍 **Cinema Location Display** – Shows where each movie is playing.


<img width="1907" height="920" alt="image" src="https://github.com/user-attachments/assets/eeea20e1-88f3-4637-9584-73c5196982ec" />


---

## 🔐 Authentication

The site features:

- 🧑‍💻 **Login/Register System**
  - Two types of users: **User** and **Admin**
  <img width="1910" height="897" alt="image" src="https://github.com/user-attachments/assets/4a6490f6-6fb5-4cfb-9c0f-fad4f869134d" />
  <img width="1904" height="804" alt="image" src="https://github.com/user-attachments/assets/bdbcab5e-4bc6-45b5-91e6-4ec0baa36848" />
  - Secure authentication flow
  - Change profile details
  <img width="1906" height="734" alt="image" src="https://github.com/user-attachments/assets/33250854-fa4a-4cbc-a0ee-64ac155a9efc" />




---

## 🛠️ Admin Dashboard

The **Admin Dashboard** offers full control over cinema operations and content management. Admins can analyze performance and easily manage movies, projections, and cinema halls.

### 👤 User vs Admin View

Admins get access to extended features unavailable to regular users. Here's a comparison:

| User View | Admin View |
|-----------|------------|
<img width="164" height="201" alt="image" src="https://github.com/user-attachments/assets/9a506188-7dad-450d-81b5-ccad8d110f00" />
<img width="161" height="240" alt="image" src="https://github.com/user-attachments/assets/b22cac1c-9db0-4fa1-8f40-a691721adee2" />

### 🎬 Add / Edit Movie

Admins can add new movies or update existing ones, including title, duration, genre, rating, description, and trailer.

📸 _Add/Edit Movie Interface:_  
<img width="1916" height="922" alt="image" src="https://github.com/user-attachments/assets/b28375f5-b15d-488f-b7bc-1b519769e8ee" />
### 📽️ Manage Projection Types

Admins can define or update **projection types** (e.g., 2D, 3D, IMAX) to organize show formats effectively.

📸 _Add/Edit Projection Type:_ 
<img width="1909" height="909" alt="image" src="https://github.com/user-attachments/assets/1e508b2f-5239-4c26-a2dc-5580d90a95e9" />
### 🏢 Add Movie Hall & Location

Cinemas can operate multiple halls across different locations. This section allows the admin to create and manage these venues.

📸 _Add/Edit Movie Halls & Locations:_  


https://github.com/user-attachments/assets/dcd1833b-0a91-4696-b633-2644c5823c02



### 📊 Dashboard Metrics

- 💰 Total movie revenue
- 📈 Profits & insights
- 🎟️ Ticket sales breakdown
<img width="1905" height="898" alt="image" src="https://github.com/user-attachments/assets/02a8dcc4-7e23-4ae1-ada4-70a960dc4bd4" />

---

## 🎥 Movie Details Page

When clicking on a movie from the list, users are taken to a detailed movie page which includes:

- 🎞️ **Trailer**
- 🕒 **Airing Times & Locations**
- ⭐ **Rating**
- 📝 **Title & Description**
- 🧑‍🏫 **User Reviews** – View and add ratings/comments (if logged in)
- 



---

## 🪑 Seat Selection & Payment Flow

Logged-in users can:

1. 🛒 Click **Buy Now**
2. 🕒 Select the **time and location**
3. 🎭 Get redirected to the **Hall View** to select seats (based on a dynamic seat array) 

https://github.com/user-attachments/assets/ada57da4-eea5-4631-8503-9f4466c5ac12


4. 💳 Proceed to **Stripe Payment Gateway** with all details (movie, time, seat, location)
5. ✅ If successful:
   - Redirected back to website
   - Ticket(s) shown and available in user account
   - Option to **Print Tickets**

-Video Soon



---
## ❗ Error Handling & Notifications

Cinema Paradise ensures a seamless and safe experience through robust error handling and user communication features.

---

### 🚨 Custom Error Page

When something goes wrong (like a 404, 500, or Stripe failure), users are redirected to a user-friendly error page.


📸 _Custom Error Page Preview:_  
<img width="1903" height="907" alt="image" src="https://github.com/user-attachments/assets/2f5d1ab7-d15f-41d5-b107-14e22b8a0455" />


---

### 📧 Email Notifications

Cinema Paradise uses automated email systems to notify users about reservations made.


These are implemented using:
- A transactional email service **MailJet**.
- Backend integration (.NET)

📸 _Example Email Preview:_  
<img width="598" height="344" alt="Mail" src="https://github.com/user-attachments/assets/8cd3964c-ad8b-4c5f-8c52-8870628402b2" />


---

## 🗃️ Tech Stack

- **Frontend:** React 
- **Backend:** .NET 
- **Database:** SQL Server
- **Payment:** Stripe API
- **Email** MailJet

---

