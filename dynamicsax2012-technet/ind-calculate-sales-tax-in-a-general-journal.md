---
title: (IND) Calculate sales tax in a general journal
TOCTitle: (IND) Calculate sales tax in a general journal
ms:assetid: 9e4a27c0-29f8-4b54-8c4c-a8609d58469c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664733(v=AX.60)
ms:contentKeyID: 49386064
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate sales tax in a general journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N on the **Overview** tab to create a new journal.

3.  Click **Lines** to open the **Journal voucher** form.

4.  Select the type of account in the **Account type** field.

5.  Select the ledger account for sales tax in the **Account** field.

6.  Enter the amount of the transaction in the **Debit** field or the **Credit** field.

7.  Select the type of offset account in the **Offset type account** field.

8.  Select the offset account for the journal in the **Offset account** field.

9.  Select the sales tax group in the **Sales tax group** field.

10. Select the group of sales tax codes that is used to calculate tax for an item in the **Item sales tax group** field.

11. Select the sales tax form type in the **India sales tax form type** field.

12. Click the **General** tab. You can view the amount in the journal line in one of the following fields, based on the taxable basis defined:
    
      - **Assessable value** – The value of the journal line is displayed automatically in this field if the calculation of tax is based on the assessable value of the journal line. For example, if a journal line is created for INR 1,000.00 in the **Debit** field, the **Assessable value** field displays the line amount of INR 1,000.00, for which the tax is calculated.
    
      - **Max. retail price** – Enter the value if the basis of calculation for sales tax is on the maximum retail price of the item.

13. Click the **Tax information** tab. Select the address code in the **Name** field. The address of the company is displayed in the **Address** field. The tax registration number that is attached to the company is displayed in the **Registration number** field.

14. Click **Sales tax** to open the **Temporary sales tax transactions** form, where you can view the details of the sales tax amount for the tax code.

15. Click the **Adjustment** tab to adjust the sales tax amount, if needed, and click **Apply**.

16. Click **Formula designer** to open the **Formula designer** form. View the calculation expressions that are defined for the item sales tax group that is selected for the journal. The fields in this form cannot be modified. The sequence of calculation of the tax codes and the basis of calculation of each tax code is determined by the formula that is defined for the selected item sales tax group.

17. Close the **Formula designer** form and the **Temporary sales tax transaction** form to return to the **Journal** form.

18. Post the transaction. The account that is selected in the **Account** field is debited. The offset account that is selected in the **Offset account** field is credited. Conversely, if the **Account** field is credited, the offset account is debited. The sales tax amount is credited to the payable account or debited to the expense account, depending on whether the amount is entered in the **Credit** field or the **Debit** field of the journal line.

## See also

[(IND) Journal voucher - General journal (modified form)](https://technet.microsoft.com/en-us/library/jj678053\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

  


