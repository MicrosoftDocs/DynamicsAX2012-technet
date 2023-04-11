---
title: 'Examples: Internal controls'
TOCTitle: 'Examples: Internal controls'
ms:assetid: b3024402-11fb-4233-ad73-1f8f9dbf48d4
ms:mtpsurl: https://technet.microsoft.com/library/Hh271625(v=AX.60)
ms:contentKeyID: 36384257
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Examples: Internal controls 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

These examples explain how to manually set up and use internal controls in the purchasing department of a global organization named Fabrikam. Specifically, the internal control is designed to show that the same user is not able to approve vendor invoices and then approve the corresponding vendor payments. Chris, an information technology engineer, and Phyllis, the accounting manager, work together to add information to the **Compliance** site.

For information about how to import internal controls from a Microsoft Excel workbook, see [Import internal controls to the Compliance site](import-internal-controls-to-the-compliance-site.md).

## Set up the Internal controls site structure

1.  Chris clicks **Compliance** on the top link bar, and then clicks **Set up control environment** on the Quick Launch.

2.  On the **Set up control environment** page, Chris sets up the following site structure.
    
    **Operations - Domestic**
    
      - **Purchasing - Domestic**
    
      - **Sales - Domestic**

3.  Chris selects the **Purchasing - Domestic** node and adds Phyllis as a user who has **Add/Copy** permissions.
    

    > [!NOTE]
    > <P>For detailed steps, see <A href="set-up-the-internal-controls-site.md">Set up the Internal controls site</A>.</P>



4.  Chris clicks **Save**.

## Create a significant account

A significant account corresponds to a ledger account in a chart of accounts. In this example, the significant account is the “Cash” account.

1.  Phyllis clicks **Compliance** on the top link bar, and then clicks **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, Phyllis clicks **Purchasing - Domestic**.

3.  On the **Action Pane**, in the **New** group, Phyllis clicks **Add document**.

4.  Phyllis creates a significant account named “Cash.”
    
    1.  In the **Name** field, Phyllis enters **Cash**.
    
    2.  In the **Template** list, Phyllis selects **Significant Account**.
    
    3.  Phyllis clicks **Create**.

## Create a process

A process is a prescribed way that an organization accomplishes a series of steps. In the context of the **Internal controls** site, Phyllis creates a compliance process document to prove that the process has been reviewed and that it is working effectively. In this example, the process is “Pay vendor invoices.”

1.  Phyllis clicks **Compliance** on the top link bar, and then clicks **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, Phyllis clicks the **Cash** significant account.

3.  On the **Action Pane**, in the **New** group, Phyllis clicks **Add document**.

4.  Phyllis creates a process named ”Pay vendor invoices.”
    
    1.  In the **Name** field, Phyllis enters **Pay vendor invoices**.
    
    2.  In the **Template** list, Phyllis selects **Process**.
    
    3.  Phyllis clicks **Create and edit**.

5.  On the **Edit document** page, in the **Owner** field, Phyllis enters the compliance owner. This is the person who signs off to confirm that this process is working correctly. Use the following format: domain\\alias
    

    > [!NOTE]
    > <P>The users in the <STRONG>Owner</STRONG> fields must be set up as users on the Enterprise Portal for Microsoft Dynamics AX SharePoint site.</P>



6.  Phyllis clicks the **Validate user** icon.

7.  In the **Process Owner** and **Transaction Type** fields, Phyllis can set properties for the compliance document. These properties are displayed on control reports.

8.  Phyllis assigns compliance workflow steps to users.
    
    1.  In the **Workflow** section, under **1. Review**, Phyllis clicks the **Edit line** icon.
    
    2.  In the **Assigned to** column, Phyllis enters the user who is responsible for reviewing the process, and then clicks the **Validate user** icon.
        

        > [!NOTE]
        > <P>The users in the <STRONG>Assigned to</STRONG> fields must be set up as users on the Enterprise Portal SharePoint site.</P>

    
    3.  Phyllis clicks the **Update line** icon.
    
    4.  Under **2. Sign-off**, Phyllis clicks the **Edit line** icon.
    
    5.  In the **Assigned to** column, Phyllis enters the user who is responsible for verifying that the compliance review is complete, and then clicks the **Validate user** icon.
    
    6.  Phyllis clicks the **Update line** icon.

9.  Phyllis adds evidence that a defined process exists.
    
    1.  Phyllis clicks the **Add evidence from process documentation** link.
    
    2.  Phyllis selects **Create and post a vendor invoice example.docx**. She previously uploaded this file to the **Process documentation** shared document library on the **Compliance** site.
    
    3.  Phyllis clicks **Add**.
    
    4.  Phyllis clicks the **Update line** icon.

