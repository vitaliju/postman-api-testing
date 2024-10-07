# Website API Testing With Postman/Newman

This repository contains Postman collections designed for API testing, with the capability to run automated tests using Newman, the CLI companion to Postman. These collections are crafted to ensure that tests are re-runnable without side effects, allowing for consistent and reliable testing in different environments.

### Test Cases

1. Get All Products List
2. Get All Brands List
3. POST To Create/Register User Account
4. POST To Verify Login without email parameter
5. POST To Verify Login with invalid details
6. POST To Verify Login with valid details
7. GET user account detail by email
8. PUT METHOD To Update User Account
9. DELETE METHOD To Delete User Account
10. DELETE To Verify Login

### 💻 Prerequisites

Node.js - _download and install_

```
https://nodejs.org
```

Git - _download and install_

```
https://git-scm.com
```

Postman - _download and install_

```
https://www.postman.com/downloads/
```

### 🏃 Run locally

Would like to run this project locally? Open terminal and follow these steps:

1. Clone the repo
    ```sh
    git clone https://github.com/vitaliju/website-api-testing.git
    ```
2. Install NPM packages

    ```sh
    npm i
    ```

    or

    ```sh
    npm install
    ```

## Run Tests

Once the installation is complete, you can run the Newman tests as follow:

1: Running Newman :

```sh
npm run test
```

### View Test Results

Test results can be viewed in the "Actions" tab of your GitHub repository.

## 🎅 Authors

Vitalijus: [Github](https://github.com/vitaliju)

## ⚠️ License

Distributed under the ISC License. See [LICENSE.txt](./LICENSE.txt) for more information
