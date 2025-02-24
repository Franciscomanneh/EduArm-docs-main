# Quiz 

This table will help track students' progress and performance in quizzes. 

## Schema



| No   | Property         | Type      | Description                                     |
| ---- | ---------------- | --------- | ----------------------------------------------- |
| 1.   | id               | object_id | Unique identifier for the quiz                  |
| 2.   | title            | String    | Name of the quiz                                |
| 3.   | student_id       | num       | Foreign key linking the quiz to a subject       |
| 4.   | grade_id         | num       | Foreign key linking the quiz to a grade         |
| 5.   | difficulty_level | String    | The complexity of the quiz (Easy, Medium, Hard) |
| 6.   | total-marks      | num       | The maximum possible marks                      |
| 7.   | time_limit       | num       | Duration of the quiz (if applicable)            |
|      |                  |           |                                                 |
|      |                  |           |                                                 |

