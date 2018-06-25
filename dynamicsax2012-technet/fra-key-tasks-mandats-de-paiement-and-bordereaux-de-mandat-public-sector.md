---
title: '(FRA) Key tasks: Mandats de paiement and bordereaux de mandat (Public sector)'
TOCTitle: '(FRA) Key tasks: Mandats de paiement and bordereaux de mandat (Public sector)'
ms:assetid: 834a3249-8e8a-4c6b-b111-442a01bfa157
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh450746(v=AX.60)
ms:contentKeyID: 36966684
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- Public sector
- France
- French
- bordereau de mandat
- mandat
- mandat de paiement
- bordereau
- maquette de mandat
- bordereaux
- mandats
- mandats de paiement
- bordereaux de mandat
---

# (FRA) Key tasks: Mandats de paiement and bordereaux de mandat (Public sector) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The mandat de paiement is used by the director to notify the accountant that the organization is obligated to pay a specific amount to another entity, and to authorize the accountant to pay that amount. The director or the accountant may delegate a representative to perform the task, but the responsibility for each task remains with the director or the accountant.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>Mandats de paiement are available only if the following conditions are met: 
> <UL>
> <LI>
> <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
> <LI>
> <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
> <LI>
> <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <STRONG>Commitments (France)</STRONG> regulatory document type is selected in the <STRONG>Budget parameters</STRONG> form, when the following hotfix is installed: KB3047235</P>
> <LI>
> <P>In cumulative update 7 for Microsoft Dynamics AX 2012, the <STRONG>Use French public sector accounting rules</STRONG> check box is selected in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>
> <P>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P>



A group of related mandats, together with all supporting documentation, are assigned to a bordereau de mandat for submittal to the accountant.

## What do you want to do?

Learn more about...

Director: Assign invoice lines to mandats

Director: Authorize mandats

Director: Assign mandats to a bordereau de mandat

Director: Submit mandats to the accountant

Accountant: Accept mandats

Accountant: Reject or hold mandats

Director: Issue a requisition order

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[(FRA) About mandats de paiement (Public sector)](fra-about-mandats-de-paiement-public-sector.md)

[About accounting distributions and subledger journal entries for vendor invoices](about-accounting-distributions-and-subledger-journal-entries-for-vendor-invoices.md)

## Director: Assign invoice lines to mandats

When a vendor invoice is received, the director approves or certifies that the goods or services were received and gathers the necessary supporting documentation. Once everything is in order, the director assigns each invoice line to a mandat.

For certain expenses, the accountant may make a payment before receiving a mandat, and the director will regularize the payment by issuing a mandat afterward. This usually occurs for urgent or recurrent expenses, such as utility payments or rent. It may also occur when money is owed to a régisseur.

1.  Click **Accounts payable** \> **Reports** \> **France** \> **Mandat de paiement**.

2.  To retrieve invoices that have not yet been paid, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve invoices that have already been paid, in the **Invoice status** group, click **Posted**.
    

    > [!IMPORTANT]
    > <P>Lines from invoices that are being edited will not be retrieved.</P>



3.  In the **From date** field, enter the first date in the range of dates that you want to select invoices from. In the **To date** field, enter the last date in the range of dates. Invoices that were created within this range will be reviewed to determine whether they meet the selected criteria.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the vendor invoices that you want to assign to mandats. In most cases, you will select a single vendor account for the **Invoice accounts** field, and leave the remaining criteria blank.
    

    > [!NOTE]
    > <P>To find the invoice lines from mandats that were rejected by the accountant, select <STRONG>Not reviewed</STRONG> for the <STRONG>Director authorization status</STRONG> and <STRONG>Rejected</STRONG> for the <STRONG>Accountant acceptance status</STRONG>. Do not enter a mandat number. The mandat number and bordereau de mandat number are removed when the accountant rejects the mandat.</P>



6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Click the **Mandat** column heading to sort the invoice lines by mandat number. All the invoice lines that are not assigned to a mandat will appear at the top of the column.

8.  Select the check box at the start of each line that you want to assign to a mandat.

9.  Click **Assign to mandat**. Each line that you selected is assigned to a mandat.

