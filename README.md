# DE141_PROJECT

A database design project built in **Oracle SQL Developer Data Modeler**, modeling an exam
registration system for Thai university entrance exams (A-Level, TGAT, TPAT subjects).

## Entities

- **STUDENT** – exam candidates
- **SUBJECT** – exam subject/category catalog (Alevel, Tgat, Tpat)
- **EXAM** – a specific exam instance for a subject
- **EXAM ROOM** – physical rooms exams are held in
- **EXAM SCHEDULE** – links an exam to a room/time slot
- **EXAM REGISTRATION** – a student signing up for an exam
- **EXAM STUDENT** – a student's attendance/result record for an exam

## Opening the project

Open `DE141-P-2.dmd` (or the top-level `.dmd` design) in
[Oracle SQL Developer Data Modeler](https://www.oracle.com/database/sqldeveloper/technologies/sql-data-modeler/)
to view and edit the ER diagram, relational model, and generated DDL.
