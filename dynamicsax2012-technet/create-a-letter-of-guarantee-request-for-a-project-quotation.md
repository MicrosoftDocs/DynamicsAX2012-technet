---
title: Create a letter of guarantee request for a project quotation
TOCTitle: Create a letter of guarantee request for a project quotation
ms:assetid: f77cf344-7a9b-42ce-a5a9-179d96f927a2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227549(v=AX.60)
ms:contentKeyID: 36060033
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Create the letter of guarantee request for a quotation (Project)
- Lletter of guarantee request for a quotation (Project)
audience: Application User
ms.search.region: Global
---

# Create a letter of guarantee request for a project quotation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A letter of guarantee can be issued for a project quotation transaction between a principal and a beneficiary. After the project quotation is created, the principal can create a letter of guarantee request for the beneficiary and submit it to the bank. When the bank approves the request, the letter of guarantee is issued to the beneficiary. For more information, see [About letter of guarantee](about-letter-of-guarantee.md).

## Create a project quotation

Use the **Project quotation** form to create a project quotation with the **Bank document type** as **Letter of guarantee**.


> [!NOTE]
> <P>Before you can set the <STRONG>Bank document type</STRONG>, you must select the <STRONG>Bank document</STRONG> check box in the <STRONG>Configuration</STRONG> form, and then use the <STRONG>General ledger parameters</STRONG> form to activate the letter of guarantee. For more information, see <A href="activate-the-letter-of-guarantee.md">Activate the letter of guarantee</A>.</P>



1.  Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**.

2.  Click **Project quotation** to create a new project quotation.

3.  In the **Account type** field, select **Customer**.

4.  In the **Customer account** field, select the customer that has requested the letter of guarantee.

5.  Click the **General** FastTab, and in the **Bank document type** field, select **Letter of guarantee**. Enter any other required details.

6.  Click **OK** to close the **Create quotation** form and return to the **Project quotation** form.

## Create the letter of guarantee request for a project quotation

You can request a letter of guarantee for a customer using the **Project quotation** form. After you make a request, you must submit it to the bank for approval.

1.  In the **Project quotation** form, click the **Lines** FastTab.

2.  Click **New** to create a project quotation line for an item, and then specify the following: **Transaction type**, **Project category**, **Quantity**, **Line property**, and **Unit price**.

3.  On the Action Pane, click the **Quote** tab.

4.  In the **Bank document** group, click **Letter of guarantee** to open the **Letter of guarantee** form. For information about how to create the request, submit it to the bank, and issue the letter of guarantee to the beneficiary, see [Request and issue the letter of guarantee](request-and-issue-the-letter-of-guarantee.md).

5.  Close the forms to save your changes.

## See also

[Increase or decrease the letter of guarantee value](increase-or-decrease-the-letter-of-guarantee-value.md)

[Liquidate, extend, or cancel a letter of guarantee](liquidate-extend-or-cancel-a-letter-of-guarantee.md)

[Letter of guarantee (form)](https://technet.microsoft.com/en-us/library/hh227662\(v=ax.60\))

  


