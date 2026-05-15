# Project Name : Dmoney API Testing

## Project Description:
##### This API testing project covers the DMoney system, including User Registration & Authentication, Roles & Money Flow, and Customer Transactions. Here users are created by register via self-signup and activated through email confirmation and admin approval. Authentication uses credential login with OTP verification for most roles, while Admin/System uses JWT-based access for secure control. The system manages hierarchical money flow where SYSTEM acts as the central pool, Admin funds SYSTEM, Agents distribute money to Customers with commission, and Customers operate within wallet limits. Customer transactions include cash-out via agents, P2P transfers, and merchant payments with service fees. Overall, the project ensures secure authentication, role-based access control, and accurate transaction, fee, and commission handling across the system.

#### Technology Used:
- Node JS
- Postman
- Newman
- HTML Report Extra

#### API Documentation:
[Click Here to see the API Documentation](https://documenter.getpostman.com/view/54469406/2sBXqQHJFr#0622fdde-a85b-4eab-8a7b-bec60c7afd4a)

### Newman Installation and Report:

##### Newman Installation:

- `npm init -y`
- `npm i newman`
- `npm i dotenv`
- `npm i newman-reporter-htmlextra`

##### Newman Report:

##### Report Creation Command:
- `newman run file_name.json --delay-request (how much delay)`
- `node .\report.js`



<img width="2400" height="2400" alt="127 0 0 1_5500_Reports_report html" src="https://github.com/user-attachments/assets/18e3cf6b-81fb-4db2-9c30-c09bb89bf97a" />
<img width="2400" height="2400" alt="127 0 0 1_5500_Reports_report html (1)" src="https://github.com/user-attachments/assets/4e049b5a-703e-4b4a-b027-8405f4b15d3b" />

