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

## OUTPUT
<img width="1917" height="930" alt="image" src="https://github.com/user-attachments/assets/47728d63-44c2-4d60-9c6d-662f5db8b160" />

<img width="1916" height="922" alt="image" src="https://github.com/user-attachments/assets/d7d9bb7f-e113-44c9-bbb5-a41117cf8ee5" />


 ## RESULT
 The AWS account was successfully created, with set up for the root user. Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
 

  


