# Past Papers

These tables will help students access past exam papers along with their answers for effective revision.

## Schema

| No   | Property   | Type      | Description                                             |
| ---- | ---------- | --------- | ------------------------------------------------------- |
| 1.   | id         | object_id | Unique identifier for the past paper                    |
| 2.   | student_id | num       | Foreign key linking the paper to a specific subject     |
| 3.   | grade_id   | num       | Foreign key linking the paper to a specific grade level |
| 4.   | year       | num       | The year the past paper was issued                      |
| 5.   | exam_type  | String    | Type of exam (e.g., WASSCE, Mock Exam, Test)            |
| 6.   | file_url   | String    | Link to the downloadable past paper (PDF, DOC)          |
|      |            |           |                                                         |
|      |            |           |                                                         |
|      |            |           |                                                         |

