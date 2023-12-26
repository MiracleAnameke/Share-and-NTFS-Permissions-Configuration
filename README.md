# Share and NTFS Permissions Configuration

## Lab Overview

This lab involves setting up DHCP, configuring shared folders on Server 2008, and managing NTFS permissions. It encompasses creating department-specific folders, managing user accounts, and ensuring appropriate access controls.

## Preparation

- Use Server 2008 R2 VM and Windows 7 or 10 VM.
- Ensure NICs are configured correctly.
- Run `slmgr /rearm` on both VMs to avoid activation warnings.

## Lab Tasks and Screenshots

### 1. Add DHCP

Set up and configure DHCP with the designated network scope and settings. 

- **Screenshot 1**: Capture of DHCP and Network Policy settings.

  
  <img src="https://i.imgur.com/XRAtfJ4.png" height="400px" width="auto" alt="DHCP Configuration"/>

### 2. Configuring Share folders on Server 2008

Create and configure shared folders, setting up both Share level and NTFS permissions.

- **Slide 2a, 2b, 2c**: Capture settings, shared folders, and access levels.

  
  <img src="https://i.imgur.com/IzQ1ZdQ.png" height="400px" width="auto" alt="Shared Folder Configuration"/>
  <img src="https://i.imgur.com/VWvqah9.png" height="400px" width="auto" alt="Shared Folder Configuration"/>
  <img src="https://i.imgur.com/9WzKQe7.png" height="400px" width="auto" alt="Shared Folder Configuration"/>


### 3. User Accounts and Access Control
 
Create user accounts for department managers and workers. Configure access controls to ensure departmental integrity and data security.

## Slide 3 Explanation: Departmental Share Permissions

### HR Department:
- **Manager (John)**: Full control over HR, read-only for other departments.
- **Worker (Emma)**: Modify and write access to "Employee_Records."
- **Worker (David)**: Modify and write access to "Payroll."

### Marketing Department:
- **Manager (Susan)**: Full control over Marketing, read-only for other departments.
- **Worker (Lisa)**: Modify and write access to "Campaigns."
- **Worker (Paul)**: Modify and write access to "Research."

### Finance Department:
- **Manager (Michael)**: Full control over Finance, read-only for other departments.
- **Worker (Sarah)**: Modify and write access to "Budgets."
- **Worker (James)**: Modify and write access to "Invoices."

  
 **Slide 3**: Capture all folders and access privileges of each department.


  <img src="https://i.imgur.com/vOiAeal.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/2WgssTL.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/jvHhtbX.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/P4bYxex.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/5zaIrzm.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/brc4o1j.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/gsn7zc6.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/MxUaGSz.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/TLr3HWi.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/5y8KcJ2.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/VTuVBYA.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/KPX1cLT.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/ZQyL5Tx.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/4j3vHGo.png" height="400px" width="auto" alt="Folder Access Privileges"/>
  <img src="https://i.imgur.com/jgaZO9V.png" height="400px" width="auto" alt="Folder Access Privileges"/>

- **Slide 4**: Proof of managers' access limitations to other departments.
  <img src="https://i.imgur.com/lAOZYNh.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  <img src="https://i.imgur.com/nHDs1ZM.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  <img src="https://i.imgur.com/JccMEOr.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  <img src="https://i.imgur.com/82S0qN7.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  <img src="https://i.imgur.com/vZ3QSUq.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  <img src="https://i.imgur.com/YbPtjQf.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  <img src="https://i.imgur.com/7O0aBx6.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  <img src="https://i.imgur.com/Oj5nqHN.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  <img src="https://i.imgur.com/0DlXQHD.png" height="400px" width="auto" alt="Managers Access Limitations"/>
  

- **Slide 5**: Share permissions for each department folder, with explanation.
  ## Explanation of Sharing Setup

