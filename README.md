# BookMyShow Clone

A full-stack movie ticket booking web application built with Spring Boot and standard web frontend technologies.

---

## What It Does

- **Movie Listings & Search**: Displays active movies with details, genres, and durations.
- **Showtime Selection**: Filters upcoming showtimes by city and date.
- **Interactive Seat Booking**: Allows users to select available seats and book tickets in real time.
- **Booking Management**: Tracks user bookings and prevents seat double-booking.

---

## Tech Stack

- **Backend**: Java 17, Spring Boot, Spring Data JPA, MySQL
- **Frontend**: HTML5, CSS3, JavaScript (Fetch API)
- **Tools**: IntelliJ IDEA, VS Code, Git, Postman

---

## Key Backend Highlights

- **Optimistic Locking (`@Version`)**: Applied on shows to prevent concurrent seat double-booking.
- **Query Optimization**: Custom JPQL queries using `JOIN FETCH` to prevent N+1 query performance issues.
- **Clean Architecture**: Organized into layered Controllers, Services, Repositories, Entities, and DTOs.

---

## How to Run

### 1. Spring Boot Backend
1. Clone the repository:
   ```bash
   git clone [https://github.com/yogesh-87/BookMyShow-FullStack.git](https://github.com/yogesh-87/BookMyShow-FullStack.git)
