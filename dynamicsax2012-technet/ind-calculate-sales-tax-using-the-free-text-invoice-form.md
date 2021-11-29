---
title: (IND) Calculate sales tax using the free text invoice form
TOCTitle: (IND) Calculate sales tax using the free text invoice form
ms:assetid: 2f81e541-0186-4357-81b2-a49a6a4151af
ms:mtpsurl: https://technet.microsoft.com/library/JJ664597(v=AX.60)
ms:contentKeyID: 49385674
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate sales tax using the free text invoice form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Press CTRL+N on the **Overview** tab to create a new line.

3.  Select the account number of the customer.

4.  Click the **Invoice** tab.

5.  Select the sales tax group in the **Sales tax group** field.

6.  Select the sales tax codes for the item sales tax group in the **Item sales tax group** field.

7.  Click the **Address** tab and enter the address of the customer.

8.  Click the **Invoice lines** tab to create an invoice line.

9.  Select the offset ledger account in the **Ledger account** field.

10. View or modify the sales tax group in the **Sales tax group** field.

11. View or modify the item sales tax group for calculation of sales tax on the invoice line in the **Item sales tax group** field.

12. Enter the amount of the invoice line in the **Amount** field.

13. Select the sales tax form type in the **India sales tax form type** field. You can view or modify the amount in the order line in one of the following fields, based on the taxable basis defined:
    
      - **Assessable value** – The value of the item in the order line is displayed automatically in this field. The calculation of tax is based on the assessable value of the transaction line.
    
      - **Max. retail price** – Enter the value if the basis of calculation for sales tax is on the maximum retail price of the transaction line.

14. Click the **Tax information** tab. Select the address code in the **Name** field. The address of the company is displayed in the **Address** field. The tax registration number that is attached to the company is displayed in the **Registration number** field.

15. Click **Setup** and select the **Sales tax** option to open the **Temporary sales tax transactions** form. You can view the sales tax calculation on the **Overview** tab.

16. Click the **Adjustment** tab to adjust the sales tax amount, if needed, and click **Apply**.

17. Click **Formula designer** to open the **Formula designer** form. View the calculation expression that is defined for each tax code in the item sales tax sales group. You cannot modify the fields in this form.

18. Close the **Formula designer** form and the **Temporary sales tax transactions** form to return to the **Free text invoice** form.

19. Post the invoice.

## See also

[(IND) Free text invoice (modified form)](https://technet.microsoft.com/library/jj664875\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

  


