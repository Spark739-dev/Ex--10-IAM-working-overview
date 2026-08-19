# Ex--6-IAM-working-overview

# AIM

To explore AWS IAM users, groups, and policies, assign users to appropriate groups, and verify how permissions control access to AWS services.

# ALGORITHM

1.Open the AWS Management Console and select IAM.

2.Explore the pre-created IAM users: user-1, user-2, and user-3.

3.Explore the groups: S3-Support, EC2-Support, and EC2-Admin.

4.Check the policies attached to each group.

5.Add user-1 to S3-Support.

6.Add user-2 to EC2-Support.

7.Add user-3 to EC2-Admin.

8.Sign in as each user using the IAM sign-in URL.

9.Test the permissions for S3 and EC2.

10.Verify that each user can perform only the actions allowed by their assigned policy.

# OUTPUT
## OVERVIEW OF IAM

<img width="1918" height="976" alt="1" src="https://github.com/user-attachments/assets/2c506971-efd8-432c-a9e5-4e0be781fb86" />


## IAM USERS

<img width="1918" height="992" alt="2" src="https://github.com/user-attachments/assets/d397c976-5cf7-4190-90bd-cc93dc1b86e4" />


## IAM GROUPS

<img width="1918" height="970" alt="4" src="https://github.com/user-attachments/assets/1c676b3b-9e01-4c39-922e-b084a44a7d1b" />


## USER1
<img width="1918" height="967" alt="3 u1" src="https://github.com/user-attachments/assets/aa94879e-37a8-4d8b-a417-8a2da4cb0666" />

<img width="1918" height="953" alt="5" src="https://github.com/user-attachments/assets/b25c74f4-a3cb-4f05-a2af-1c75c69c736c" />


## USER GROUPS(EC2 SUPPORT)

<img width="1918" height="973" alt="6" src="https://github.com/user-attachments/assets/23ef2351-cea3-49b5-888c-aeb373e716f3" />

<img width="1912" height="966" alt="7" src="https://github.com/user-attachments/assets/0818361d-6578-44a6-a9cf-a88f45175f36" />


## USER GROUPS(S3 SUPPORT)

<img width="1918" height="981" alt="8" src="https://github.com/user-attachments/assets/8ed24c18-b54c-417a-a840-544a9195f771" />

<img width="1918" height="977" alt="9" src="https://github.com/user-attachments/assets/471bdff1-2a25-4e5a-8d07-dabcff35eebf" />


## USER GROUPS(EC2 ADMIN)
<img width="1918" height="968" alt="10" src="https://github.com/user-attachments/assets/fc207912-8fc0-42f2-a1e2-adcc0ea55acd" />

<img width="1918" height="1002" alt="11" src="https://github.com/user-attachments/assets/d69c1412-1dcb-4838-b2ea-385e68ca9d96" />


## ADDING USERS(USER 1->S3 SUPPORT)
<img width="1912" height="1011" alt="12" src="https://github.com/user-attachments/assets/7b245859-6aac-4da1-a26f-48ac005aa1df" />

<img width="1913" height="975" alt="13" src="https://github.com/user-attachments/assets/40b3480b-2c12-45c6-a861-1138101375df" />

## ADDING USERS(USER 2-> EC2 SUPPORT)
<img width="1918" height="966" alt="14" src="https://github.com/user-attachments/assets/9a791d80-7c45-4dd1-a50a-1cc3ccf4c7c1" />

<img width="1918" height="978" alt="15" src="https://github.com/user-attachments/assets/d8b0779e-11ce-49b4-bf1c-cc0b1652b606" />


## ADDING USERS(USER 3-> EC2 ADMIN)
<img width="1907" height="1013" alt="16" src="https://github.com/user-attachments/assets/9187b9c8-e317-4e08-9723-9a9934918166" />

<img width="1917" height="965" alt="17" src="https://github.com/user-attachments/assets/be003c74-2036-4bc5-bbdd-124279eef518" />


## LOG IN USERS ACCOUNT TO CHECK AND TEST ASSIGNED AWS SERVICES(USER 1)




# RESULT

Thus, the AWS IAM users, groups, and policies were successfully explored and configured. The permissions of each user were successfully tested, demonstrating read-only S3 access for user-1, read-only EC2 access for user-2, and EC2 view/start/stop access for user-3
