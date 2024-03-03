# MONGO-DB-TASK-2

**MongoDB Queries and Results**

This repository contains MongoDB queries along with their corresponding results for various tasks related to managing data for a fictional organization. Below is a brief overview of each task and its associated query and result.

**Task 1: Find all the topics and tasks taught in the month of October**
- **Query**: 
  - Finds topics taught in October along with the tasks associated with them.
- **Result**: 
  - Lists topic ID, covered by, held on date, and the assigned task.

**Task 2: Find all the company drives appearing between 15th Oct 2020 and 31st Oct 2020**
- **Query**:
  - Retrieves company drives within the specified date range.
- **Result**:
  - Displays the company name and the date of the drive.

**Task 3: Find all the company drives and students who appeared for the placement**
- **Query**:
  - Matches documents where students attended the placement and retrieves their information along with the company name.
- **Result**:
  - Lists company names along with the usernames of students who attended the placement.

**Task 4: Find the number of problems solved by users in CodeKata**
- **Query**:
  - Joins data from the 'codekata' collection with 'users' collection and calculates the total number of problems solved by each user.
- **Result**:
  - Provides the user ID, name, email, and the number of problems solved.

**Task 5: Find all mentors with more than 15 mentees**
- **Query**:
  - Retrieves mentors having more than 15 mentees.
- **Result**:
  - Lists mentor details along with the count of mentees.

**Task 6: Find the number of users who were absent and did not submit tasks between 15th Oct 2020 and 31st Oct 2020**
- **Query**:
  - Matches documents where users were absent and tasks were not submitted within the specified date range.
- **Result**:
  - Provides user details along with the attendance status and tasks not submitted within the specified date range.
