---
title: (IND) Calculate sales tax in an invoice approval journal
TOCTitle: (IND) Calculate sales tax in an invoice approval journal
ms:assetid: 9d03ab86-8b71-4c5c-852f-238c4f63a948
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664727(v=AX.60)
ms:contentKeyID: 49386058
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate sales tax in an invoice approval journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

2.  Click **Lines** to open the **Journal voucher** form.

3.  Press CTRL+N on the **Overview** tab to create a new journal.

4.  Click **Fetch vouchers** to select a voucher.

5.  Click **OK** to close the form. The details of the voucher from the **Invoice register** form is displayed in the invoice approval journal line on the **Overview** tab.

6.  In the **Journal voucher** form, click the **General** tab.

7.  Select the sales tax group in the **Sales tax group** field.

8.  In the **Item sales tax group** field, select the group of sales tax codes that is used to calculate tax for an item. View the amount in the journal line in one of the following fields, based on the taxable basis defined.
    
      - **Assessable value** – The value of the journal line in the order line is displayed automatically in this field. The calculation of tax is based on the assessable value of the journal line.
    
      - **Max. retail price** – Enter the value if the basis of calculation for sales tax is on the maximum retail price of the item in the order line.

9.  Click the **Tax information** tab and select the address code in the **Name** field. The address of the company is displayed in the **Address** field and the tax registration number of the company in the **Registration number** field.

10. Select the India sales tax form type in the **Form type** field.

11. Click **Sales tax** to open the **Temporary sales tax transactions** form. The details of the sales tax amount for the transaction are displayed on the **Overview** tab.

12. Click the **Adjustment** tab to adjust the sales tax amount, if needed, and click **Apply**.

13. Click **Formula designer** to open the **Formula designer** form. View the calculation expression that is defined for each tax code in the item sales tax sales group. The fields in this form cannot be modified.

14. Close the **Formula designer** form and the **Temporary sales tax transactions** form to return to the **Invoice approval journal** form.

15. Click **Functions** \> **Purchase order** to post the voucher.

## See also

[(IND) Journal voucher - Invoice approval journal (modified form)](https://technet.microsoft.com/en-us/library/jj678033\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

  


