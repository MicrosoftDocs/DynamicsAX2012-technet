---
title: (NOR) Set up free-text interpreter for FTX type of eGiro segments
TOCTitle: (NOR) Set up free-text interpreter for FTX type of eGiro segments
ms:assetid: eb71528d-6893-45fa-ae8d-881719ccd418
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243251(v=AX.60)
ms:contentKeyID: 36059873
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (NOR) Set up free-text interpreter for FTX type of eGiro segments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can define the free-text interpreter for the free-text (FTX) type of segments that are found in the eGiro import file.

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **eGiro** \> **Free text interpreter**.

2.  Press CTRL+N to create a free-text interpreter.

3.  In the **Account type** field, **Customer** is selected.

4.  In the **Account** field, select the customer account number for which you are creating the free-text interpreter.

5.  Enter the segment group, occurrence, and qualifier combination in the **Group**, **Occurrence** and **Qualifier** fields. Enter the priority on which the eGiro free-text analysis for the selected combination in the **Priority** field is based.

6.  Select the **Column search** check box to enable the column search for the eGiro free-text analysis. Enter the total number of characters to search for in the **Column width of text** field. Enter the string to use for the search criteria in the **Search string** field.

7.  Select the **Read first line** check box to review the first line as payment information in the eGiro free-text analysis. If you do not select this check box, the first line is considered to be the header information.

8.  Enter the start and end positions of the invoice for the eGiro free-text analysis in the **Invoice from position** and **Invoice to position** fields.

9.  Enter the start and end positions of the amount for the eGiro free-text analysis in the **Amount from position** and **Amount to position** fields.

10. Enter the start and end positions of the account number for the eGiro free-text analysis in the **Account from position** and **Account to position** fields.

11. Close the form to save your changes.

## See also

[(NOR) Set up the eGiro method of payment](nor-set-up-the-egiro-method-of-payment.md)

[(NOR) Set up eGiro parameters](nor-set-up-egiro-parameters.md)

[(NOR) Free text interpreter (form)](https://technet.microsoft.com/en-us/library/hh227597\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

