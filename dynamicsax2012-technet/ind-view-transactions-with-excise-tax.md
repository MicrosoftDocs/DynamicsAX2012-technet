---
title: (IND) View transactions with excise tax
TOCTitle: (IND) View transactions with excise tax
ms:assetid: ada58c70-f8a7-4de4-b225-adc5a9594447
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664792(v=AX.60)
ms:contentKeyID: 49386122
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) View transactions with excise tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Excise inquiry** form to view all transactions for the selected Excise Control Code (ECC) number and the tax settlement period. You can also use this form to run queries for the date of issue or receipt of goods, type of excise register specified for a transaction, and transactions with direct settlement to an excise register. The **Excise** check box must be selected on the Sales tax area in the **General ledger parameters** form. (Click **General ledger** \> **Setup** \> **General ledger parameters**.)


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise**.

2.  In the **Excise inquiry** form, select the query to modify in the **Select query** field.

3.  Click **Modify** to modify, save, or delete the current query.

4.  Select the ECC number for the company's address in the **ECC number** field.

5.  Enter the tax settlement period for the selected ECC number in the **Tax settlement period** field.

6.  Select the starting date in the **From date** field and the ending date in the **To date** field.

7.  Select the required fields from the **Available** list.

8.  Click **\>** to add items from the **Available** to the **Selected** list.

9.  Click **\<** to remove items from the **Selected** list.

10. Click **Top**, **Up**, **Down**, or **Bottom** to rearrange the order of items.

11. Select or clear the **Header note** check box to indicate whether the header note must be defined and displayed, and then enter the text for the header note in the **Header note** field, if needed.

12. Select or clear the **Footer note** check box to indicate whether the footer note must be defined and displayed, and then enter the text for the footer note in the **Footer note** field, if needed.

13. Click **Inquiry** to create or update the selected query in the **Inquiry** form.

14. Click **Total** to select the amount-related fields that are to be totaled. Only the amount-related fields that are in the **Selected** list can be added in this form. Close the **Total** form.

15. Click **OK** to open the **Excise transactions** form, where you can view the details of the inquiry.

16. You can click the following buttons in the **Excise transactions** form to view additional information:
    
      - **Voucher** - Opens the **Voucher transactions** form, where you can view ledger account details.
    
      - **Totals** - Opens the **Totals - Excise** form, where you can view the total amount.
    
      - **Tax components** - Opens the **Tax components - Excise** form, where you can view excise tax information for the tax components and currency details.
    
      - **Misc. charges** - Opens the **Misc. charges transactions** form, where you can view the details of the miscellaneous charges transactions.

17. Close the **Excise transactions** form.

## See also

[(IND) Excise inquiry (form)](https://technet.microsoft.com/en-us/library/jj664652\(v=ax.60\))

[(IND) Totals - Excise (form)](https://technet.microsoft.com/en-us/library/jj710981\(v=ax.60\))

[(IND) Excise transactions (form)](https://technet.microsoft.com/en-us/library/jj664581\(v=ax.60\))

[(IND) Tax components - Excise (form)](https://technet.microsoft.com/en-us/library/jj677960\(v=ax.60\))

  


