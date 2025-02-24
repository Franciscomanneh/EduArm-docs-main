# Past Papers

These tables will help students access past exam papers along with their answers for effective revision



## Schma



| No   | Property        | Type      | Description                                         |
| ---- | --------------- | --------- | --------------------------------------------------- |
| 1.   | id              | object_id | Unique identifier for the answer record             |
| 2.   | paper_id        | num       | Foreign key linking to the corresponding past paper |
| 3.   | question_number | num       | The number of the question in the past paper        |
| 4.   | answer          | String    | The correct answer (text, image, or explanation)    |
| 5.   | explanation     | String    | Detailed explanation for the answer (optional)      |
|      |                 |           |                                                     |

