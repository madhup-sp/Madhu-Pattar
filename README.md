Company ABC wants to move their product to AWS. They have the following
things set up right now:
1. MySQL DB
2. Website (PHP)
   
The company wants high availability on this product, therefore wants Auto
Scaling to be enabled on this website.
Steps To Solve:
1. Launch an EC2 Instance
2. Enable Auto Scaling on these instances (minimum 2)
3. Create an RDS Instance
4. Create Database & Table in RDS instance:
a. Database name: intel
b. Table name: data
c. Database password: intel123
5. Change hostname in website
6. Allow traffic from EC2 to RDS instanc
