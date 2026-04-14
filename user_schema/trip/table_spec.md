| Column Name   | Data Type | Format                                     |
|---------------|-----------|--------------------------------------------|
| trip_id       | INTEGER    | Generated as identity Autoinc PK           |
| entry datetime| TIMESTAMP  |                                            |
| exit_datetime | TIMESTAMP  |                                            |
| stops         | JSON       | Includes start/end, see stops_example.json, not null |
| tags          | JSON       |                                            |
| user_id       | INTEGER    | Foreign Key                                |
| status        | VARCHAR(32)|                                            |
| name          | TEXT       |                                            |
| public        | BOOLEAN    | NOTNULL                                    |
