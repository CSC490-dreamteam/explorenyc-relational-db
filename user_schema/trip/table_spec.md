| Column Name | Data Type | Format                                     |
|-------------|-----------|--------------------------------------------|
| trip_id     | INTEGER   | Generated Autoinc                          |
| entry_point | VARCHAR   |                                            |
| exit_point  | VARCHAR   |                                            |
| start_time  | TIMESTAMP |                                            |
| end_time    | TIMESTAMP |                                            |
| stops       | JSON      | Includes start/end, see stops_example.json |
| tags        | JSON      |                                            |
| user_id     | INTEGER   | Foreign Key                                |
