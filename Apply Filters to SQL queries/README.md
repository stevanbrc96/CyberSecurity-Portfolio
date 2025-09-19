# Project: SQL for Security Analysis

## Objective
This project demonstrates how to use SQL (Structured Query Language) to query a database and filter for specific information relevant to a security investigation. [cite_start]The goal was to analyze employee and login-attempt data to identify patterns and potential security incidents[cite: 561, 562].

## Process & Tools Used
[cite_start]Using **MariaDB**, I performed several queries on an organizational database containing `employees` and `log_in_attempts` tables[cite: 563]. Key tasks included:
* [cite_start]**Filtering After-Hours Logins:** Wrote a query using `WHERE`, `AND`, and comparison operators to isolate all failed login attempts that occurred after business hours (`18:00`)[cite: 592, 593, 594, 595].
* [cite_start]**Investigating Specific Dates:** Used the `OR` operator to retrieve all login activity from a specific date and the day prior to investigate a suspicious event[cite: 597, 598, 599, 600].
* [cite_start]**Excluding Specific Locations:** Employed the `NOT LIKE` operator with a wildcard (`%`) to filter out all login attempts originating from a specific country to narrow down an investigation[cite: 694, 695].
* [cite_start]**Querying Employee Data:** Used `AND`, `OR`, and `NOT` operators to gather information on employees from specific departments or office locations for targeted system updates[cite: 838, 854, 869].

## Skills Demonstrated
* **SQL Querying:** Proficiency in writing SQL statements with `SELECT`, `FROM`, `WHERE`, `AND`, `OR`, `NOT`, and `LIKE`.
* **Data Analysis:** Ability to extract and interpret data to answer security-related questions.
* **Log Investigation:** Simulating the process of querying log data to investigate potential security incidents.
* **Database Management:** Basic interaction with a relational database system (MariaDB).