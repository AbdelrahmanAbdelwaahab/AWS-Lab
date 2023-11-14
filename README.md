<h1>Configuring Kali Linux as an EC2 instance in AWS</h1>

<h2>Description</h2>
Unlock the world of ethical hacking with our step-by-step guide on configuring Kali Linux as an EC2 instance in AWS! 🌐🔐

Empower your ethical hacking journey by setting up a dynamic hacking lab in the cloud. This repository provides detailed instructions and scripts to seamlessly deploy Kali Linux on an AWS EC2 instance. Dive into the world of penetration testing and cybersecurity from anywhere, harnessing the flexibility and power of cloud computing.
<br />

<h2>Steps walk-through:Here's where the adventure begins</h2>

<p align="center">

Open AWS Account: Log in <br />
(1)Navigate to Services. <br />
(2) Select EC2: Click on EC2 to enter the realm where Kali Linux will come to life!: <br/>
<img src="https://github.com/AbdelrahmanAbdelwaahab/AWS-Lab/assets/150354821/419cef36-830f-4838-a813-4519bf6f5746" height="80%" width="80%" alt="Login to AWS, navigate to services then click on EC2"/>
<br />
<br />
Once inside EC2, locate and click on "Launch Instance."  <br/>
<img src="https://github.com/AbdelrahmanAbdelwaahab/Anythinglabb/assets/150354821/79d4ba56-5017-4e24-8661-5ed0a53d2c4a" height="80%" width="80%" alt="Creating the Instance"/>
<br />
<br />
<h3>Let's tailor your Kali Linux machine to your specifications:</h3>

(1) Name Your Machine: Give your hacking lab a distinct identity by assigning it a name.<br/>
(2) Search for Kali Linux: Type "kali linux" in the search box and press "ENTER". <br/>
<img src="https://github.com/AbdelrahmanAbdelwaahab/AWS-Lab/assets/150354821/a33d444a-6bbd-4da8-a7cf-291d97144f72" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>Let's pinpoint Kali Linux in the AWS Marketplace</h3>
(1) Explore AWS Marketplace AMIs: Click on "AWS Marketplace AMIs"  <br/>
(2) Locate and Select Kali Linux <br/>
<img src="https://github.com/AbdelrahmanAbdelwaahab/AWS-Lab/assets/150354821/1043f93e-c898-4e0e-906d-ba8650529fe8" height="80%" width="80%" alt="Searching for Kali Linux in the search box"/>
<br />
<br />


<h3> By selecting Kali we will get back automatically to the configuration page, so lets resume our configuration baking </h3>
(1)Adjust Instance Type: Opt for the T2 Micro instance type image -it's within the free tier, aligning perfectly with your budget-friendly hacking lab. 
<br />
(2)Click on "Create Key Pairs".<br/>
<img src="https://github.com/AbdelrahmanAbdelwaahab/AWS-Lab/assets/150354821/3c58e40e-a69e-4ed9-ae54-31b27b7702cb" height="80%" width="80%" alt="Adjusting instance type to t2 micro to save the costs of AWS"/>
<br />
<br />
<h3> Name Your Key Pair </h3>
(1) Name Your Key Pair: Choose a distinctive name for your key pair - in this example, it's named "Lord Sauron." <br />
(2) Click on "Create Key Pair." The key pair file will automatically download to your PC. <br />

<img src="https://github.com/AbdelrahmanAbdelwaahab/Anythinglabb/assets/150354821/13862177-c742-4803-befb-0ffa4ea65b34" height="80%" width="80%" alt="Naming the key pair and saving it to the PC"/>
<br />
<br />

Remember, guard this key pair like the One Ring! Store it securely as it's your ticket to connect with your Kali machine via SSH. Losing it could be as perilous as losing the One Ring to Mordor.
Sanitization complete:   <br/>
<img src="https://www.denofgeek.com/wp-content/uploads/2020/03/Lord-of-The-Rings-Amazon.jpg?resize=768%2C432" height="80%" width="80%" alt="The Ring inspired from Lord of The Rings"/>
<br />
<br />

<h3>With the key pair secured, let's kick off the building process: </h3>
Back to Configuration: After creating the key pair, you'll be automatically redirected to the configuration page. <br />
Launch Instance: Click on "Launch Instance" to initiate the construction of your Kali Linux machine. <br />
Now, sit back, relax, and give it a moment. Your hacking lab is in the making! 🚀💻
Sanitization complete:   <br/>
<img src="https://github.com/AbdelrahmanAbdelwaahab/Anythinglabb/assets/150354821/0e11ddf5-3810-45f7-82a5-14de375c1679" height="80%" width="80%" alt="Creating the instance"/>
<br />
<br />

<h3>Your Kali Linux instance is now ready for action: </h3>
(1) Browse from EC2 Service: Navigate to the EC2 service to find your freshly baked Kali Linux instance. <br />
(2) Ready to Use: Your instance is now fully operational and ready for your ethical hacking experiments! <br />
A friendly reminder: To keep your hacking lab budget-friendly, don't forget to stop the instance when not in use. Happy ethical hacking! 🌐💻<br/>
<img src="https://github.com/AbdelrahmanAbdelwaahab/AWS-Lab/assets/150354821/1da1e153-66ef-49e5-bd82-528033b982a8" height="80%" width="80%" alt="Acess your Kali machine, and keeping things budget friendly"/>
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
