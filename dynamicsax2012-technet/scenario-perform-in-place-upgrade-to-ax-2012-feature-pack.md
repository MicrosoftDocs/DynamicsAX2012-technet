---
title: 'Scenario: Perform in-place upgrade to AX 2012 Feature Pack'
TOCTitle: 'Scenario: Perform in-place upgrade to AX 2012 Feature Pack'
ms:assetid: eadfc86d-fcc0-4c96-aa96-1a58a6e82590
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863522(v=AX.60)
ms:contentKeyID: 50395322
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Scenario: Perform in-place upgrade to AX 2012 Feature Pack [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

An upgrade Microsoft Dynamics AX 2012 to Microsoft Dynamics AX 2012 Feature Pack is an in-place upgrade. Upgrades of this kind differ significantly from source-to-target upgrades, such as the upgrade from Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012. There is no source-to-target workflow. Instead, the installation of a new model file on the existing Microsoft Dynamics AX 2012 system causes the **Software update checklist** to open when the system is restarted. The upgrade is completed by performing the tasks on this checklist.

Complete the following procedures to upgrade to Microsoft Dynamics AX 2012 Feature Pack from a supported Microsoft Dynamics AX 2012 system.


> [!IMPORTANT]
> <P>Before you try to upgrade, make sure that you have the required permissions on the operating system and for Microsoft SQL Server. For more information, see <A href="verify-that-you-have-the-required-permissions-for-installation.md">Verify that you have the required permissions for installation</A>.</P>



## Install the Microsoft Dynamics AX Feature Pack components and models

Use this procedure to add the Retail-related files and metadata to an existing Microsoft Dynamics AX 2012 system.

1.  Close any open clients on your Microsoft Dynamics AX system.

2.  Open the **CD** folder of the Microsoft Dynamics AX 2012 Feature Pack distribution DVD, and navigate to the **updates** folder.

3.  (Skip this step if Cumulative Update 2 (CU2) has previously been installed.) In the **DynamicsAX2012-KB2606916** folder, double-click the **AxUpdate** file to install the update. Specify the correct databases to upgrade, select all the other components that are offered, and then click through the wizard.

4.  (Skip this step if your Microsoft Dynamics AX kernel version is 6.0.947.862 or higher.) In the **DynamicsAX2012-KB2650968** folder, double-click the **AxUpdate** file to install the update. Select all the component updates that are offered, and then click through the wizard.

5.  In the **CD** folder, run Setup.exe.

6.  Under **Install**, click **Microsoft Dynamics AX components**.

7.  Click through the wizard to the **Review license terms** page, select **I accept the license**, and then click **Next**.

8.  On the **Ready to install** page, click **Install** to install setup support files and updates for the support files.

9.  On the **Modify Microsoft Dynamics AX installation** page, select **Add or modify components**, and then click **Next**.

10. On the **Add or Modify Components** page, select **Databases**, and then click **Next**.
    

    > [!WARNING]
    > <P>Do not select any of the Retail components for installation at this point. The system upgrade must be completed before you install the Retail components.</P>



11. On the **Prerequisite Validation** page, satisfy any prerequisites, and then click **Next**.

12. On the **Select databases page**, select **Configure existing databases**, and then click **Next**.

13. On the **Configure existing databases** page, accept or provide the name of the SQL Server computer and the database names, and then click **Next**.

14. On the **Select additional models** page, select **Extensions** and **Extensions Upgrade**, and then click **Next**.

15. On the **Prerequisite Validation** page, satisfy any prerequisites, and then click **Next**.

16. On the **Ready to install** page, click **Install**.

17. When setup has been completed successfully, click **Finish**.

## Update data

Use this procedure to synchronize the Microsoft Dynamics AX databases that have been modified, and to run the required upgrade scripts.

1.  Restart the AOS.

2.  Open the Microsoft Dynamics AX client. If the Extensions and Extensions Upgrade models were installed correctly, a window opens with the message: “The model store has been modified.” Select **Start the software update checklist**, and then click **OK**.
    
    After a brief compile, the **Software update checklist** opens.
    

    > [!NOTE]
    > <P>You can also open the <STRONG>Software update checklist</STRONG> manually. You must open the checklist manually if it fails to start automatically, or if you close the client before you complete the checklist tasks. To open the checklist, click <STRONG>System administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Checklists</STRONG> &gt; <STRONG>Software update checklist</STRONG>.</P>



3.  Complete the following checklist tasks. For more information about these tasks, see the user Help.
    
    1.  **Restart Application Object Server**
    
    2.  **Compile application**
    
    3.  **Detect code upgrade conflicts**
    
    4.  **Compile into .NET Framework CIL**
    
    5.  **Detect upgrade scripts**
    
    6.  **Synchronize database**

4.  Close the client.

## Install Microsoft Dynamics AX 2012 Feature Pack components

To install Retail components on your upgraded Microsoft Dynamics AX 2012 Feature Pack system, follow the instructions in [Install Microsoft Dynamics AX 2012](install-microsoft-dynamics-ax-2012.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

