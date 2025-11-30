A C-based console application designed to manage subscribers in a health insurance system.
The program enables users to register subscribers, store records permanently, list all subscribers, and process medical insurance claims according to predefined annual limits.
OBJECTIVE:
The objective of this project is to implement basic data management, file handling, and modular programming concepts in C by creating an interactive Health Insurance Management System.

FEATURES:
🔹 ADD SUBSCRIBER
1)Assigns a unique ID automatically
2)Stores subscriber details (Name, Age, Plan, Annual Claim Limit)
3)Saves information permanently using file handling
🔹 LIST SUBSCRIBER
1)Displays all subscribers in a tabular format
2)Shows used and remaining claim limit
🔹 PROCESS CLAIM
1)Validates the requested claim amount
2)Approves, partially approves, or rejects claim based on remaining limit
3)Updates the record in the file
🔹 Exit
1)Safely terminates the system

RUNNING OF THE PROGRAM:
Language-	C
Concepts-	 Structures, Arrays, File Handling, Menu-driven Interface
Storage-	Data.txt (Binary file format)
Platform-	GCC/MinGw/VS code
SAMPLE INTERFACE:
1. Add New Subscriber
2. List All Subscribers
3. Process Claim
4. Exit
Enter your choice:

TESTING SUMMARY:
| Test Scenario      | Input                   | Expected Result               |
--------------------------------------------------------------------------------
| Add Subscriber     | Name, Age, Plan, Limit  | Subscriber saved successfully |
| Claim Within Limit | Claim ≤ Remaining Limit | Approved and updated          |
| Claim Beyond Limit | Claim > Limit           | Partial approval or rejection |
| Invalid ID         | Non-existing ID         | Display error message         |

PROJECT REPORT: It includes an Introduction, Problem Statement, System Design, Algorithms, Flowcharts, Screenshots, Testing Summary
CREATED BY:
NAYONIKA AGARWAL
BTECH COMPUTER SCIENCE
UPES,DEHRADUN
