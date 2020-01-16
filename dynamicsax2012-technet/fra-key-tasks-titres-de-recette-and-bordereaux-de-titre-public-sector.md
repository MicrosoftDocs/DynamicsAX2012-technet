---
title: '(FRA) Key tasks: Titres de recette and bordereaux de titre (Public sector)'
TOCTitle: '(FRA) Key tasks: Titres de recette and bordereaux de titre (Public sector)'
ms:assetid: 6caa1120-6636-47ed-b376-5b187e184286
ms:mtpsurl: https://technet.microsoft.com/library/Hh450745(v=AX.60)
ms:contentKeyID: 36966683
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- Public sector
- France
- French
- bordereau de titre
- titre
- titre de recette
- bordereau
- bordereaux
- titres
- titres de recette
- bordereaux de titre
audience: Application User
ms.search.region: France
---

# (FRA) Key tasks: Titres de recette and bordereaux de titre (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The titre de recette is used by the director to notify the accountant that the organization is entitled to collect a specific amount from another entity, and to authorize the accountant to pay that amount. The director or the accountant may delegate a representative to perform the task, but the responsibility for each task remains with the director or the accountant.

A group of related titres, together with all supporting documentation, are assigned to a bordereau de titre for submittal to the accountant.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>Titres de recette are available only if the following conditions are met: 
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



## What do you want to do?

Learn more about...

Director: Assign invoice lines to titres

Director: Authorize titres

Director: Assign titres to a bordereau de titre

Director: Submit titres to the accountant

Accountant: Accept titres

Accountant: Reject or hold titres

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[(FRA) About titres de recette (Public sector)](fra-about-titres-de-recette-public-sector.md)

[About customer invoices, free text invoices, and pro forma invoices](about-customer-invoices-free-text-invoices-and-pro-forma-invoices.md)

## Director: Assign invoice lines to titres

When a free text invoice is created, the director approves or certifies that the goods or services were provided and gathers the necessary supporting documentation. Once everything is in order, the director assigns each invoice line to a titre.

For certain expenses, the accountant may receive a payment before receiving a titre, and the director will regularize the receipt by issuing a titre afterward. This behavior may occur for certain recurrent receipts, such as rent. It may also occur when money is collected by a régisseur.

1.  Click **Accounts receivable** \> **Periodic** \> **Maintain titres de recette (France)**.

2.  To retrieve invoice lines for which the payment has not yet been received, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve invoice lines for which the payment has already been received, in the **Invoice status** group, click **Posted**.

3.  In the **From date** field, enter the first date in the range of dates that you want to select invoices from. In the **To date** field, enter the last date in the range of dates. Invoices that were created within this range will be reviewed to determine whether they meet the selected criteria.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the invoices that you want to assign to titres. In most cases, you will select a customer account for the **Invoice accounts** field and leave the remaining criteria blank.
    

    > [!NOTE]
    > <P>To find the invoice lines from titres that were rejected by the accountant, select <STRONG>Not reviewed</STRONG> for the <STRONG>Director authorization status</STRONG> and <STRONG>Rejected</STRONG> for the <STRONG>Accountant acceptance status</STRONG>. Do not enter a titre number. The titre number and bordereau de titre number are removed when the accountant rejects the titre.</P>



6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Click the **Titre** column heading to sort the invoice lines by titre number. All the invoice lines that are not assigned to a titre will appear at the top of the column.

8.  Select the check box at the start of each line that you want to assign to a titre.

9.  Click **Assign to titre**. Each line that you selected is assigned to a titre.

Back to top

## Director: Authorize titres

After reviewing the titre and all supporting documentation, the director can authorize the collection of the invoice line that is assigned to the titre. This can be done either from the titre maintenance form, or from the invoice line on the free text invoice form.

### From the titre maintenance form

1.  Click **Accounts receivable** \> **Periodic** \> **Maintain titres de recette (France)**.

2.  To retrieve invoices for which payment has not yet been received, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve invoices for which payment has already been received, in the **Invoice status** group, click **Posted**.

3.  In the **From date** field, enter the first date in the range of dates that you want to select invoices from. In the **To date** field, enter the last date in the range of dates. Invoices that were created within this range will be reviewed to determine whether they meet the selected criteria.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the invoices for which you want to authorize collection.

6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Select an invoice line, and then click **View invoice** to review the information about the invoice line. If necessary, also review any related documents that may exist outside the system.

8.  Once you have verified that the invoice line should be collected, return to the titre maintenance form and select **Authorized** in the **Director authorization status** field for the line.

### From the free text invoice form

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Double-click an invoice to open it.

3.  Review the information about the invoice line. If necessary, also review any related documents that may exist outside the system.

4.  Once you have verified that the invoice line should be collected, on the **Titre de recette** tab, in the **Director authorization status** field, select **Authorized**.

Back to top

## Director: Assign titres to a bordereau de titre

The director assigns related mandats to a bordereau de titre so that they can be submitted to the accountant.

