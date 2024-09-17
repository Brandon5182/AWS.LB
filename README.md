<h1>AWS - Disk Sanitization</h1>


<h2>Description</h2>
In this assignment, I will demonstrate how to create a Load balancer in AWS by creating two EC2 instances. After I create a target group, link the two EC2 instances to the target, and associate them with a load balancer. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>AWS</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Create your first EC2 and name the instance "Bswebserver01" and select your AMI: <br/>
<img src="https://i.imgur.com/XzCRAPk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select your Security group and allow your EC2 to accept HTTP, HTTPS and SSH traffic:  <br/>
<img src="https://i.imgur.com/GlDg4ys.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Watch Video for description and Launch Instnace: <br/>
<img src="https://i.imgur.com/QjXJDB2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a new instance using the first EC2 instances as a template and name it "BsWebserver02":  <br/>
<img src="https://i.imgur.com/geXlqHY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
