# Entity Relationship Diagram

## Modules

- User
- Student
- Teacher
- Parent
- Class
- Section
- Subject
- Attendance
- Fee
- Exam
- Result

## Relationships

User (1) -------- (Many) Student

Class (1) ------- (Many) Student

Section (1) ----- (Many) Student

Parent (1) ------ (Many) Student

Teacher (1) ----- (Many) Subject

Subject (Many) -- (Many) Student