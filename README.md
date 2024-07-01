# Filtering SQL Queries

## Objective

The following steps provide examples of how I used SQL with filters to perform security-related tasks. Such as, investigating protential security issues and filtering employee computers to update systems.

### Skills Learned

- Using SQL to find failed login attempts.
- Filtering to find time and dates of login attempts.
- Retrieving login attempts outside of a certin country.
- Filtering for employee information from specific departments in the organization.

### Tools Used

- MariaDB Shell to run SQL Queries.

## Steps
1) Retrieve after hours failed login attempts: There was a potential security incident that occurred after business hours (after 18:00). All after hours login attempts that failed need to be investigated.

![1](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/b21bc497-2212-4b20-af94-d3a924fdc1e8)

![2](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/a032b4e4-a1aa-4eb7-b59f-93f0e547a9aa)

2) Retrieve login attempts on specific dates: A suspicious event occurred on 2022-05-09. Any login activity that happened on 2022-05-09 or on the day before needs to be investigated. The following code demonstrates how I created a SQL query to filter for login attempts that occurred on specific dates.

![3](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/547413f1-01ad-40b8-9d23-428561ee870d)

![4](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/c077ffbf-334c-42eb-a4df-9911ab19e2aa)

3) Retrieve login attempts outside of Mexico: After investigating the organization’s data on login attempts, I believe there is an issue with the login attempts that occurred outside of Mexico. These login attempts should be investigated.

![5](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/0c4e727b-1a8a-49be-8623-fa3ee6431894)

![6](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/5bb899be-1fb6-4117-948d-cbbead8c15ce)

3) Retrieve employees in Marketing: My team wants to update the computers for certain employees in the Marketing department. To do this, I have to get information on which employee machines to update.

![7](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/89345a8d-b627-4d7e-a921-f08f56ac7d03)

4) Retrieve employees in Finance or Sales: The machines for employees in the Finance and Sales departments also need to be updated. Since a different security update is needed, I have to get information on employees only from these two departments.

![8](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/14ff9350-54fe-47d0-895f-1d85ecf4fb79)

5) Retrieve all employees not in IT: My team needs to make one more security update on employees who are not in the Information Technology department. To make the update, I first have to get information on these employees.

![9](https://github.com/KylePBell/Filtering-SQL-Queries/assets/174375217/b7131878-581b-40b8-b9c5-bd9717d36436)
