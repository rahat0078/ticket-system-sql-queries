## Football Ticket Booking System

### Overview

This project is a simplified Football Ticket Booking System database developed as part of a Database Design & SQL assignment.

The system manages:

- Users (Football Fans and Ticket Managers)
- Football Matches
- Ticket Bookings

The project demonstrates database design concepts including:

- Primary Keys (PK)
- Foreign Keys (FK)
- One-to-Many Relationships
- SQL Joins
- Subqueries
- Aggregate Functions
- NULL Handling
- Pagination

---

### Database Tables

#### Users

Stores information about registered users.

| Field | Description |
|---------|------------|
| user_id | Unique user identifier |
| full_name | User's full name |
| email | User email address |
| role | Football Fan or Ticket Manager |
| phone_number | Contact number |

#### Matches

Stores football match information.

| Field | Description |
|---------|------------|
| match_id | Unique match identifier |
| fixture | Competing teams |
| tournament_category | League or tournament |
| base_ticket_price | Ticket price |
| match_status | Match availability status |

#### Bookings

Stores ticket booking records.

| Field | Description |
|---------|------------|
| booking_id | Unique booking identifier |
| user_id | User reference |
| match_id | Match reference |
| seat_number | Stadium seat |
| payment_status | Payment status |
| total_cost | Booking cost |

---

#### Relationships

- One User can have many Bookings.
- One Match can have many Bookings.
- Each Booking belongs to exactly one User and one Match.

---

### SQL Queries

The project includes solutions for:

1. Available Champions League matches.
2. User search using LIKE / ILIKE.
3. NULL handling using COALESCE.
4. INNER JOIN between Users, Matches, and Bookings.
5. LEFT JOIN for users without bookings.
6. Subquery using AVG().
7. Pagination using LIMIT and OFFSET.

---

### ERD

ERD Link:

https://drive.google.com/file/d/1SqX0Lm86z01bvOj8Or50SmMWv9bqMNlq/view?usp=sharing

---





