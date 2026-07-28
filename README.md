# CREATE AN  ACCOUNT IN AWS SET UP A ROOT USER AND AN IAM USER 
### Name: SURYANARAYANAN T
### Reg Number: 212224040341
## AIM
To Create an Account in AWS Set up a Root user and an IAM user.
## PROBLEM STATEMENT
This experiment involves creating an AWS account, configuring security settings for the root user, and setting up an IAM user. IAM users allow for secure, managed access to AWS resources without exposing the main account's root credentials.
## ALGORITHM
 ### Step 1: Create an AWS Account
- Visit the AWS website.
- Click **Create an AWS Account**.
- Enter your email address, account name, and password.
- Verify your email, provide contact and payment details, and complete identity verification.
- Sign in to the **AWS Management Console**.

### Step 2: Sign in as the Root User
- Log in using the email address and password registered during account creation.
- The **Root User** has complete administrative access to all AWS resources.
- Use the root account only for critical account management tasks.

### Step 3: Enable Multi-Factor Authentication (MFA)
- Open the **IAM Dashboard** and navigate to **Security Credentials**.
- Select **Assign MFA Device**.
- Configure an authenticator app or hardware MFA device.
- Verify the setup to enhance the security of the root account.

### Step 4: Create an IAM User
- Navigate to **IAM → Users → Create User**.
- Enter a username (e.g., `adminuser`).
- Choose the required permissions by attaching policies or adding the user to a group.
- Create the user and securely save the login credentials.

### Step 5: Sign in with the IAM User
- Open the AWS IAM sign-in URL.
- Log in using the IAM username and password.
- Use the IAM user for daily AWS operations.
- Reserve the root user account for administrative and account-level tasks only.

## OUTPUTS
### AWS Management Console – Root User Login
<img width="1920" height="1080" alt="Screenshot 2026-07-28 091907" src="https://github.com/user-attachments/assets/67cde911-09b0-425f-83e5-6fa7fa2c6844" />

### IAM User Created
<img width="1920" height="1080" alt="Screenshot 2026-07-28 092028" src="https://github.com/user-attachments/assets/49826a15-1a46-4551-944d-0f30ba9b930f" />

### IAM User Permissions
<img width="1920" height="1080" alt="Screenshot 2026-07-28 092249" src="https://github.com/user-attachments/assets/49c941a6-2f26-4c60-8440-91c2fd68a8f7" />
<img width="1920" height="1080" alt="Screenshot 2026-07-28 092344" src="https://github.com/user-attachments/assets/905eacd6-d5c6-442c-ae51-e503a60feb33" />
<img width="1920" height="1080" alt="Screenshot 2026-07-28 092453" src="https://github.com/user-attachments/assets/6a4ae1aa-4e40-4111-aa0a-39991524f1aa" />

### IAM User Successfully Logged In
<img width="1920" height="1080" alt="Screenshot 2026-07-28 093014" src="https://github.com/user-attachments/assets/d3f05d5d-7ebd-40dc-8e99-8795909117de" />
<img width="1920" height="1080" alt="Screenshot 2026-07-28 093151" src="https://github.com/user-attachments/assets/350d9ae8-792e-4a7c-a548-43aaae214b51" />





 ## RESULT
 The AWS account was successfully created, with set up for the root user. Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
 

  


