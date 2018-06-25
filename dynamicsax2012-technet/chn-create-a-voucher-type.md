---
title: (CHN) Create a voucher type
TOCTitle: (CHN) Create a voucher type
ms:assetid: e0750f01-5b9c-4c61-bac7-f6afb08be9f7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664122(v=AX.60)
ms:contentKeyID: 49384704
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Create a voucher type [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Voucher type setup** form to set up voucher types. You can set up rules to validate the accounts that are used for a voucher type.


> [!NOTE]
> <P>The <STRONG>Voucher type setup</STRONG> form is available only if you select the <STRONG>Chinese voucher system</STRONG> check box in the <STRONG>General ledger parameters</STRONG> form.</P>



1.  Click **General ledger** \> **Setup** \> **Journals** \> **Voucher type setup** \> **Voucher type**.

2.  Click **New** to create a voucher type.

3.  In the **Voucher type** field, enter the unique identification code for the selected voucher type.

4.  In the **Description** field, enter a description for the selected voucher type.

5.  In the **Voucher type number** field, enter a number for the selected voucher type.

6.  In the **Priority** field, enter a priority for the selected voucher type. Priority values range from 1 to 5.

7.  Select the **Default** check box to specify that the voucher type is used by default during posting whenever you cannot indicate a voucher type, such as during the posting of sales invoices or production orders.
    

    > [!NOTE]
    > <P>You can assign only one default reference for each voucher type.</P>



8.  On the **General** tab, in the **Number sequence code** field, select the default number sequence for the voucher type.

9.  In the **Print layout group** field, select the default print layout group that is used for the voucher type when the voucher is printed by using the **General journal** form. You can set up print layout groups in the **Print layout** form. For more information, see [(CHN) Print layout (form)](https://technet.microsoft.com/en-us/library/jj664037\(v=ax.60\)).

10. In the **Name** field, select the name of the default journal.

11. In the **Default prepared by** field, select the name of the person who prepared the voucher. This name is printed on the Chinese voucher report.

12. In the **Default approved by** field, select the name of the person who approved the voucher.

13. On the **Rules** tab, click **Add** to open the **Select voucher type rule** form, where you can select a rule to validate the accounts that are used for the selected voucher type.

14. Click **OK** to add the selected rule to the **Restriction** field.

15. In the **Account type** field, select the account type to use for the selected restriction.

16. In the **Main account** field, select the ledger account for the account type.

## See also

[(CHN) Voucher type setup (form)](https://technet.microsoft.com/en-us/library/jj664036\(v=ax.60\))

[(CHN) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj664137\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

