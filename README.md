# Azure - Role-Based-Access-Control
Role-Based Access Control Student Lab

In this exercise, you will complete the following tasks:

Task 1: Use the Azure portal to create a user account for Joseph Price.

Task 2: Use the Azure portal to create a Senior Admins group and add the user account of Joseph Price to the group.

### 1️⃣ **Use the Azure portal to create a user account for Joseph Price**
In this task, you will create a user account for Joseph Price.

1. Start a browser session and sign-in to the Azure portal https://portal.azure.com/
2. In the Search resources, services, and docs text box at the top of the Azure portal page, type Microsoft Entra ID and press the Enter key.

<img width="551" height="161" alt="image" src="https://github.com/user-attachments/assets/3e107b19-9edb-4db3-a230-ff8f7e576e34" />

3. On the Overview blade of the Microsoft Entra ID tenant, in the Manage section, select Users, and then select + New user.
4. On the New User blade, ensure that the Create user option is selected, and specify the following settings:
   
<img width="448" height="614" alt="image" src="https://github.com/user-attachments/assets/8eab91f6-99c3-49dc-8eb2-5c537311c46f" />

5. Click on the copy icon next to the User name to copy the full user.
6. Ensure that the Auto-generate password is selected, select the Show password checkbox to identify the automatically generated password. You would need to provide this password, along with the user name to Joseph.
7. Click Create.
8. Refresh the **Users,	All users** blade to verify the new user was created in your Microsoft Entra tenant.
<img width="1005" height="365" alt="image" src="https://github.com/user-attachments/assets/565a6e84-6b65-4fb8-91ff-d4001dbaad6a" />

### 2️⃣ **Use the Azure portal to create a Senior Admins group and add the user account of Joseph Price to the group.**

In this task, you will create the Senior Admins group, add the user account of Joseph Price to the group, and configure it as the group owner.

1. In the Azure portal, navigate back to the blade displaying your Microsoft Entra ID tenant.
2. In the Manage section, click Groups, and then select + New group.
3. On the New Group blade, specify the following settings (leave others with their default values):

<img width="689" height="556" alt="image" src="https://github.com/user-attachments/assets/f15575d7-efdf-4939-a9e3-ce1a92c6688b" />

4. Click the No owners selected link, on the Add owners blade, select Joseph Price, and click Select.
5. Click the No members selected link, on the Add members blade, select Joseph Price, and click Select.
6. Back on the New Group blade, click Create.

### 3️⃣ **Create a Junior Admins group containing the user account of Isabel Garcia as its member.**

In this exercise, you will complete the following tasks:

Task 1: Use PowerShell to create a user account for Isabel Garcia.

Task 2: Use PowerShell to create the Junior Admins group and add the user account of Isabel Garcia to the group.

1. Open the Cloud Shell by clicking the Cloud Shell icon in the top-right corner of the Azure portal.
2. If prompted, set up Cloud Shell by creating a storage account. This is required only the first time you launch Cloud Shell.
3. In the Cloud Shell pane, ensure PowerShell is selected from the drop-down menu in the upper-left corner.
4. In the PowerShell session within the Cloud Shell pane, run the following to create a password profile object:

<img width="688" height="24" alt="image" src="https://github.com/user-attachments/assets/c9942ae1-eac5-472d-8c6e-59c442a4423f" />

5. In the PowerShell session within the Cloud Shell pane, run the following to set the value of the password within the profile object:

<img width="387" height="18" alt="image" src="https://github.com/user-attachments/assets/ec19a330-1d19-4065-a851-27b47b5c2b04" />

6. In the PowerShell session within the Cloud Shell pane, run the following to connect to Microsoft Entra ID:

<img width="138" height="15" alt="image" src="https://github.com/user-attachments/assets/ad934a47-aa36-462a-ae07-0757b31add9b" />

7. In the PowerShell session within the Cloud Shell pane, run the following to identify the name of your Microsoft Entra tenant:

<img width="598" height="20" alt="image" src="https://github.com/user-attachments/assets/434ceb4c-d82f-40ba-a047-2f3b0e13fd91" />

8. In the PowerShell session within the Cloud Shell pane, run the following to create a user account for Isabel Garcia:

<img width="1481" height="17" alt="image" src="https://github.com/user-attachments/assets/c2dbb94d-fa9d-4904-85a4-496ef98ccfc3" />

9. In the PowerShell session within the Cloud Shell pane, run the following to list Microsoft Entra ID users (the accounts of Joseph and Isabel should appear on the listed):

<img width="791" height="18" alt="image" src="https://github.com/user-attachments/assets/954e2542-6db1-4adf-b504-781da36008e7" />

4️⃣ Use PowerShell to create the Junior Admins group and add the user account of Isabel Garcia to the group.

In this task, you will create the Junior Admins group and add the user account of Isabel Garcia to the group by using PowerShell.

1. In the same PowerShell session within the Cloud Shell pane, run the following to create a new security group named Junior Admins:

<img width="1120" height="23" alt="image" src="https://github.com/user-attachments/assets/cd588f36-2281-4133-b7f6-1fef9da1d775" />

2. In the PowerShell session within the Cloud Shell pane, run the following to list groups in your Microsoft Entra tenant (the list should include the Senior Admins and Junior Admins groups)

<img width="1114" height="21" alt="image" src="https://github.com/user-attachments/assets/7c5ca936-2990-4893-a2a0-00791d65cbd7" />

3. In the PowerShell session within the Cloud Shell pane, run the following to obtain a reference to the user account of Isabel Garcia:

<img width="885" height="22" alt="image" src="https://github.com/user-attachments/assets/2de322e4-e131-46e7-8e0d-6bb92e08388f" />

4. In the PowerShell session within the Cloud Shell pane, run the following to add the user account of Isabel to the Junior Admins43846135 group:




