# Chess Connect

A chess club management system for any chess club, built with a MySQL Workbench database design and an Oracle APEX application. It manages members, coaches, tournaments, classes and user accounts across clubs. Built as my year-long academic project for my Diploma in ICT (Application Development) at Walter Sisulu University.

## User Roles
* **Organiser:** Creates tournaments, accepts or rejects the entry submissions that coaches make for them, and generates the pairings on the day of the tournament.
* **Coach:** Sees how many of their players have said they are going to a tournament, then submits an entry to the organiser.
* **Player:** Responds (RSVP) to a tournament. The RSVP goes to their coach.
* **Admin:** Posts and manages announcements for the club.

## How It Works
1. The organiser creates a tournament.
2. Players RSVP to the tournament, and the RSVPs go to their coaches.
3. Each coach sees how many players are going, then submits an entry for the tournament.
4. The organiser accepts or rejects each coach's entry.
5. On the day of the tournament, the organiser generates the pairings in the app.

   ## Features
* **Centralized Person Records:** Manages personal data securely across roles (Players, Coaches, Organizers, IT Admins).
* **Tournament Management:** Tracks club entries, tournament brackets, matches, and automated fee messaging.
* **Pairings:** Organisers generate the pairings in the app on tournament day.
* **Security:** Includes a `USER_ACCOUNTS` table with hashed passwords for system authentication.
* **Role-based dashboards:** Separate dashboards for each user role.

## Technologies Used
* MySQL & MySQL Workbench (relational database design: 1NF, 2NF, 3NF)
* Oracle APEX and SQL (application)

## Files
* `f196477.sql`: the exported Oracle APEX application
* `chess_connect_schema.sql`: database tables, views and indexes

## Screenshots
## Login Page
<img width="306" height="309" alt="image" src="https://github.com/user-attachments/assets/8f322079-5b12-44a7-8c11-877922a38ce6" />



### Admin Home
<img width="1356" height="161" alt="image" src="https://github.com/user-attachments/assets/ec6af94a-9512-4026-85ed-8cf9acf21a71" />


### Coach Home
<img width="1354" height="308" alt="image" src="https://github.com/user-attachments/assets/efd5a5cd-ae62-4a72-a170-4e5e506f76b0" />



### Player Home
<img width="1363" height="284" alt="image" src="https://github.com/user-attachments/assets/55dad516-9bc8-465d-bf7c-60872f3f4d98" />



### Organiser Home
<img width="1353" height="367" alt="image" src="https://github.com/user-attachments/assets/9e7f0888-e222-44fd-a544-61e6a825dc1d" />


### Tournaments
<img width="1347" height="505" alt="image" src="https://github.com/user-attachments/assets/721037dd-216f-4337-8419-0e3001ab5ca3" />



### Fixtures
<img width="1338" height="595" alt="image" src="https://github.com/user-attachments/assets/8dae64cd-ae66-44a9-a7bd-e48850110014" />
