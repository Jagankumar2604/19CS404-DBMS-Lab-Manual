# ER Diagram Workshop – Submission Template

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario A: City Fitness Club Management

**Business Context:**  
FlexiFit Gym wants a database to manage its members, trainers, and fitness programs.

**Requirements:**  
- Members register with name, membership type, and start date.  
- Each member can join multiple programs (Yoga, Zumba, Weight Training).  
- Trainers assigned to programs; a program may have multiple trainers.  
- Members may book personal training sessions with trainers.  
- Attendance recorded for each session.  
- Payments tracked for memberships and sessions.

### ER Diagram:
*Paste or attach your diagram here*  
<img width="893" height="495" alt="image" src="https://github.com/user-attachments/assets/b1edb208-57fe-49d8-aab9-c9ad4ca42cc3" />

### Entities and Attributes

<img width="1083" height="333" alt="image" src="https://github.com/user-attachments/assets/b06016d9-ddb2-4a28-b7cf-d69ed0ad6bd1" />


### Relationships and Constraints

<img width="1281" height="411" alt="image" src="https://github.com/user-attachments/assets/8f8f698f-d3f3-4c60-9534-319c6a643dc0" />


### Assumptions

> Every trainer can teach one or more programs.
> Members may join multiple fitness programs.
> Attendance is recorded for every session Payments are made only by registered members

---

# Scenario B: City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:
*Paste or attach your diagram here*  
<img width="870" height="502" alt="image" src="https://github.com/user-attachments/assets/9a46ebf0-ade8-44cb-ac89-c3aeb4b8dcb1" />

### Entities and Attributes
<img width="867" height="305" alt="image" src="https://github.com/user-attachments/assets/8a6898d4-7bdf-4280-8168-d37d20cf5d31" />


### Relationships and Constraints

<img width="998" height="270" alt="image" src="https://github.com/user-attachments/assets/39bf7227-c91c-4922-aec9-d65258e7b42c" />


### Assumptions

> Only registered members can borrow books.
> Members may register for multiple events.
> Members may register for multiple events. A book can be borrowed many times at different periods.

---

# Scenario C: Restaurant Table Reservation & Ordering

**Business Context:**  
A popular restaurant wants to manage reservations, orders, and billing.

**Requirements:**  
- Customers can reserve tables or walk in.  
- Each reservation includes date, time, and number of guests.  
- Customers place food orders linked to reservations.  
- Each order contains multiple dishes; dishes belong to categories (starter, main, dessert).  
- Bills generated per reservation, including food and service charges.  
- Waiters assigned to serve reservations.

### ER Diagram:
*Paste or attach your diagram here*  
<img width="900" height="456" alt="image" src="https://github.com/user-attachments/assets/efec5e75-f9d7-4d19-9390-0d21865c6480" />

### Entities and Attributes

<img width="1085" height="302" alt="image" src="https://github.com/user-attachments/assets/ef6799b6-bd94-4deb-97a0-9555b96d744a" />


### Relationships and Constraints

<img width="1250" height="261" alt="image" src="https://github.com/user-attachments/assets/1fe2e128-4574-4ef5-b3cd-f95cd7e5f7f1" />


### Assumptions

> Only customers can make reservations.
> Every reservation is served by one waiter
> Multiple dishes can be included in a single order.

---

## Instructions for Students

1. Complete **all three scenarios** (A, B, C).  
2. Identify entities, relationships, and attributes for each.  
3. Draw ER diagrams using **draw.io / diagrams.net** or hand-drawn & scanned.  
4. Fill in all tables and assumptions for each scenario.  
5. Export the completed Markdown (with diagrams) as **a single PDF**
