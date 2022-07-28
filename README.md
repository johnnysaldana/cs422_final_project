# Online Shop Application

#### A full-stack Online Shop web application using Spring Boot and Angular 8. 
This is a Single Page Appliaction with client-side rendering. It includes [backend](https://github.com/singhanshika311/wipro_capstone_project_c7_b2/tree/master/BACKEND) and [frontend](https://github.com/singhanshika311/wipro_capstone_project_c7_b2/tree/master/FRONTEND) two seperate projects on different branches.
E-Commerce application developed for performing Admin and Customer user role operations with respective user interfaces. Application is implemented in two parts:
1. RESTfull web services: API's build using spring boot are used for handling all the back end operations 
2. Front End: User interfaces designed and developed using Angular utilising web services for handling appropriate user actions.I also use [angular material](https://material.angular.io/) UI component library for creating frontend component like navbar, buttons
The frontend client makes API calls to the backend server when it is running.

#### Features available based on the user role
* Admin
  * Adding products
  * Adding catagories
  * Updating products
  * Deleting products
  * Manage Orders
  * View user
  * Can send email
  * Can upload bulk data in csv format
* Customer
  * Registering into System
  * Login into Website
  * Add product in wishlist
  * Adding product to Cart
  * Updating/ Deleting the Product in cart as well as in wishlist
  * Placing the order

* Technologies: 
  * Angular8 (https://material.angular.io/)
  * Typescript
  * Spring Boot
  * Hibernate with JPA 
  * MySQL
 
 #### Application screenshots
* Login 
    ![Image of screenshot](https://github.com/singhanshika311/wipro_capstone_project_c7_b2/blob/master/PROJECT%20IMAGES/login.jpeg)
* Register 
    ![Image of screenshot](https://github.com/singhanshika311/wipro_capstone_project_c7_b2/blob/master/PROJECT%20IMAGES/register.jpeg)
* Customer 
    * Home 
        ![Image of screenshot](https://github.com/cyela/Angular-Springboot/blob/master/src/assets/Screenshots/CustHome.png)
    * Address 
        ![Image of screenshot](https://github.com/cyela/Angular-Springboot/blob/master/src/assets/Screenshots/CustAddress.png)
    * Cart 
        ![Image of screenshot](https://github.com/cyela/Angular-Springboot/blob/master/src/assets/Screenshots/CartScreen.png)
* Admin 
    * Home
        ![Image of screenshot](https://github.com/cyela/Angular-Springboot/blob/master/src/assets/Screenshots/AdminHome.png)
    * Add new product 
        ![Image of screenshot](https://github.com/cyela/Angular-Springboot/blob/master/src/assets/Screenshots/AddProduct.png)
    * Edit product 
        ![Image of screenshot](https://github.com/cyela/Angular-Springboot/blob/master/src/assets/Screenshots/EditProduct.png)
    * View orders 
        ![Image of screenshot](https://github.com/cyela/Angular-Springboot/blob/master/src/assets/Screenshots/OrderScreen.png)
---------


## How to  Run

Start the backend server before the frontend client.  

**Backend**

  1. Install [MYSQL](https://www.mysql.org/download/) 
  2. Configure datasource in `application.yml`.
  3. `cd backend`.
  4. Run `mvn install`.
  5. Run `mvn spring-boot:run`.
  6. Spring Boot will import mock data into database by executing `import.sql` automatically.
  7. The backend server is running on [localhost:8080]().

**Frontend**
  1. Install [Node.js and npm](https://www.npmjs.com/get-npm)
  2. `cd frontend`.
  3. Run `npm install`.
  4. Run `ng serve`
  5. The frontend client is running on [localhost:4200]().
