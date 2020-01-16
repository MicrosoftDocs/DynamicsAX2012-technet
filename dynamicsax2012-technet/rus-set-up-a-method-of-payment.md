---
title: (RUS) Set up a method of payment
TOCTitle: (RUS) Set up a method of payment
ms:assetid: 8099649d-8879-4a2d-ac6e-8518f799a69f
ms:mtpsurl: https://technet.microsoft.com/library/JJ678416(v=AX.60)
ms:contentKeyID: 49387646
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a method of payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The method of payment determines the format that is used for export of payment orders. Within the payment type, you can also set up bridging accounts when reconciliation is being done. In this case, when posting payment journals, the payments are reflected in off-balance Accounts payable and banking operations. After banking reconciliation, these transactions are reversed and reflected in Accounts payable and banking accounts. To link actual accounts with payment types, in most cases, the number of payment types created equals the number of accounts that the company holds.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a new line.

3.  In the **Method of payment** field, enter the code for the method of payment.

4.  In the **Description** field, enter a description for the method of payment.

5.  In the **Payment status** field, select the status for the payment line, which indicates the status for posting.

6.  On the **General** tab, in the **Account type** field, select the account type as **Bank**.

7.  In the **Payment account** field, select the bank account for payment.

8.  Select the **Bridging Posting** check box.
    

    > [!NOTE]
    > <P>You can enter information in the <STRONG>Bridging account</STRONG> field only after you select the <STRONG>Bridging Posting</STRONG> check box.</P>



9.  In the **Bridging account** field, select the account number for posting in the ledger.

10. In the **Bank transaction type** field, select the bank transaction type.

11. On the **File formats** tab, click **Setup** to open the **File formats for methods of payment** form.

12. Transfer formats from the **Available** field to the **Selected** field to generate a list of accessible formats for exporting payment orders.

13. Close the form and return to the **File formats** tab in the **Methods of payment** form.

14. In the **Export format** field, select the format for exporting payment orders for the specified method of payment.
    

    > [!NOTE]
    > <P>When using the customer-bank, the <STRONG>Export format</STRONG> field should show the class that handles the export of data for the payment journal to an external file in a format that corresponds to the customer-bank of the actual bank.</P>



15. On the **Payment control** tab, select the control for the method of payment from the following list:
    
      - **Payment reference is mandatory** – Checks that the essential details for the payment are filled in.
    
      - **Payment note is mandatory** – Checks that the note for the payment is filled in.
    
      - **Payment ID is mandatory** – Checks that the ID for the payment is filled in.
    
      - **Payment specification is mandatory** – Checks that the payment specification is filled in.
    
      - **Check number is mandatory** – Checks that the check number is filled in.
    
      - **Offset account has the type bank** – Checks that the type of corresponding account is **Bank**.
    
      - **Bank transaction type is mandatory** – Checks that a type of bank operation is selected.

16. Press CTRL+S or close the form.

## See also

[(RUS) Methods of payment (modified form)](https://technet.microsoft.com/library/jj665379\(v=ax.60\))

  


