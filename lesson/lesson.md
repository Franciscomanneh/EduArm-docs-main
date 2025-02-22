# Lessons Table

Stores individual lessons under each subject.

## Schema



| No   | Property         | Type        | Description                                          |
| ---- | ---------------- | ----------- | ---------------------------------------------------- |
| 1.   | id               | object_id   | Unique identifier for the lesson                     |
| 2.   | title            | String      | Lesson title (e.g., Algebra Basics)                  |
| 3.   | subject_id       | String (FK) | Foreign key linking to Subjects                      |
| 4.   | content_type     | String      | Type of content (Text, Video, Quiz, PDF)             |
| 5.   | difficulty_level | String      | Lesson difficulty (Beginner, Intermediate, Advanced) |
| 6.   | file_path        | String      | Path to offline-stored resources                     |
|      |                  |             |                                                      |
|      |                  |             |                                                      |
|      |                  |             |                                                      |

