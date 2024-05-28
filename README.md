# study_planner

Overview
This Python project is designed to help students create a study schedule based on the complexity of the subjects and topics they need to cover. It reads complexity data from a CSV file, trains a linear regression model to predict study times, and then schedules study sessions within a user-defined time frame, including breaks and lunch periods. The schedule is displayed with all relevant details.

Features
Reads subject, topic, and complexity data from a CSV file.
Fills missing values with the mean of the column.
Trains a linear regression model to predict study time based on complexity.
Calculates study times for user-specified subjects and topics.
Schedules study sessions within user-defined start and end times, considering breaks and lunch periods.
Avoids scheduling during unavailable time slots specified by the user.
Displays the complete study schedule in a readable format.
