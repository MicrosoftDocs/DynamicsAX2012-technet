---
title: (IND) View an excise register
TOCTitle: (IND) View an excise register
ms:assetid: 081ef3d2-f4ec-4db6-afbc-d7fb6cd89bab
ms:mtpsurl: https://technet.microsoft.com/library/JJ664455(v=AX.60)
ms:contentKeyID: 49385534
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) View an excise register 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Several types of inquiries are available for excise registers. Select the parameters, such as the Excise Control Code (ECC) number, excise settlement period, date range, and excise register, in the **Excise register inquiry** form. When you click **OK** in the **Excise register inquiry** form, a **Transactions** form displays excise information. The name of the **Transactions** form depends on the excise register that you select in the **Register** field in the **Excise register inquiry** form.

1.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

2.  In the **Excise registers balance inquiry** form, in the **Select query** field, select a query to modify, or enter a new query.

3.  In the **ECC number** field, select the Excise Control Code number.

4.  In the **Sales tax settlement period** field, select the settlement period for sales tax.

5.  In the **Register** field, select the excise register. The following options are available:
    
      - **RG23A Part - I** – View the quantitative details of the input items that are received at the warehouse, and the quantity that is issued for production and for clearance from the RG23A register.
    
      - **RG23A Part - II** – View the details of excise taxes. These details include the credit that is used by the manufacturer, the excise credit that is used by the manufacturer against the clearance of final products, and the credit balance that is available.
    
      - **RG23C Part - I** – View the quantitative details of capital items.
    
      - **RG23C Part - II** – View the excise recoverable details that are calculated on the capital items.
    
      - **RG23D** – View the excise details of the purchase and sale of items by the trader. You can view the excise details according to quantity and the excise duty that is applied.
    
      - **PLA** – View the excise details of the personal ledger account for the excise duty that is deposited by the manufacturer against the clearance of the excisable items.
    
      - **DSA** – View the excise details of the daily stock register. These details include the description of the manufactured items, the opening balance of the quantity of items, the quantity of manufactured items, and the details of the duty that is paid for the finished items.

6.  Select the starting date and the ending date. This date range must be in the date range of the settlement period for sales tax. All the transactions for the selected date range are displayed in the **Transactions** form for the excise register that you select in the **Register** field.

7.  In the **Available** list, select the fields to display in the **Transactions** form for the specified excise register, and then move the fields to the **Selected** list.
    

    > [!NOTE]
    > <P>You cannot remove the <STRONG>Date</STRONG>, <STRONG>Voucher</STRONG>, and <STRONG>Excise tariff code</STRONG> fields from the <STRONG>Selected</STRONG> list. You can move a maximum of 47 fields from the <STRONG>Available</STRONG> list to the <STRONG>Selected</STRONG> list.</P>



8.  Select the **Header note** check box to enter the text for a header note. Then enter the text for the header note in the **Header note** field. The header note is displayed in the **Transactions** form for the specified excise register.

9.  Select the **Footer note** check box to enter the text for a footer note. Then enter the text for the footer note in the **Footer note** field. The footer note is displayed in the **Transactions** form for the specified excise register.

10. Click **Inquiry** to define the values that must be displayed in the fields in the **Transactions** form for the specified excise register.

11. Close the **Inquiry** form.

12. In the **Excise register inquiry** form, click **Modify...** to save or delete the query.

13. In the **Excise register inquiry** form, click **OK** to open the **Transactions** form for the specified excise register. The fields in this form are displayed in the order that you specify in the **Excise register inquiry** form. The data that is displayed in these fields is based on the information in the **Inquiry** form. You can view all the transactions, which are filtered by the ECC number, tax settlement period, date range, and excise register, based on criteria that you specify.

## See also

[(IND) Excise register inquiry (form)](https://technet.microsoft.com/library/jj710979\(v=ax.60\))

[(IND) Transactions (form)](https://technet.microsoft.com/library/jj664764\(v=ax.60\))

  


