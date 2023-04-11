---
title: (RUS) Register reimbursement or disbursement slips
TOCTitle: (RUS) Register reimbursement or disbursement slips
ms:assetid: 58909a5c-4c65-4bb5-80c5-b197d51fdbfc
ms:mtpsurl: https://technet.microsoft.com/library/JJ665402(v=AX.60)
ms:contentKeyID: 49387490
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Register reimbursement or disbursement slips 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must create a cash journal to register cash reimbursement and disbursement slips.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can generate a cash reimbursement slip when you confirm a cash receipt in the **Journal voucher** form. When you confirm a cash expenditure in the same form, you can generate a cash disbursement slip. You can register all the cash transactions in a cash journal, and then post and print a cash reimbursement or cash disbursement slip after the cash voucher is approved.

1.  Click **Cash and bank management** \> **Journals** \> **Slip journal**.

2.  Press CTRL+N to create a new journal batch.

3.  Click **Lines** to open the **Journal voucher** form.

4.  In the **Date** field, enter the date of reimbursement or disbursement.

5.  In the **Account** field, select the account in which the cash transaction is to be registered.

6.  In the **Transaction text** field, enter a description for the transaction.

7.  Enter the cash amount in the **Debit** field if the receipt is registered for a cash reimbursement slip, or in the **Credit** field if the expense is registered for a cash disbursement slip.
    

    > [!NOTE]
    > <P>The total amount of all cash reimbursement slips and cash disbursement slips entered in the current journal is displayed in the <STRONG>Reimb</STRONG> field and the <STRONG>Disb</STRONG> field.</P>



8.  In the **Offset account type** and **Offset account** fields, select an offset account type for the cash transactions and an offset account for the offset account type.

9.  In the **Currency** field, select a currency code. The currency entered for the cash account is displayed by default.

10. In the **Order number** field, the slip number selected in the number sequence group for the cash account is automatically displayed. You can enter a different value, if required.

11. In the **Document type** field, one of the following values is displayed:
    
      - **Cash reimbursement slip** − The line amount is entered as **Debit**.
    
      - **Cash disbursement slip** − The line amount is entered as **Credit**.
    
      - **Correction** − The line amount is entered as a negative amount.

12. Click the **General** tab to enter the reimbursement or disbursement details for the customer or vendor.
    

    > [!NOTE]
    > <P>You can select the <STRONG>Offset account type</STRONG> as <STRONG>Vendor</STRONG> or <STRONG>Customer</STRONG>.</P>



13. In the **Contracts Group** and the **DVR** fields, enter the contract group and the contract registration number to the cash transaction that was received or disbursed.

14. Click the **Dimensions** tab, and then assign the dimension codes.

15. Click the **Cash Order** tab, and then enter the following information about the counteragent representative:
    
      - In the **Reason** field, enter the reason for the reimbursement or disbursement.
    
      - In the **Document** and the **Document Date** fields, enter the document number and the document date for the cash document.
    
      - In the **Representative type** field, select the type of representative as **Employee**, **Other**, **Vendor**, or **Customer**.
    
      - In the **Representative** field, select the representative for the option selected in the **Representative type** field.
    

    > [!NOTE]
    > <P>If you select <STRONG>Adv. holder</STRONG> in the <STRONG>Offset account type</STRONG> field and the employee code in the <STRONG>Offset account</STRONG> field, then all the details related to the employee are displayed in the <STRONG>Representative</STRONG> field group.</P>



16. Click the **Officials** tab to select the approval authority. Select the positions of the director, the chief accountant, and the cashier in the **Position** field. The employee names and the job titles are displayed with values from the corresponding fields in the **Officials** form.

17. Click the **Payment** tab, and enter the following information:
    
      - In the **Note** field, enter comments about the transaction, such as numbers and dates of relevant documents that the cash transaction is based on.
    
      - Select the **Prepayment** check box, if the payment is a prepayment.
    
      - In the **Posting Profile** field, select the posting profile for the cash account. The default value in the **Cash Posting Profiles** form is displayed (**Bank** \> **Setup** \> **Cash Posting Profiles**).
    
      - In the **Offset Posting Profile** field, select the posting profile for the corresponding account.

## See also

[(RUS) Cash accounts (form)](https://technet.microsoft.com/library/jj665230\(v=ax.60\))

  


