# Student Progress Bar

This table tracks student progress based on their activities within the app.

## Schema

| No   | Property              | Type      | Description                                                  |
| ---- | --------------------- | --------- | ------------------------------------------------------------ |
| 1.   | id                    | object_id | Unique identifier for progress tracking                      |
| 2.   | student_id            | num       | Foreign key linking the progress to a student                |
| 3.   | student_id            | num       | Foreign key linking the progress to a subject                |
| 4.   | lessons_completed     | num       | Number of lessons completed in the subject                   |
| 5.   | quizzes_taken         | num       | Number of quizzes attempted                                  |
| 6.   | average_score         | num       | The student's average quiz score (%)                         |
| 7.   | completion_percentage | num       | Percentage of the subject completed (auto-calculated)        |
| 8.   | performance_level     | String    | Status based on progress (e.g., Beginner, Intermediate, Advanced) |
|      |                       |           |                                                              |
|      |                       |           |                                                              |
|      |                       |           |                                                              |

