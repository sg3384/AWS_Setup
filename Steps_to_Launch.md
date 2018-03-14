# Easy Steps to Launch when in AWS Set up

Tip:
Avoid using Chrome.
Prefer using Mozilla, Safari or Internet Explorer.

### 1. In The EC2 dashboard, choose "launch Instance". 

( https://console.aws.amazon.com/ec2/ )

### 2. Configure your instance:

2.1. Choose an Amazon Machine Image (AMI): recommended: Amazon Linux AMI (free tier eligible)

2.2. Choose instance type: recommended: t2.micro (free tier eligible)

2.3. Choose security Group: Select -> MY IP [so that only you have access to your instance and data ] , and then HTTPS

2.4. Launch Instance: Review and Launch your instance.

### 3. Create a key pair: 

(create a new one or used a old one). It takes a few minutes to launch your instance. 
Have patience. It getting a virtual machine set up for you.

### 4. Connect to your instance:
     
4.1. Select the EC2 instance you created and choose "Connect".

4.2. You should have your key to access your instance.

4.3. Select "A Java SSH client directly from my browser". Ensure Java is installed and enabled.

4.4. Enter the Private key path (example: C:\KeyPairs\my-key-pair.pem).

4.5. Choose "Launch SSH Client".

### 5. Terminate instances:
           
Action -> Instance State -> Terminate