10. Phyllis clicks **Save**.

## Identify a risk

A risk is associated with a process. In this example, a risk is that the same user might approve vendor invoices and payments.

1.  Phyllis clicks **Compliance** on the top link bar, and then clicks **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, Phyllis clicks the **Pay vendor invoices** process.

3.  On the **Action Pane**, in the **New** group, Phyllis clicks **Add document**.

4.  Phyllis creates a risk named “Same user approves vendor invoices and payments.”
    
    1.  In the **Name** field, Phyllis enters **Same user approves vendor invoices and payments**.
    
    2.  In the **Template** list, Phyllis selects **Risk**.
    
    3.  Phyllis clicks **Create and edit**.

5.  On the **Edit document** page, in the **Owner** field, Phyllis enters the compliance owner for this risk and then clicks the **Validate user** icon.

6.  In the **Properties** section, Phyllis can set properties for the risk. For example, she can set the impact of the risk and the probability of the risk occurring.

7.  Phyllis marks the first compliance workflow step as completed.
    
    1.  In the **Workflow** section, under **1. Documentation**, Phyllis clicks the **Edit line** icon.
    
    2.  In the **Complete** column, Phyllis selects the check box.
    
    3.  In the **Assigned to** column, Phyllis enters the user who completed this step, and then clicks the **Validate user** icon.
    
    4.  Phyllis clicks the **Update line** icon.

8.  Phyllis assigns the remaining compliance workflow steps to users.
    
    1.  In the **Workflow** section, under **2. Review**, Phyllis clicks the **Edit line** icon.
    
    2.  In the **Assigned to** column, Phyllis enters the user who is responsible for reviewing the risk documentation, and then clicks the **Validate user** icon.
    
    3.  Phyllis clicks the **Update line** icon.
    
    4.  Under **3. Sign-off**, Phyllis clicks the **Edit line** icon.
    
    5.  In the **Assigned to** column, Phyllis enters the user who is responsible for evaluating the impact and probability of the risk, and then clicks the **Validate user** icon.
    
    6.  Phyllis clicks the **Update line** icon.

9.  Phyllis clicks **Save**.

## Create a control

A control mitigates a risk. In this example, segregation of duty rules are used to make sure that the same user does not have access to approve vendor invoices and to approve vendor payments.

1.  Phyllis clicks **Compliance** on the top link bar, and then clicks **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, Phyllis clicks the **Same user approves vendor invoices and payments** risk.

3.  On the **Action Pane**, in the **New** group, Phyllis clicks **Add document**.

4.  Phyllis creates a control named ”Segregation of duty rule for vendor invoices and payments.”
    
    1.  In the **Name** field, Phyllis enters **Segregation of duty rule for vendor invoices and payments**.
    
    2.  In the **Template** list, Phyllis selects **Control**.
    
    3.  Phyllis clicks **Create and edit**.

5.  On the **Edit document** page, in the **Owner** field, Phyllis enters the compliance owner for this control and then clicks the **Validate user** icon.

6.  In the **Properties** section, Phyllis can set properties for the control. These properties are displayed on control reports. The **Control Effectiveness** property is used for the **Control Effectiveness** chart on the **Compliance** site home page.

7.  Phyllis marks the first compliance workflow step as completed.
    
    1.  In the **Workflow** section, under **1. Documentation**, Phyllis clicks the **Edit line** icon.
    
    2.  In the **Complete** column, Phyllis selects the check box.
    
    3.  In the **Assigned to** column, Phyllis enters the user who completed this step, and then clicks the **Validate user** icon.
    
    4.  Phyllis clicks the **Update line** icon.

8.  Phyllis assigns the remaining compliance workflow steps to users.
    
    1.  In the **Workflow** section, under **2. Test**, Phyllis clicks the **Edit line** icon.
    
    2.  In the **Assigned to** column, Phyllis enters the user who is responsible for testing the control, and then clicks the **Validate user** icon.
    
    3.  Phyllis clicks the **Update line** icon.
    
    4.  Under **3. Review**, Phyllis clicks the **Edit line** icon.
    
    5.  In the **Assigned to** column, Phyllis enters the user who is responsible for reviewing the risk documentation, and then clicks the **Validate user** icon.
    
    6.  Phyllis clicks the **Update line** icon.
    
    7.  Under **4. Sign-off**, Phyllis clicks the **Edit line** icon.
    
    8.  In the **Assigned to** column, Phyllis enters the user who is responsible for making sure that the control is effective, and then clicks the **Validate user** icon.
    
    9.  Phyllis clicks the **Update line** icon.

9.  Phyllis clicks **Save**.

## Create a test plan

