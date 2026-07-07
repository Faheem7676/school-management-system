# User Table Design

## Entity: User

| Field | Type | Required |
|--------|------|----------|
| email | Email | Yes |
| password | Password | Yes |
| first_name | String | Yes |
| last_name | String | Yes |
| phone | String | No |
| role | Choice | Yes |
| is_active | Boolean | Yes |
| is_staff | Boolean | Yes |
| created_at | DateTime | Yes |
| updated_at | DateTime | Yes |

## Roles

- ADMIN
- PRINCIPAL
- TEACHER
- STUDENT
- PARENT
- ACCOUNTANT
- LIBRARIAN