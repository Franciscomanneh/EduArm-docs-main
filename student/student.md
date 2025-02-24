# Student 

Helps track student performance and personalize their learning experience.

Enables login authentication and profile management.

Supports progress tracking and lesson recommendations.

## Schema



| No   | Property        | Type      | Description                                                 |
| ---- | --------------- | --------- | ----------------------------------------------------------- |
| 1.   | id              | object_id | Unique identifier for the student                           |
| 2.   | full_name       | String    | Student’s full name                                         |
| 3.   | email           | String    | Student’s email address (optional)                          |
| 4.   | phone_number    | num       | Contact number for communication (optional)                 |
| 5.   | user_name       | String    | Unique username for login                                   |
| 6.   | password        | String    | Encrypted password for security                             |
| 7.   | grade_id        | num       | Foreign key linking to the student’s grade level            |
| 8.   | profile_picture | String    | Link to the student’s profile image (optional)              |
| 9.   | date-of_birth   | num       | Student’s birthdate (optional)                              |
| 10.  | enrollment_date | num       | Date the student registered on the platform                 |
| 11.  | progress_status | String    | Current learning status (e.g., Active, Inactive, Completed) |
|      |                 |           |                                                             |
|      |                 |           |                                                             |
|      |                 |           |                                                             |

