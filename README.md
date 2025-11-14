
# Watch the Video of me Creating Users and Groups in Active Directory HERE:

https://www.loom.com/share/bdbb5d1bf03146aebb802c549ad08960

# Creating Users and Groups in Active Directory

This lab guides you through creating new users and groups within an Active Directory (AD) domain using **Active Directory Users and Computers (ADUC)**.

---

## Prerequisites
- Active Directory Domain Services installed  
- Access to **Active Directory Users and Computers** with appropriate permissions  
- Logged into the **testing.local** domain controller  

---

## Steps

### 1. Open Active Directory Users and Computers
1. In the Windows search bar, type **Active Directory Users and Computers**.
2. Open the application.

---

### 2. Navigate to the Domain Structure
1. In the left pane, expand the **testing.local** domain.
2. Select the **Users** folder.

---

## Creating a User

### 3. Create a New User
1. Right-click the **Users** folder.
2. Select **New → User**.

### 4. Enter User Details
1. Fill in the required fields (First Name, Last Name, User Logon Name, etc.).
2. Click **Next**.

### 5. Set a Password
1. Assign a **secure password** for the new user.
2. Check the box for **Password never expires** (if required by your lab instructions).
3. Click **Next**, then **Finish**.

### 6. Verify User Creation
1. Scroll through the **Users** folder.
2. Confirm the new account appears in the list.

---

## Creating a Group

### 7. Create a New Group
1. In the **Users** folder, right-click an empty area.
2. Select **New → Group**.
3. Provide a name for the group.
4. Configure group scope/type as needed (default settings are fine for the lab).
5. Click **OK**.

---

## Completion
You have successfully created:
- A new **user** in Active Directory  
- A new **security group** within the Users container  

Your AD environment is now updated with the specified objects.

