# **ESBPII** **-** **LAB01** #
----------

###Name : Haputhanthrie J.S###
###ID No : IT13113582###

##Exercise 1##
###********** Login to AWS Account **********###
1. Create your AWS account and login to it.
![Login](http://i.imgur.com/ufbfuRq.png)
##Exercise 2##
###********** Launch windows instance **********###
- Select EC2 from Amerzon Web Services

![EC2](http://i.imgur.com/8sOeyHS.png)

- Launch the instance

![Launch Instance](http://i.imgur.com/hl79gQE.png)

- Select windows free tier eligible
 
![Microsoft Windows](http://i.imgur.com/jRRh95Y.png)

- Do the following steps

![Instance Type](http://i.imgur.com/pOhWI9c.png)

![Instance Details](http://i.imgur.com/8yx1dX3.png)

![Add Storage](http://i.imgur.com/xJ5rug0.png)

![Tag Instance](http://i.imgur.com/PWI8FId.png)

![Configure security group](http://i.imgur.com/1YfJxi6.png)

![Review Instance](http://i.imgur.com/eI7C24u.png)

![Key Pair#1](http://i.imgur.com/hSGjru2.png)


- If you already have the key pair with the same name it would not allow you to download the key pair.Use a different name

![Error Key Pair](http://i.imgur.com/o88I3ZO.png)

![Key Pair#2](http://i.imgur.com/hzXsFyP.png)


- View the instance

![View Instance](http://i.imgur.com/W1OqG51.png)

- Then connect the instance with the remote desktop

![Connect](http://i.imgur.com/8kvAEBW.png)

![Get Password](http://i.imgur.com/Gw6amOk.png)

![Browse Key Pair#2](http://i.imgur.com/JDexd1u.png)

![Open Key Pair#2](http://i.imgur.com/BqrflnX.png)

![Decrypt PW](http://i.imgur.com/bqoUbTc.png)

- Copy the password and close the pop up window

![Copy PW](http://i.imgur.com/JTSdxF8.png)

- Go to start menu and search Remote desktop connection.
- Enter the **Public** **IP** and connect.

![Select Remote Desktop](http://i.imgur.com/495GPNx.png)

- Enter **user** **name**(Administrator) and **password**(decrypted password)

![Remote Login](http://i.imgur.com/LSoumH5.png)

![Warning Message](http://i.imgur.com/vq9EnrP.png)

- Remote Desktop

![Remote Desktop](http://i.imgur.com/JQI5TXc.png)

- After completing the process, we need to terminate the instance

![Termination](http://i.imgur.com/QWhparW.png)

![Warning message](http://i.imgur.com/kwvZCXJ.png)

![Instance Terminated](http://i.imgur.com/zbwbLmB.png)

##Exercise 3##
###********** Launch Linux instance **********###
- After login to the AWS site select EC2 from Amerzon Web Services

![EC2](http://i.imgur.com/8sOeyHS.png)

- Launch the instance

![Launch Instance](http://i.imgur.com/hl79gQE.png)

- Select Linux free tier eligible

![Select Linux](http://i.imgur.com/EOG028P.png)

- Do the following steps

![Instance Type](http://i.imgur.com/pOhWI9c.png)

![Instance Details](http://i.imgur.com/8yx1dX3.png)

![Add Storage](http://i.imgur.com/yQUFzMT.png)

![Tag Instance](http://i.imgur.com/PWI8FId.png)

![Configure Security Group](http://i.imgur.com/7X05kKL.png)

![Review Launch](http://i.imgur.com/eLg4rBB.png)

- Download the key pair and launch the instance

![Key Pair#1](http://i.imgur.com/hSGjru2.png)

- View the instance

![view Instance](http://i.imgur.com/W1OqG51.png)

![running Instance](http://i.imgur.com/VABL1Ru.png)

- Now install **Putty** and **PuttyGen(Beta version)** softwares to your PC.
- Open **PuttyGen** Software.

![Putty Gen](http://i.imgur.com/SpZMo10.png)

- Select **Load** and open **.pem** file to the software.

![Load](http://i.imgur.com/s6K7nFX.png)

![open .pem](http://i.imgur.com/wcjRQVt.png)

- Then Save it as a **Private** **Key**.

![Save Private Key](http://i.imgur.com/O56mSgU.png)

![Save PK](http://i.imgur.com/ZVxdEpx.png)

- Open **Putty** **configuration** software
- Set **Public** **IP** as the IP Address.

![Putty](http://i.imgur.com/RL87lm4.png)

- From Catogory navigation panel select **Connection****->**SSH**->****Auth**
- Browse key(.ppk) and open it.

![Open console](http://i.imgur.com/YQvNk9l.png)

- Then Linux console will appear. Logged as **ec2-user**.

![Console](http://i.imgur.com/irnhXT1.png)

- After completing the process, we need to terminate the instance

![Instance Termination](http://i.imgur.com/QWhparW.png)

![Warning Message](http://i.imgur.com/h1rBhwj.png)

![Terminated](http://i.imgur.com/EVkH4dW.png)
