# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

### NAME: Sherlin Jenifa VS
### REG NO: 212225230263

# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
### a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3. 

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard. 

Step 3: Create Bucket Click the Create bucket button. 

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access. 

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none). 

Step 9: Advanced Settings (optional) Add tags, configure logging, etc. 

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

### b) Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

### c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

### d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances.
Select your instance → Instance State → Terminate.


# Output:

## Creating S3 Bucket:

<img width="1787" height="853" alt="Screenshot 2026-09-11 102602" src="https://github.com/user-attachments/assets/874d9a54-63f5-43bb-93d5-2825b9f46508" />


## Uploading Files in Bucket:

<img width="1793" height="852" alt="Screenshot 2026-09-11 103747" src="https://github.com/user-attachments/assets/43629a73-d176-4cc4-a8d3-b25615e9de90" />



## Launching EC2 Instance:

<img width="1818" height="868" alt="Screenshot 2026-09-11 104314" src="https://github.com/user-attachments/assets/019aeaa6-5cb2-4981-a15c-e790041e62e5" />



## Connecting Instance:

<img width="1654" height="783" alt="Screenshot 2026-09-11 105025" src="https://github.com/user-attachments/assets/cafee1e4-8e60-464e-87fc-bf0d4c9c9f65" />

<img width="1354" height="565" alt="Screenshot 2026-09-11 105409" src="https://github.com/user-attachments/assets/5596d9d3-6a5f-4184-85e2-68bcc68a9f25" />



## Stopping the Instance:

<img width="1649" height="790" alt="image" src="https://github.com/user-attachments/assets/a0f8fbf5-983a-4f1d-b6db-a5139cd3d90b" />



# Result:

Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