Back to top

## Director: Authorize mandats

After reviewing the mandat and all supporting documentation, the director can authorize payment of the invoice line that is assigned to the mandat. This can be done either from the mandat maintenance form, or from the invoice line on the vendor invoice form or the vendor transactions form.

### From the mandat maintenance form

1.  Click **Accounts payable** \> **Reports** \> **France** \> **Mandat de paiement**.

2.  To retrieve an invoice that has not yet been paid, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve an invoice that has already been paid, in the **Invoice status** group, click **Posted**.
    

    > [!IMPORTANT]
    > <P>Lines from invoices that are being edited will not be retrieved.</P>



3.  In the **From date** field, enter the first date in the range of dates that you want to select invoices from. In the **To date** field, enter the last date in the range of dates. Invoices that were created within this range will be reviewed to determine whether they meet the selected criteria.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the vendor invoices that you want to authorize payments for. In most cases, you will select **Not reviewed** as the criteria for the **Director authorization status** field, and leave the remaining criteria blank.

6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Select an invoice line, and then click **View invoice** to review the information about the invoice line. If necessary, also review any related documents that may exist outside the system.

8.  Once you have verified that the invoice line should be paid, return to the mandat maintenance form and select **Authorized** in the **Director authorization status** field for the line.

### From the vendor invoice or vendor transactions form

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

2.  Double-click an invoice to open it.

3.  Review the information about the invoice line. If necessary, also review any related documents that may exist outside the system.

4.  Once you have verified that the invoice line should be paid, on the **Mandat de paiement** tab, in the **Director authorization status** field, select **Authorized**.

Back to top

## Director: Assign mandats to a bordereau de mandat

The director assigns related mandats to a bordereau de mandat so that they can be submitted to the accountant.

1.  Click **Accounts payable** \> **Reports** \> **France** \> **Mandat de paiement**.

2.  To retrieve invoices that have not yet been paid, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve mandats that have already been paid, in the **Invoice status** group, click **Posted**.
    

    > [!IMPORTANT]
    > <P>Lines from invoices that are being edited will not be retrieved.</P>



3.  In the **From date** field, enter the first date in the range of dates that you want to select invoices from. In the **To date** field, enter the last date in the range of dates. Invoices that were created within this range will be reviewed to determine whether they meet the selected criteria.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the invoice lines associated with the mandats that you want to assign to a bordereau de mandat.

6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Click the **Bordereau de mandat** column heading to sort the invoice lines by bordereau de mandat number. All the invoice lines that are not assigned to a bordereau de mandat will appear at the top of the column.

8.  Select the check box at the start of each line that you want to assign to a bordereau de mandat. A bordereau de mandat must contain either invoice lines related to capital expenses or invoice lines related to operational expenses. It cannot contain a mix of the two.

9.  Click **Assign to bordereau de mandat**. All of the lines that you selected are assigned to a single bordereau de mandat.

Back to top

## Director: Submit mandats to the accountant

The director collects printed mandats and their related documentation under a bordereau de mandat and submits them to the accountant.

### Print the mandats assigned to a bordereau

1.  Click **Accounts payable** \> **Reports** \> **France** \> **Mandat de paiement**.

2.  Click **Select** to open a database inquiry form.

3.  On the inquiry form, enter the criteria to identify the mandats that you want to print, and then click **OK**.

4.  In the **Director** and **Accountant** fields, type the name of the director and the name of the accountant for your organization.

5.  Print the selected mandats.

### Print the bordereau

1.  Click **Accounts payable** \> **Reports** \> **France** \> **Bordereau de mandat**.

2.  Click **Select** to open a database inquiry form.

3.  On the inquiry form, enter the criteria to identify the bordereau that you want to print, and then click **OK**.

4.  Print the selected bordereau.

Back to top

## Accountant: Accept mandats

The accountant reviews the submitted mandats and all supporting documentation. If an invoice line meets all legal and organizational requirements, the accountant can accept the mandat and pay the invoice line that is assigned to the mandat.

### From the mandat maintenance form

1.  Click **Accounts payable** \> **Reports** \> **France** \> **Mandat de paiement**.

