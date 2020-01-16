---
title: (IND) Calculate sales tax in an Accounts receivable payment journal
TOCTitle: (IND) Calculate sales tax in an Accounts receivable payment journal
ms:assetid: 0e740d81-1f2c-42c0-a630-ac621755d4bd
ms:mtpsurl: https://technet.microsoft.com/library/JJ664488(v=AX.60)
ms:contentKeyID: 49385567
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate sales tax in an Accounts receivable payment journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N on the **Overview** tab to create a new journal.
    

    > [!NOTE]
    > <P>For more information, see "Journal header (form)" in the Applications and Business Processes Help.</P>



3.  Click **Lines** to open the **Journal voucher** form.

4.  Enter the required details on the **Overview** tab.
    

    > [!NOTE]
    > <P>For more information, see "Customer payment journal lines (form)" in the Applications and Business Processes Help.</P>



5.  Click the **General** tab.

6.  Select the account type as **Customer** in the **Account type** field in the **Account selection** field group.

7.  Select the sales tax group in the **Sales tax group** field.

8.  Select the group of sales tax codes that is calculated for an item in the **Item sales tax group** field. View the amount in the journal line in one of the following fields:
    
      - **Assessable value** – View or modify the net value of the journal line if the calculation of tax is based on the assessable value of the journal line.
    
      - **Max. retail price** – View or modify the value if the calculation of tax is based on the maximum retail price of the item.

9.  Select the offset account type as **Bank** in the **Offset account type** field.

10. Enter the credit amount in given currency in the **Credit** field.

11. Click the **Tax information** tab and select the address code in the **Name** field. The address of the company is displayed in the **Address** field and the sales tax registration number in the **Registration number** field.

12. Select the India sales tax form type in the **Form type** field.

13. Click **Sales tax** to open the **Temporary sales tax transactions** form. You can view the details of the sales tax amount of the transaction on the **Overview** tab.

14. Click the **Adjustment** tab to adjust the sales tax amount, if needed, and click **Apply**.

15. Click **Formula designer** to open the **Formula designer** form. View the calculation expression that is defined for each tax code in the item sales tax sales group. The fields in this form cannot be modified.

16. Close the **Formula designer** form and the **Temporary sales tax transactions** form to return to the **Payment journal** form.

17. Post the journal.

## See also

[(IND) Journal voucher - General journal (modified form)](https://technet.microsoft.com/library/jj678053\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

  


