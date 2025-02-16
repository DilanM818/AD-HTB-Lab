# Basic AD Administration-HTB LAB

# Scenario
You are a domain administrator for a day and has been tasked to help the IT department close some work orders. You will be performing actions such as adding and removing users and groups, managing group policy, adding a new computer to the proper domain, and apply a modified Group Policy already in GPMC.

# Requirements
##### 🔸Users
-Andromeda Cepheus
<br />
-Orion Starchaser
<br />
-Artemis Callisto
<br />
##### 🔸User Attributes
-Full Name
<br />
-Email (first-initial.lastname@inlanefreight.local)
<br />
-Display Name
<br />
-User must change password at next logon
<br />

# Tasks
-Add new users into AD
<br />
-Remove a few old and inactive users
<br />
-Unlock a user since they've locked themselves out
<br />
-Create a new security group for the new users and a new OU for the group and corresponding PCs
<br />
-Add newly provisioned computer for a new user to the domain. Validate their objects are correct.
<br />

# Adding Users
#### 🔸Powershell
![image](https://github.com/user-attachments/assets/07fd3fa1-cf5d-414f-841b-44be65811688)
#### 🔸ADUC
![image](https://github.com/user-attachments/assets/33e9c477-97ab-41c7-9b2d-0d1443c014c7)

![image](https://github.com/user-attachments/assets/4f4c474d-467b-4572-ac3d-61efce6bdde6)

![image](https://github.com/user-attachments/assets/6280e923-63f2-428a-964c-14f3cc9fe97e)

# Removing Users
#### 🔸Powershell
![image](https://github.com/user-attachments/assets/101b4d0c-e78a-42e1-a8dd-1faea818cb9b)
#### 🔸ADUC
![image](https://github.com/user-attachments/assets/4dfee315-212e-4bcb-923e-8ca9201e450b)

# Unlock Account & Force password change at Logon
#### 🔸Powershell
![image](https://github.com/user-attachments/assets/515aa695-f227-41ed-96e3-90a1b2e6b21c)
#### 🔸ADDUC
![image](https://github.com/user-attachments/assets/18dfecda-39fe-41d9-8424-907616e8a14b)

# Creating and Verifying a Security Group
#### 🔸Powershell
![image](https://github.com/user-attachments/assets/d43b6a49-f88d-4a4f-9af1-933b297665da)

![image](https://github.com/user-attachments/assets/c803f83e-70d0-4630-9ecb-c84503bdc074)

![image](https://github.com/user-attachments/assets/2e790f3d-ddc5-4d67-8f7d-0a40e0224f9b)

#### 🔸ADUC
![image](https://github.com/user-attachments/assets/98baeb8e-9698-421a-a411-1e69b918b796)

![image](https://github.com/user-attachments/assets/26ce8ed9-ad9e-4d39-b7cd-75527efcf348)

![image](https://github.com/user-attachments/assets/5976313c-2848-4adc-ab2c-1bdb967ca28d)

![image](https://github.com/user-attachments/assets/5d95345a-5dc5-4774-87f2-17b3c8582f31)

# Manage Group Policy Objects
#### 🔸Copy GPO to another GPO with a different name
![image](https://github.com/user-attachments/assets/3d1e1203-9f27-4b3b-8c5b-58eeb51fd421)

#### 🔸Link Existing GPO to specified OU path and ensure GPO is enabled
![image](https://github.com/user-attachments/assets/5c58fbc0-c6e8-4815-924a-02a284ad56f9)

#### 🔸New Users will require access to CMD/Powershell
![image](https://github.com/user-attachments/assets/3a1ccb8d-6124-41e0-a6d3-9f41d88f98f4)

#### 🔸Verify Logon Banner is enabled
![image](https://github.com/user-attachments/assets/6e99be74-c149-4ddf-b0eb-2b963ffc0252)

![image](https://github.com/user-attachments/assets/bb43672b-4859-4ada-a73a-680579c3ca3d)

![image](https://github.com/user-attachments/assets/0621579e-4fca-4280-9b8e-eb1554e99ef5)

#### 🔸Disable USB access 
![image](https://github.com/user-attachments/assets/450c4561-e3a3-455c-862d-3c2a884632b8)

#### 🔸Strengthen Password Policy
![image](https://github.com/user-attachments/assets/b28b43ac-bb42-4230-a76b-c9256718b959)

# Adding a Computer to the Domain
#### 🔸Powershell
###### Host Computer
![image](https://github.com/user-attachments/assets/51f1da3e-5c50-48ca-8f50-307a1602c3a2)

#### 🔸Verified on Domain Controller
![image](https://github.com/user-attachments/assets/8e629b35-f0b1-4a7e-bbd2-d7eeb1c6d233)

##### 🔸ADUC
###### Host Computer
![image](https://github.com/user-attachments/assets/57be6327-88e9-4bc6-b104-fe61a0267fb4)

#### 🔸Verified on Domain Controller
![image](https://github.com/user-attachments/assets/f5551add-03c2-4faf-9a31-416cf38cfc2f)

# Move Computer Object to the new OU
![image](https://github.com/user-attachments/assets/215f8e5a-90ff-4668-9453-13ebeaca1772)

#### 🔸Verified Computer Object has been moved
![image](https://github.com/user-attachments/assets/bcdb1295-35b0-4f83-8af7-e4f6d1ad2014)

# Key Takeaways
-Learning how to use programs for AD administration such Active Directory Users and Groups and Group Policy Management Console
<br />
-Gain familiarity using Powershell cmdlets in addition to GUI
<br />
-Verify changes have been made either through Powershell or ADUC
<br />
-Implement minimum AD hardening via Group Policies