2.  To retrieve invoice lines that have not yet been paid, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve invoice lines that have already been paid, in the **Invoice status** group, click **Posted**.
    

    > [!IMPORTANT]
    > <P>Lines from invoices that are being edited will not be retrieved.</P>



3.  In the **From date** field, enter the first date in the range of dates that you want to select invoices from. In the **To date** field, enter the last date in the range of dates. Invoices that were created within this range will be reviewed to determine whether they meet the selected criteria.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the vendor invoice lines that you want to accept for payment. These will usually have a **Director authorization status** of **Authorized** and an **Accountant acceptance status** of **Not reviewed**.

6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Select an invoice line, and then click **View invoice** to review the information about the invoice line. If necessary, also review any related documents that accompanied the mandat and the bordereau de mandat.

8.  If the invoice line meets all legal and organizational requirements, return to the mandat maintenance form and select **Accepted** in the **Accountant acceptance status** field.

### From the vendor invoice or vendor transactions form

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

2.  Double-click an invoice to open it.

3.  Review the information about the invoice line. If necessary, also review any related documents that accompanied the mandat and the bordereau de mandat.

4.  If the invoice line meets all legal and organizational requirements, on the **Mandat de paiement** tab, in the **Accountant acceptance status** field, select **Accepted**.

Back to top

## Accountant: Reject or hold mandats

The accountant reviews mandats and all supporting documentation (including requisition orders). If an invoice line does not meet all legal and organizational requirements, the accountant must reject the mandat.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

2.  Double-click an invoice to open it.

3.  Review the information about the invoice line. If necessary, also review any related documents that accompanied the mandat and the bordereau de mandat.

4.  To reject the mandat, on the **Mandat de paiement** tab, in the **Accountant acceptance status** field, select **Rejected**. When you do this, the **Director authorization status** changes to **Not reviewed**, and the mandat and bordereau de mandat numbers are cleared.
    
    –or–
    
    To hold the mandat for additional investigation, leave the **Accountant acceptance status** field set to **Not reviewed**.

5.  In the **Memo** field, enter a brief explanation of the reason for holding or rejecting the mandat.

Back to top

## Director: Issue a requisition order

When the accountant rejects a mandat, the director may request that the accountant pay the invoice line even though it does not meet all of the usual requirements. To do this, the director writes a letter assuming responsibility for the payment, and then assigns the invoice line to a new mandat, which indicates that the mandat is to be treated as a requisition order.

1.  Click **Accounts payable** \> **Reports** \> **France** \> **Mandat de paiement**.

2.  To retrieve an invoice that has not yet been paid, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve an invoice that has already been paid, in the **Invoice status** group, click **Posted**.
    

    > [!IMPORTANT]
    > <P>Lines from invoices that are being edited will not be retrieved.</P>



3.  In the **From date** field, enter a date earlier than or the same as the invoice date of the invoice that was assigned to the rejected mandat. In the **To date** field, enter a date later than or the same as the invoice date of the invoice.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the vendor invoices that you want to issue a requisition order for.

6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Select the invoice line that you want to issue a requisition order for, and then click **Assign to mandat** to assign the invoice line to a new mandat.

8.  Click **View invoice** to open the invoice.

9.  On the **Mandat de paiement** tab, do the following:
    
    1.  In the **Director authorization status** field, select **Authorized**.
    
    2.  Select the **Requisition order** check box.
    
    3.  Enter a brief explanatory message in the **Memo** field.

10. Assign the mandat to a bordereau de mandat and submit it to the accountant in the usual manner.
    

    > [!IMPORTANT]
    > <P>When you print the mandat, attach the letter in which you take responsibility for the payment together with all other supporting documentation.</P>



Back to top

## Find form help

[Vendor invoice (form)](https://technet.microsoft.com/en-us/library/hh209644\(v=ax.60\))

[Vendor invoice journal (form)](https://technet.microsoft.com/en-us/library/aa587621\(v=ax.60\))

[(FRA) Maintain mandats de paiement (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh450744\(v=ax.60\))

[Inquiry (form)](https://technet.microsoft.com/en-us/library/aa575929\(v=ax.60\))

## Find related tasks

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

