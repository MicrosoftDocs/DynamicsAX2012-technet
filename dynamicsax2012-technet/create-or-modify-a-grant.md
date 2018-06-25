---
title: Create or modify a grant
TOCTitle: Create or modify a grant
ms:assetid: 6d72a050-52d3-43f8-a6df-aeed35a4914b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242638(v=AX.60)
ms:contentKeyID: 36058029
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create or modify a grant [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A grant is a gift of money for a specific purpose or project. Usually, there are restrictions on how a grant can be spent. In **Project management and accounting**, you can enter and track grants and define their relationships to projects and project contracts. For example, you can:

  - Associate grants with projects and funding sources through links to the **Project** form and **Project contract details** form.

  - Enter and track changes to a grant as it transitions from one status to another.

  - Enter and track costs, requested amounts, and awarded amounts.

  - Create master grants and associate subgrants with them.

You can create a grant by entering all of the details into a new record, or you can copy and modify the details from an existing grant.

## Create a new grant and enter the details

1.  Click **Project management and accounting** \> **Common** \> **Grants** \> **Grants**.

2.  On the **Action Pane**, on the **Grant** tab, in the **New** group, click **Grant**.

3.  In the **Grant details** form, on the **General** FastTab, in the **Grant ID** field, enter an alphanumeric identifier for the grant.

4.  In the **Grant name** field, enter a name for the grant.

5.  Add details about the new grant.
    
    Most fields are optional and you can enter as little or as much information as you want. The following table describes the type of information that you can enter on each FastTab.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>FastTab</p></th>
    <th><p>Information</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>General</strong></p></td>
    <td><p>Enter details about the name, status, description, purpose, and amount of the grant.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Contact information</strong></p></td>
    <td><p>Enter details about the staff members and the department that will manage the grant, and about the grant customer, or organization, that is the source of the grant.</p>
    <p>You can also identify whether your organization is a pass-through entity that receives the grant and then passes it on to another recipient.</p>
    <p>Click <strong>Add</strong> to add contact information such as telephone numbers and email addresses for the organization that is providing the grant.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Dates and deadlines</strong></p></td>
    <td><p>Enter dates that are related to the grant and to the grant application. You can enter such details as the date the application is due, when it is submitted, and when it is approved or rejected.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Associated projects and project contracts</strong></p></td>
    <td><p>Click a button to do any of the following:</p>
    <ul>
    <li><p><strong>Add funding source</strong> – Add a new funding source for the grant. You can enter all the details now, or use default information and update it later. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh242771(v=ax.60)">Funding source definition (form)</a>.</p></li>
    <li><p><strong>Add project contract</strong> – Add or update project contract information. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa586038(v=ax.60)">Project contracts (form)</a>.</p></li>
    <li><p><strong>Add project</strong> – Add or update project details. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa585245(v=ax.60)">Projects (form)</a>.</p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>You can enter information on this FastTab only if the <STRONG>Grant status</STRONG> field on the <STRONG>General</STRONG> FastTab is set to <STRONG>Active</STRONG> or <STRONG>Awarded</STRONG>.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Setup</strong></p></td>
    <td><p>Enter details about matching funds, if they are required. Many organizations that award grants require a recipient to spend a certain amount of their own money or resources to match what is awarded in the grant. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh227437(v=ax.60)">Matching types (form)</a>.</p>
    <p>In the <strong>Local project or tracking ID</strong> field, you can enter an identifier that is different from the project identifier. Select the <strong>Subgrantor</strong> check box if part of the grant will be awarded to a different organization.</p>
    <p>For grants that are awarded in the United States, you can specify whether a grant will be awarded under a state or federal mandate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Drawdown details</strong></p></td>
    <td><p>Add or update information about how often grant funds can be withdrawn, billed for, or spent.</p></td>
    </tr>
    </tbody>
    </table>


## Create a new grant by copying the details from an existing grant

1.  Click **Project management and accounting** \> **Common** \> **Grants** \> **Grants**.

2.  Select the grant that you want to copy.

3.  On the **Action Pane**, on the **Grant** tab, in the **New** group, click **Copy from grant**.

4.  Enter an alphanumeric identifier and a name for the new grant, and then click **OK**.

5.  In the **Grant details** form, review the details of the copied grant and make changes as necessary.
    
    Most fields in the form are optional. For more information, see [Grant details (form)](https://technet.microsoft.com/en-us/library/hh242883\(v=ax.60\)).

## View or modify the details for an existing grant

1.  Click **Project management and accounting** \> **Common** \> **Grants** \> **Grants**.

2.  Select the grant that you want to modify.

3.  On the **Action Pane**, on the **Grant** tab, in the **Maintain** group, click **Edit**.

4.  Review the grant details and make changes as necessary. For more information about specific fields, see [Grant details (form)](https://technet.microsoft.com/en-us/library/hh242883\(v=ax.60\)).

## See also

[Funding source details (form)](https://technet.microsoft.com/en-us/library/hh209607\(v=ax.60\))

[Funding source definition (form)](https://technet.microsoft.com/en-us/library/hh242771\(v=ax.60\))

[Grant details (form)](https://technet.microsoft.com/en-us/library/hh242883\(v=ax.60\))

[Grant types (form)](https://technet.microsoft.com/en-us/library/hh227643\(v=ax.60\))

[Grant customer types (form)](https://technet.microsoft.com/en-us/library/hh209046\(v=ax.60\))

[Matching types (form)](https://technet.microsoft.com/en-us/library/hh227437\(v=ax.60\))

[Project contracts (form)](https://technet.microsoft.com/en-us/library/aa586038\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

