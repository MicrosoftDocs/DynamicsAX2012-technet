---
title: Unapprove a formula version
TOCTitle: Unapprove a formula version
ms:assetid: 284b97c0-1b81-422a-aa10-7622a63827ec
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352190(v=AX.60)
ms:contentKeyID: 36687823
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Unapprove a formula version 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to remove an approval status from a formula version.


> [!NOTE]
> <P>If the <STRONG>Block removal of approval</STRONG> check box is selected on the <STRONG>General</STRONG> tab in the <STRONG>Production control parameters</STRONG> form, you cannot change the approval status of an approved formula.</P>



1.  Click **Inventory and warehouse management** \> **Common** \> **Formula**.

2.  Select the formula with the formula version to be unapproved.

3.  In the **Versions** section, verify that the desired formula version is selected.

4.  Select the formula version to unapprove.

5.  To unapprove the formula version, click the **Approve** button.

6.  From the **Approved by** list, select the worker who is removing the approval status from the formula version.

7.  Select the **Remove approval** check box.

8.  Click **OK**.
    

    > [!NOTE]
    > <P><SPAN id=q></SPAN>If a user is set up to require electronic signature, a <STRONG>Signature</STRONG> form is displayed after you clear the <STRONG>Approval</STRONG> status. You must be authorized to sign electronically and the certificate must be successfully validated for the change to be committed. If your signature cannot be authenticated, the request to remove approval is denied and the change that initiated it is returned to its original state.</P>



## See also

[Formula (form)](https://technet.microsoft.com/en-us/library/hh328668\(v=ax.60\))

[Production control parameters (form)](https://technet.microsoft.com/en-us/library/aa498700\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

