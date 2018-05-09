---
title: Create advanced account structures and rules for a chart of accounts
TOCTitle: Create advanced account structures and rules for a chart of accounts
ms:assetid: 020dc70a-9020-4cfe-82ad-861c74dc1e16
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242096(v=AX.60)
ms:contentKeyID: 36055924
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advanced rules
- advanced structures
- create advanced account rules
- create advanced account strucctures
- create advanced rules
- create advanced structures
---

# Create advanced account structures and rules for a chart of accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create advanced rules to provide additional financial dimensions that are part of the account combination, but that are not included in the account structure.

An advanced rule structure includes one or more financial dimensions that contain information that your organization wants to track, but that are not part of the account structure. Each advanced rule is associated with a specific account structure and can consist of one or more advanced rule structures.

## Create an advanced rule structure

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Advanced rule structures**.

2.  Click **New**, enter an advanced rule structure ID and description, and then click **OK**.

3.  Click the **Add segment** button to add criteria, and then select the appropriate options to create the criteria. You might have to scroll down to view all of the criteria. For more information, see the example later in this topic.

4.  Click **Activate** and close the form.

5.  Complete the steps in the next procedure to create an advanced rule that you will assign the advanced rule structure to.

## Create an advanced rule

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Configure account structures**.

2.  Select the account structure to apply the advanced rule to.

3.  On the **Action Pane**, in the **Setup** group, click **Advanced rule**.

4.  Click **New**.
    

    > [!NOTE]
    > <P>To add or modify advanced rules for an account structure, the account structure must be in <STRONG>Draft</STRONG> status. If the account structure has a status of <STRONG>Active</STRONG>, and you select to create a new advanced rule or modify an existing advanced rule, you will receive a message. Click the <STRONG>Edit advanced rule</STRONG> button to change the status of the account structure from <STRONG>Active</STRONG> to <STRONG>Draft</STRONG>.</P>



5.  Enter an advanced rule ID and name, and then click **OK**.

6.  Click the **Add filter** button to add criteria, and then select the appropriate options to create the criteria. You might have to scroll down to view all of the criteria.

7.  On the **Advanced rule structures** FastTab, click **Add**. Select the advanced rule structure to use when the advanced rule is being used.
    
    Only active advanced rule structures are displayed.

8.  To activate the advanced rule, you must activate the account structure by clicking **Activate** on the **Action Pane** in the **Configure account structures** form.

## Example

Your legal entity wants to track license plates for the vehicles that it owns as part of the vehicle maintenance main account. However, only one department uses these vehicles. Therefore, the legal entity does not have to enter that information for all departments. You could set up an advanced rule structure to track the license plate information, and you could set up an advanced rule to use that structure for only that department.

1.  Create the following advanced rule structure to track license plates for legal entity vehicles.
    
    **Advanced rule structure** = License plate

2.  Create the following advanced rule to determine when to use the advanced rule structure.
    
    Where Department **is** Delivery

3.  Add the **License plate** advanced rule structure to use when the advance rule is being used.

4.  Activate the account structure in the **Configure account structures** form.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

