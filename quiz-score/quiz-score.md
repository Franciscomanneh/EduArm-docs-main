# Quiz Score (For Student Attempts)

This table will help track students' progress and performance in quizzes. 

## Schema



| No   | Property    | Type      | Description                                                  |
| ---- | ----------- | --------- | ------------------------------------------------------------ |
| 1.   | id          | object_id | Unique identifier for the quiz score record                  |
| 2.   | student_id  | num       | Foreign key linking the score to a specific student          |
| 3.   | quiz_id     | object_id | Foreign key linking the score to a specific quiz             |
| 4.   | score       | num       | The total marks obtained by the student                      |
| 5.   | total_marks | num       | The maximum possible marks for the quiz                      |
| 6.   | percentage  | num       | Calculated percentage score based on total marks             |
| 7.   | date_taken  | num       | The date and time the quiz was attempted                     |
| 8.   | status      | String    | Pass/Fail or performance category (e.g., Excellent, Good, Needs Improvement) |
|      |             |           |                                                              |

