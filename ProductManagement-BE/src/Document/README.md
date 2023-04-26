ProductManagement

Technology:-NodeJs,mongodb,express,jsonwebtoken,bcryptjs,express-jwt
Created project using yarn.


System configuration:-

    • Must have mongodb installed.


Overview:-

    • Implement role base authentication with jsonwebtoken and express-jwt authentication mechanism.
    • Develop the endpoints fot the products,
    • Product management is a manage product with role base authentication.
    • Follow MVC structure .
    • Add manually admin with register api (or we can also use seeding in mongodb but it time consuming).
    • Admin can access this product(insert,update,delete and view) 
    • User can only view product list.
      

Env Setup:-

    • Added dev.env file into the root config folder.
         Added below content:
      PORT=3001
      MONGODB_URL="mongodb://localhost:27017/productManagement"
      JWT_SECRET="this is secret for my app"

Steps to start backend:-
                 
    • yarn install (install the node module)
    • yarn start (to start application)



Endpoints:-
     
    • /user/login
 - Manage role base login
      
    • /user/createUser
         - Create user
      
    • /product/createProduct
          -Create product 
      
    • /product/getProduct
          -Get all product details
      
    • /product/getProduct/id
           -Get a single product details based on product id 
      
    • /product/updateProduct/id
            -Update product detail by product id 
      
    • /product/deleteproduct/id
                        -Delete product by product id
                       
     