---
title: (LVA) Set up validation and numbering for bank account numbers
TOCTitle: (LVA) Set up validation and numbering for bank account numbers
ms:assetid: 8513df5e-15de-449c-bfd2-5d5da83c1e17
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ721425(v=AX.60)
ms:contentKeyID: 49729988
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LVA) Set up validation and numbering for bank account numbers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up and validate bank account numbers, based on the account number format that is used in Latvia.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Press CTRL+N to create a new bank account and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Bank accounts (form)" in the Applications and Business Processes Help.</P>



3.  In the **Bank account** field, enter the bank account number.

4.  In the **Corr. bank account** field, enter the correspondence bank account number if the bank has a correspondence bank account.

5.  Click the **Currency management** FastTab.

6.  Select the **Default** check box to set up the bank account as the default bank account for a specific currency.

7.  In the **Payment order form** field, select the layout for the bank payment order from the following options:
    
      - **Local** – Print the payment order in local currency.
    
      - **Currency** – Print the payment order in foreign currency.

8.  In the **P/O numeration** field, select the number sequence code for payment orders that are printed for the bank account.
    

    > [!NOTE]
    > <P>Each currency can be assigned one bank account as its default bank account.</P>



9.  Press CTRL+S or close the form.

## See also

[(LVA) Bank accounts (modified form)](https://technet.microsoft.com/en-us/library/jj721426\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

