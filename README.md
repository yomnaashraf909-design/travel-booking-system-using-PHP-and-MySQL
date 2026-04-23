# ✈️ travel-booking-system-using-PHP-and-MySQL

## 📌 Project Overview
The **Flight Booking System** is a dynamic travel web application that allows users to explore and select travel-related services including flights, hotel rooms, restaurants, and tourist attractions based on a selected country.

The system integrates a responsive frontend with a PHP-based backend and a MySQL database to deliver a seamless and interactive user experience.

---

## 🎯 Objectives
- Build an intuitive and user-friendly travel planning interface  
- Dynamically fetch and display data from a MySQL database  
- Provide interactive dropdown selections for travel options  
- Collect personal and travel-related user information  
- Ensure smooth communication between frontend and backend  

---

## 🚀 Features

### 🎨 Front-End Features

#### 🧾 Tourism Form (HTML & CSS)
- 🌍 **Country Selection**: Users select a country from a dropdown menu  
- ✈️ **Dynamic Flight Selection**: Flights are loaded dynamically based on the selected country  
- 👤 **Personal Information Form**:
  - First Name, Last Name  
  - National ID, Passport Number  
  - Address, Email  
  - Gender, Date of Birth  
  - Phone Number, Pre-existing Diseases  
- 📱 **Responsive Design**: Mobile-friendly and clean UI  

---

### ⚡ Dynamic Interaction (JavaScript)
- 🔄 **onChange Event**: Triggers data fetching when country changes  
- 🌐 **AJAX / Fetch API**: Retrieves data without page reload  
- ⚡ **Real-Time Updates**: Improves user experience with dynamic content  

---

### ⚙️ Back-End Features (PHP)

#### 📊 Data Retrieval
Fetches:
- Flights ✈️  
- Hotel Rooms 🏨  
- Restaurants 🍽  
- Tourist Attractions 📍  

Filters results based on the selected country.

---

#### 🧠 Core Files
- `reading.php` → Handles data fetching and returns results  
- `backend.php` → Handles form submission and data storage  

---

#### 📝 Form Submission
- Collects all user inputs  
- Validates data  
- Stores information securely in the database  
- Handles errors and ensures smooth processing  

---

## 🔄 Project Workflow

### 1. 👤 User Interaction
- User selects a country  
- System dynamically loads travel options  
- User fills in personal details  

---

### 2. ⚙️ Backend Processing

**reading.php:**
- Fetches filtered data from the database  
- Sends results to the frontend  

**backend.php:**
- Receives submitted form data  
- Processes and stores it  

---

### 3. ⚡ Dynamic Updates
- JavaScript `fetch()` updates dropdowns instantly  
- No page reload required  

---

## 🗄 Database Design

The system uses a relational database with the following tables:

- `flight`
- `hotel`
- `hotel_room`
- `restaurant`
- `tourist_attraction`

---

### 🔗 Relationships
- One hotel → Many rooms  
- One country → Multiple travel options  

---

## 🛠️ Technologies Used

### Frontend:
- HTML  
- CSS  
- JavaScript  

### Backend:
- PHP  

### Database:
- MySQL  

---

## ✅ Conclusion
The **Flight Booking System** demonstrates a complete full-stack web application combining:

- Dynamic frontend interaction  
- Efficient backend processing  
- Structured database design  