The Share permissions are configured to ensure that workers have the necessary access to fulfill their specific job responsibilities within their assigned subfolders. Managers have Full Control to oversee departmental operations, while workers have Change permissions limited to their areas of responsibility to prevent unauthorized access to other sensitive areas. This setup maintains a high level of data security and integrity by ensuring that only authorized personnel can modify content within their scope of work. Other department managers are granted Read permissions to allow for necessary visibility across departments without compromising the control over departmental resources.

  
  <img src="https://i.imgur.com/JF4zTEY.png" height="400px" width="auto" alt="Department Share Permissions"/>
  <img src="https://i.imgur.com/MkLIhL4.png" height="400px" width="auto" alt="Department Share Permissions"/>
  <img src="https://i.imgur.com/8oIpwZM.png" height="400px" width="auto" alt="Department Share Permissions"/>
  <img src="https://i.imgur.com/onN3j1p.png" height="400px" width="auto" alt="Department Share Permissions"/>
  <img src="https://i.imgur.com/MylUfob.png" height="400px" width="auto" alt="Department Share Permissions"/>
  <img src="https://i.imgur.com/QaSgNiw.png" height="400px" width="auto" alt="Department Share Permissions"/>
  <img src="https://i.imgur.com/R6s5rhf.png" height="400px" width="auto" alt="Department Share Permissions"/>
  <img src="https://i.imgur.com/iJKL35O.png" height="400px" width="auto" alt="Department Share Permissions"/>
  <img src="https://i.imgur.com/IsKElwx.png" height="400px" width="auto" alt="Department Share Permissions"/>
  

### 4. Explicit Deny and Allow Rules

### Why Deny is Not Good to Use

Using "Deny" permissions is generally not recommended because it can create confusion and override any "Allow" permissions, leading to unexpected access issues that can disrupt normal operations and complicate the security structure.

Implement explicit deny and allow rules in the directory structure. Understand the implications of using these permissions.

### Rules for Deny and Allow

#### Deny Rule:
- **Precedence**: Takes precedence over Allow rules. If a user has both denied and allowed permissions, Deny will be enforced.
- **Usage**: Should be used sparingly due to its ability to complicate permission structures.
- **Impact**: Can silently block access even when Allow permissions are set, leading to unexpected access issues.

#### Allow Rule:
- **Granting Access**: Used to grant necessary permissions for users or groups.
- **Principle of Least Privilege**: Align with the principle of least privilege.
- **Simplicity**: Makes the system easier to understand and manage.


 **Slide 6**: Capture folders affected by explicit deny and allow rules, explain the user impact and rules.
  <img src="https://i.imgur.com/gv31Ze2.png" height="400px" width="auto" alt="Explicit Deny and Allow Rules"/>
  <img src="https://i.imgur.com/RMhPxlq.png" height="400px" width="auto" alt="Explicit Deny and Allow Rules"/>
  <img src="https://i.imgur.com/ooMLvgE.png" height="400px" width="auto" alt="Explicit Deny and Allow Rules"/>
  <img src="https://i.imgur.com/ebvmeWh.png" height="400px" width="auto" alt="Explicit Deny and Allow Rules"/>
  

### 5. Testing and Explanation

Log in from Win7 and Win10 workstations to the domain. Test the setup and explain how share and NTFS permissions interact.

- **Slide 7**: Capture setup from workstations, explaining share and NTFS permissions interaction.
  <img src="https://i.imgur.com/H4qzcuc.png" height="400px" width="auto" alt="Permissions Interaction"/>
  <img src="https://i.imgur.com/ebvmeWh.png" height="400px" width="auto" alt="Permissions Interaction"/>
  <img src="https://i.imgur.com/mseJwLf.png" height="400px" width="auto" alt="Permissions Interaction"/>
  <img src="https://i.imgur.com/it7iCnn.png" height="400px" width="auto" alt="Permissions Interaction"/>


###  Explain the way share and NTFS permissions work. Which overrides the other??
**Share Permissions**: Set on shared folders and dictate how resources are accessed over the network. They are simpler, with options like Read, Change, and Full Control.
**NTFS Permissions**: Apply to users and groups for both local and network access. They offer detailed settings, like Read, Write, Modify, and Full Control, and can be applied to both files and folders.

When a user accesses a file over the network, the system checks both Share and NTFS permissions and applies the most restrictive of the two. For example, if Share permissions allow Full Control but NTFS permissions only allow Read, the user will only have Read access. This is because NTFS permissions are more granular and specific, and thus take precedence in restricting access.
