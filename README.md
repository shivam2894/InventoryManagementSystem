## NattuKaka - Inventory Management System

<p align="center">
  <a href="http://3.87.75.52:3000">
    <img src="https://i.imgur.com/SHVx6u4.png"/>
  </a>
</p>


------------
>“NattuKaka"Web Application which is an online inventory management system enabling customers to keep track of all the products that your business has in stock. Company can update, insert , delete as well as view & track their Inventory. The admin has full access to the resources available, and he can also add role based members with limited access to the resources.

------------
#### Technologies used:
- #### Backend
    - Spring Boot for RESTful Web Services
    - Spring Security for JWT based authentication
    - Spring Data JPA as persistence layer
    - Hibernate as ORM tool
- #### Frontend
    - React JS as UI library
    - Tailwind CSS for styling
    - Redux for state management
    - Axios for making API requests
- #### Database
    - MySQL for storing data

------------

#### Prerequisites
- JDK 11 and preffered editor (Eclipse / STS / IntelliJ)
- MySQL
- NodeJS

------------


#### Setup
1. Download the zip file or clone this repository
`git clone https://github.com/PG-DAC-Sept-2021-Project/NattuKakaApp.git`

2. Open `NattuKakaApp-backend` folder in Eclipse / STS
3. Edit `NattuKakaApp-backend/src/main/resources/application.properties` file as per your configuration
4. Run the Spring Boot Application
5. Run the queries provided in `NattuKakaApp-backend/src/main/resources/sqlQueries/userRoles` in the created database `nk`
5. Open `NattuKakaApp-frontend` folder in your preffered editor and run `npm install` to install all dependencies
6. Run `npm run dev` and access the development server on `http://localhost:3000` on your browser

