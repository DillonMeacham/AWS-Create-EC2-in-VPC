<h1>Launch an EC2 Instance in a VPC</h1>

<h2>Description</h2>
In this project, Alfredo of Alfredo's Pizza is looking to set up a website to advertise his business. To help him out, I created a custom virtual private cloud (VPC), subnets across multiple Availability Zones (AZs), routes and an internet gateway, as well as adding a security group. <br />


<h2>Environments Used </h2>

- <b>AWS Management Console</b>

<h2>Project walk-through:</h2>

<p align="center">
Setting up the VPC: <br/>
<img src="https://imgur.com/UjxZ78c.png" height="80%" width="80%" />
<br />
<br />
Creating Public Subnet for VPC:  <br/>
<img src=https://imgur.com/qz053og.png" height="80%" width="80%"
<br />
<br />
Creating Internet Gateway: <br/>
<img src="https://imgur.com/e6pV03q.png" height="80%" width="80%"
<br />
<br />
Attaching Gateway to VPC:  <br/>
<img src="https://imgur.com/zJfhK21.png" height="80%" width="80%"
<br />
<br />
Creating Route Table:  <br/>
<img src="https://imgur.com/4rNx9UK.png" height="80%" width="80%"
<br />
<br />
Adding Route Table to communicate with the Public Internet:  <br/>
<img src="https://imgur.com/tOTPv1e.png" height="80%" width="80%"
<br />
<br />
Associating Route with Public Subnet:  <br/>
<img src="https://imgur.com/Ehd3DbQ.png" height="80%" width="80%"
<br />
<br />
Setting up a new EC2 Instance:  <br/>
<img src="https://imgur.com/8disYTE.png" height="80%" width="80%"
<br />
<br />
Connecting to EC2 Instance:  <br/>
<img src="https://imgur.com/NW1h6v5.png" height="80%" width="80%"
<br />
<br />
Connected to EC2 Instane Successfully:  <br/>
<img src="https://imgur.com/s6Ma5BF.png" height="80%" width="80%"
</p>
