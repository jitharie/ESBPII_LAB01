# **ESBPII** **-** **LAB03** #
----------

###Name : Haputhanthrie J.S###
###ID No : IT13113582###

##Exercise 1##
###********** Login to AWS Account **********###
1. Create your AWS account and login to it.
![Login](http://i.imgur.com/ufbfuRq.png)
##Exercise 2##
###********** Creating amazon RDS instance (MySQL) **********###
- After login to the AWS site select RDS database from Amerzon Web Services

![RDS](http://i.imgur.com/cibeeq3.png)

- Select subnet group from RDS dashboard

![subnet group](http://i.imgur.com/7GBS821.png)

- Create new subnet group

![create sub](http://i.imgur.com/PLDco2F.png)

- Use name and description for the database and select the relevant VPC ID,Available zone,Subnet ID as follows.

- Select **add** **all** **the** **subnets** and you may remove the last subnet id from the id group. Then **Create**.

![detail sub](http://i.imgur.com/gwOcedX.png)

- After creating subnets groups next create DB instance.

![Instance](http://i.imgur.com/0k7u4xy.png)

- Next select launch DB instance

![Launch instance](http://i.imgur.com/jPuL54J.png)

- Select mySQL as engine

![mySQL](http://i.imgur.com/2Vy0Dlz.png)

- Now select RDS free usage tier and click next step

![mySQL free tier](http://i.imgur.com/rLRdTmV.png)

- Specify DB Details. Select DB instance class as **db.t2.micro** (free tier eligible) 
- In the settings section provide a db identifier, a master username and a password. Remember these as they will be used to connect to the db instance later. Then go to the next step. 

![config settings 1](http://i.imgur.com/QuRfnhD.png)

- Configure advanced settings. Select the subnet group you created. Then select the availability zone. Provide a database name in the database. Set backup period to 0 if you prefer the free option. Then click Launch DB instance button. 

![config settings 2](http://i.imgur.com/SqF9zml.png)

![launch instance](http://i.imgur.com/RhH4kGs.png)

![creating instance](http://i.imgur.com/tgV5JC1.png)

![creating instance](http://i.imgur.com/FnGaYFN.png)

![active instance](http://i.imgur.com/IJzd6uR.png)

- You will need MySQL workbench installed on your computer in order to interact with the created MySQL db instance.
- To work with the MySql workbench you can use either mySQL workbench software or command prompt.

![Mysql wrkbench](http://i.imgur.com/Q7edgq2.png)

**Connect RDS using MySql workbench software**

![connect 1](http://i.imgur.com/eKRgiYm.png)

- For the host name use the end point of the RDS and user name and password should match with the RDS user name and password 

![connect 1](http://i.imgur.com/6zGTIAE.png)

![connect 1](http://i.imgur.com/svxeSZl.png)

![connect 1](http://i.imgur.com/XeNF8qR.png)

**Connect RDS using command prompt**

- Open the command prompt and change the path to workbench installation location (alternately you can add mysql to environment variables so that mysql can be accessed from anywhere in the command line).

- Type the following command at a command prompt on a client computer to connect to a database on a MySQL DB instance using the MySQL monitor. Substitute the DNS name for your DB instance for , the master user name you used for , and the master password you used for .

- PROMPT> mysql -h -P 3306 -u -p *** Do not forget to remove the :3306 from the endpoint at the end. Then enter your password and press enter. 

![cmd](http://i.imgur.com/3WeZaUm.png)

![cmd 2](http://i.imgur.com/h6OvvHL.png)

- To delete the db instance Right click on the instance and select Delete. 

![delect ins](http://i.imgur.com/k8GjM5Y.png)

- If you choose not to use the db instance anymore you can select No in 'Create final snapshot'. Tick acknowledge and click delete. 

![delete](http://i.imgur.com/pK35lV2.png)




