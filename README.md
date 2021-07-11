# finances-API - Financial

# Index

- [About](#-About)
- [Technologies Used](#-Technologies-Used)
- [Requirements](#-Requirements)
- [Business rules](#-Business-rules)
- [How to download the project](#-How-to-download-the-project)

---


## About
 The project is a system of a bank where you can carry out every type of transaction

---

### Requirements

- [x] It should be possible to create an account
- [x] It must be possible to fetch the customer's bank statement
- [x] It must be possible to make a deposit
- [x] It must be possible to make a withdrawal
- [x] It must be possible to search the customer's bank statement by date
- [x] It must be possible to update customer account data
- [x] It must be possible to obtain customer account data
- [x] It must be possible to delete an account
- [x] It must be possible to return the balance

---

## Business rules

- [x] It must not be possible to register an account with an existing CPF
- [x] It must not be possible to make a deposit to a non-existing account
- [x] It must not be possible to fetch a statement from a non-existing account
- [x] It must not be possible to withdraw from a non-existing account
- [x] It must not be possible to withdraw when the balance is insufficient
- [x] It must not be possible to delete a non-existing account


---
## Technologies Used

The project was developed using the following technologies

 - [express](https://expressjs.com/)
 - [nodemon](https://www.npmjs.com/package/nodemon)
 - [uuid](https://www.npmjs.com/package/uuid)

---

## How to download the project

```bash

# Clone the repository
$ git clone https://github.com/tuiusx/financial-api.git

# Enter directory
$ cd financial-api

# Install dependencies
$ yarn 
```