# **ESBPII** **-** **LAB02** #
----------

###Name : Haputhanthrie J.S###
###ID No : IT13113582###

##Exercise 1##
###********** Login to AWS Account **********###
1. Create your AWS account and login to it.
![Login](http://i.imgur.com/ufbfuRq.png)
##Exercise 2##

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

- Interact with the linux instance.To update the latest packages type **"sudo** **yum** **update"** and press enter. Then confirm the download by pressing **"Y"**.

![Installation](http://i.imgur.com/oBIrh4U.png)

![Installation 2](http://i.imgur.com/uhqX1GN.png)

- Now you can work in this instance as regular linux environment 

![work 1](http://i.imgur.com/dCUlNxv.png)

![work 2](http://i.imgur.com/LTh34S5.png)
 
- After completing the process, we need to terminate the instance

![Instance Termination](http://i.imgur.com/QWhparW.png)

![Warning Message](http://i.imgur.com/h1rBhwj.png)

![Terminated](http://i.imgur.com/EVkH4dW.png)
