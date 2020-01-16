---
title: (IND) Create a tax journal for service tax
TOCTitle: (IND) Create a tax journal for service tax
ms:assetid: 9499ef53-09ae-4fb6-ab92-3b9ec3655e70
ms:mtpsurl: https://technet.microsoft.com/library/JJ678068(v=AX.60)
ms:contentKeyID: 49386029
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create a tax journal for service tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can transfer the opening balances of service tax components to the tax component ledger accounts or post adjustment entries between the tax components by using the **Tax journal** form.


> [!NOTE]
> <P>According to the legal requirement for service tax, you do not have to create a tax journal for the <STRONG>Service tax</STRONG> tax type. However, you can create a tax journal for transferring opening balances to ledger posting accounts or to make any adjustments between the tax components.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Select **Service tax** in the **Tax type** field.

3.  Select the tax ledger posting group for service tax in the **Tax ledger posting group** field.

4.  Select the service registration number in the **Tax registration number** field.

5.  Enter the date that the opening balance amounts are posted on in the **To date** field.

6.  Select the service tax component that the opening balance amount must be transferred to in the **Tax component** field.

7.  Select the ledger account that the opening balance amount is posted from in the **Account** field. If you enter a negative amount, the tax amount is deducted from the ledger account that you specify in this field, and if you enter a positive amount, the tax amount is added to the ledger account.

8.  Enter the starting balance amount in the **Amount** field. Enter a negative value if the amount is credit type and a positive value for the debit type amount.

9.  Select the tax code that the service tax component is attached to in the **Tax code** field.

10. Click **Transfer** to transfer the tax journal record to the **Journal voucher** form.

11. View the details of the tax journal record that is transferred in the **Journal voucher** form.

12. Select the ledger account that the opening balance transaction is posted to in the **Offset account** field. If you enter a negative amount in the **Amount** field in the **Tax journal** form, the tax amount is transferred to the ledger account that you specify in this field, and if you enter a positive amount, the tax amount is deducted from the ledger account.

13. Validate and post the journal.

## See also

[(IND) Tax journal ( form)](https://technet.microsoft.com/library/jj664732\(v=ax.60\))

[(IND) Journal voucher - General journal (modified form)](https://technet.microsoft.com/library/jj678053\(v=ax.60\))

  


