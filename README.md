<h1>AWS - Load-Balancer</h1>


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
Select the key pair and configure the network setting:  <br/>
<img src="https://i.imgur.com/loEDy6n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
watch video for description and launch instance:  <br/>
<img src="https://i.imgur.com/7wvuHU2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe both instances and make sure they're running:  <br/>
<img src="https://i.imgur.com/0zToFW4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create your target group and specify your group details:  <br/>
<img src="https://i.imgur.com/y2PTX9h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Register your targets by adding your instance to the target group:  <br/>
<img src="https://i.imgur.com/7l9JM7J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
<br />
Link your target group to a new load balancer:  <br/>
<img src="https://i.imgur.com/UK0EntH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
<br />
Create your Load Balancer and configure your network mapping by selecting AZ's:  <br/>
<img src="https://i.imgur.com/UB57K5y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
<br />
Select your Target Group:  <br/>
<img src="https://i.imgur.com/g1ZmhIS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
<br />
Run a health check:  <br/>
<img src="https://i.imgur.com/ziYIJ2Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
<br />
The load balancer is complete:  <br/>
<img src="https://i.imgur.com/1ie1z09.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
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
