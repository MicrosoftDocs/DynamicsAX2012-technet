---
title: (IND) View VAT transaction information
TOCTitle: (IND) View VAT transaction information
ms:assetid: bd239fe5-14f1-4069-a3e9-bbd0018ab832
ms:mtpsurl: https://technet.microsoft.com/library/JJ664825(v=AX.60)
ms:contentKeyID: 49386156
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) View VAT transaction information 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can complete this procedure, the **VAT** check box must be selected in the **General ledger parameters** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **VAT** \> **VAT**.

2.  Select the query to modify in the **Select query** field.

3.  Click **Modify...** to modify, save, or delete the current query.

4.  Select the Tax Identification Number (TIN) for the company's address in the **Tax Identification Number (TIN)** field.

5.  Enter the tax settlement period for the selected TIN number in the **Tax settlement period** field.

6.  Select the starting date in the **From date** field and the ending date in the **To date** field.

7.  Select the required fields from the **Available** list.

8.  Click **\>** to add items from the **Available** to the **Selected** list.

9.  Click **\<** to remove items from the **Selected** list.

10. Click **Top**, **Up**, **Down**, or **Bottom** to rearrange the order of items.

11. Select or clear the **Header note** check box to indicate whether the header note must be defined and displayed, and then enter the text for the header note in the **Header note** field, if needed.

12. Select or clear the **Footer note** check box to indicate whether the footer note must be defined and displayed, and then enter the text for the footer note in the **Footer note** field, if needed.

13. Click **Inquiry** to create or update the selected query in the **Inquiry** form.

14. Click **Total** to select the amount fields that are to be totaled. Only the amount-related fields that are in the **Selected** list can be added in this form. Close the **Total** form.

15. Click **OK** to open the **VAT transactions** form, where you can view the details of the inquiry.

16. You can click the following buttons in the **VAT transactions** form.
    
      - **Voucher** - Open the **Voucher transactions** form, where you can view ledger account details.
    
      - **Totals** - Open the **Totals - VAT** form, where you can view the total amount.
    
      - **Tax components** - Open the **Tax component - VAT** form, where you can view VAT amount information for the tax components and currency details.
    
      - **Charges** - Open the **Charges transactions** form, where you can view the details of the charges transactions.
    
      - **Deferment schedule** - Open the **Deferment schedule** form, where you can view the terms of the deferment schedule and the installments for the transaction line.

17. Close the **VAT transactions** transactions form.

## See also

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj677901\(v=ax.60\))

[(IND) VAT inquiry (form)](https://technet.microsoft.com/library/jj710930\(v=ax.60\))

[(IND) VAT transactions (form)](https://technet.microsoft.com/library/jj677920\(v=ax.60\))

  