A test plan verifies that a control is functional. In this example, the **Segregation of duties conflicts** form in the Microsoft Dynamics AX client is used as a test to review duties.

1.  Phyllis clicks **Compliance** on the top link bar, and then clicks **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, Phyllis clicks the **Segregation of duty rule for vendor invoices and payments** control.

3.  On the **Action Pane**, in the **New** group, Phyllis clicks **Add document**.

4.  Phyllis creates a test plan named ”View segregation of duties conflicts.”
    
    1.  In the **Name** field, Phyllis enters **View segregation of duties conflicts**.
    
    2.  In the **Template** list, Phyllis selects **Test Plan**.
    
    3.  Phyllis clicks **Create and edit**.

5.  On the **Edit document** page, in the **Owner** field, Phyllis enters the compliance owner for this test plan and then clicks the **Validate user** icon.

6.  In the **Properties** section, Phyllis can set properties for the test plan. These properties are displayed on control reports.

7.  Phyllis marks the first compliance workflow step as completed.
    
    1.  In the **Workflow** section, under **1. Documentation**, Phyllis clicks the **Edit line** icon.
    
    2.  In the **Complete** column, Phyllis selects the check box.
    
    3.  In the **Assigned to** column, Phyllis enters the user who completed this step, and then clicks the **Validate user** icon.
    
    4.  Phyllis clicks the **Update line** icon.

8.  Phyllis assigns the remaining compliance workflow steps to users.
    
    1.  In the **Workflow** section, under **2. Validate**, Phyllis clicks the **Edit line** icon.
    
    2.  In the **Assigned to** column, Phyllis enters the user who is responsible for validating the test results, and then clicks the **Validate user** icon.
    
    3.  Phyllis clicks the **Update line** icon.
    
    4.  Under **3. Review**, Phyllis clicks the **Edit line** icon.
    
    5.  In the **Assigned to** column, Phyllis enters the user who is responsible for reviewing the test plan, and then clicks the **Validate user** icon.
    
    6.  Phyllis clicks the **Update line** icon.
    
    7.  Under **4. Sign-off**, Phyllis clicks the **Edit line** icon.
    
    8.  In the **Assigned to** column, Phyllis enters the user who is responsible for testing the control, and then clicks the **Validate user** icon.
    
    9.  Phyllis clicks the **Update line** icon.

9.  Phyllis clicks **Save**.

## Report an issue and upload evidence

An issue identifies a problem with a control. For example, if the **Segregation of duty conflicts** form reveals that the same user is assigned to both the “Approve vendor invoices” and “Approve vendor payments” duties, Phyllis might change the duty assignments. She could then view the **Segregation of duty conflicts** form again and upload a screen capture of it as evidence that the issue has been resolved. This example assumes that a screen capture has been saved as a graphics file and is uploaded to a secure location on Fabrikam’s intranet.

1.  Phyllis clicks **Compliance** on the top link bar, and then clicks **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, Phyllis clicks the **Segregation of duty rule for vendor invoices and payments** control.

3.  On the **Action Pane**, in the **New** group, Phyllis clicks **Add document**.

4.  Phyllis creates an issue named “User is assigned to both the Approve vendor invoices and Approve vendor payments duties.”
    
    1.  In the **Name** field, Phyllis enters **User is assigned to both the Approve vendor invoices and Approve vendor payments duties**.
    
    2.  In the **Template** list, Phyllis selects **Issue**.
    
    3.  Phyllis clicks **Create and edit**.

5.  On the **Edit document** page, in the **Owner** field, Phyllis enters the compliance owner for this issue and then clicks the **Validate user** icon.

6.  Phyllis resolves the issue.
    
    1.  In the **Workflow** section, under **1. Resolve**, Phyllis clicks the **Edit line** icon.
    
    2.  In the **Complete** column, Phyllis selects the check box.
    
    3.  In the **Assigned to** column, Phyllis enters the user who resolved the issue, and then clicks the **Validate user** icon.
    
    4.  Phyllis clicks the **Update line** icon.

7.  Phyllis adds evidence to prove that the issue has been resolved.
    
    1.  Phyllis clicks the **Add evidence via URL** link.
    
    2.  In the **URL** column, Phyllis enters or pastes the location of the saved graphic.
        

        > [!NOTE]
        > <P>The URL must contain http://, https://, or ftp:// to be an active link.</P>

    
    3.  Phyllis clicks the **Update line** icon.

8.  Phyllis clicks **Save**.

## See also

[Set up the Internal controls site](set-up-the-internal-controls-site.md)

[Manage internal controls](manage-internal-controls.md)

[Edit document templates](edit-document-templates.md)

[About evidence](about-evidence.md)

[About internal controls reports](about-internal-controls-reports.md)

  