1.  Click **Accounts receivable** \> **Periodic** \> **Maintain titres de recette (France)**.

2.  To retrieve invoice lines for which payment has not yet been received, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve invoice lines for which payment has already been received, in the **Invoice status** group, click **Posted**.

3.  In the **From date** field, enter the first date in the range of dates that you want to select invoices from. In the **To date** field, enter the last date in the range of dates. Invoices that were created within this range will be reviewed to determine whether they meet the selected criteria.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the invoice lines associated with the titres that you want to assign to a bordereau de titre.

6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Click the **Bordereau de titre** column heading to sort the invoice lines by bordereau de titre number. All the invoice lines that are not assigned to a bordereau de titre will appear at the top of the column.

8.  Select the check box at the start of each line that you want to assign to a bordereau de titre. A bordereau de titre must contain either invoice lines related to capital receipts or invoice lines related to operational receipts. It cannot contain a mix of the two.

9.  Click **Assign to bordereau de titre**. All of the lines that you selected are assigned to a single bordereau de titre.

Back to top

## Director: Submit titres to the accountant

The director collects printed titres and their related documentation under a bordereau de titre and submits them to the accountant.

### Print the titres assigned to a bordereau

1.  Click **Accounts receivable** \> **Reports** \> **France** \> **Titre de recette**.

2.  Click **Select** to open a database inquiry form.

3.  On the inquiry form, enter the criteria to identify the titres that you want to print, and then click **OK**.

4.  In the **Director** and **Accountant** fields, type the name of the director and the accountant for your organization.

5.  Print the selected titres.

### Print the bordereau

1.  Click **Accounts receivable** \> **Reports** \> **France** \> **Bordereau de titre**.

2.  Click **Select** to open a database inquiry form.

3.  On the inquiry form, enter the criteria to identify the bordereau that you want to print, and then click **OK**.

4.  Print the selected bordereau.

Back to top

## Accountant: Accept titres

The accountant reviews the submitted titres and all supporting documentation. If an invoice line meets all legal and organizational requirements, the accountant can accept the titre and collect the payment from the invoice line that is assigned to the titre.

### From the titre maintenance form

1.  Click **Accounts receivable** \> **Periodic** \> **Maintain titres de recette (France)**.

2.  To retrieve invoice lines for which the payment has not yet been received, in the **Invoice status** group, click **Pending**.
    
    –or–
    
    To retrieve invoice lines for which the payment has already been received, in the **Invoice status** group, click **Posted**.

3.  In the **From date** field, enter the first date in the range of dates that you want to select invoices from. In the **To date** field, enter the last date in the range of dates. Invoices that were created within this range will be reviewed to determine whether they meet the selected criteria.

4.  Click **Retrieve lines** to open a database inquiry form.

5.  On the inquiry form, enter the criteria to find the invoices that you want to accept for collection. These will usually have a **Director authorization status** of **Authorized** and an **Accountant acceptance status** of **Not reviewed**.

6.  Click **OK** to close the inquiry form. All invoice lines that match the invoice status, dates, and selection criteria that you entered will appear in the grid.

7.  Select an invoice line, and then click **View invoice** to review the information about the invoice line. If necessary, also review any related documents that accompanied the titre and the bordereau de titre.

8.  If the invoice line meets all legal and organizational requirements, return to the titre maintenance form and select **Accepted** in the **Accountant acceptance status** field.

### From the free text invoice form

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Double-click an invoice to open it.

3.  Review the information about the invoice line. If necessary, also review any related documents that accompanied the titre and the bordereau de titre.

4.  If the invoice line meets all legal and organizational requirements, on the **Titre de recette** tab, in the **Accountant acceptance status** field, select **Accepted**.

Back to top

## Accountant: Reject or hold titres

The accountant reviews titres and all supporting documentation. If a titre does not meet all legal and organizational requirements, the accountant must reject the titre.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Double-click an invoice to open it.

3.  Review the information about the invoice line. If necessary, also review any related documents that accompanied the titre and the bordereau de titre.

4.  To reject the titre, on the **Titre de recette** tab, in the **Accountant acceptance status** field, select **Rejected**. When you do this, the **Director authorization status** changes to **Not reviewed**, and the titre and bordereau de titre numbers are cleared.
    
    –or–
    
    To hold the titre for additional investigation, leave the **Accountant acceptance status** field set to **Not reviewed**.

5.  In the **Memo** field, enter a brief explanation of the reason for holding or rejecting the titre.

Back to top

## Find form help

[Free text invoice (form)](https://technet.microsoft.com/library/aa556897\(v=ax.60\))

[(FRA) Maintain titres de recette (form) (Public sector)](https://technet.microsoft.com/library/hh450748\(v=ax.60\))

[Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\))

## Find related tasks

[Key tasks: Free text invoices](key-tasks-free-text-invoices.md)

[Reprint a free text invoice](reprint-a-free-text-invoice.md)

  


