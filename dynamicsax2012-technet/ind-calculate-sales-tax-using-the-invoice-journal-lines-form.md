---
title: (IND) Calculate sales tax using the Invoice journal lines form
TOCTitle: (IND) Calculate sales tax using the Invoice journal lines form
ms:assetid: 1fd2c638-0dd9-4b56-a9a8-253e34af3535
ms:mtpsurl: https://technet.microsoft.com/library/JJ664544(v=AX.60)
ms:contentKeyID: 49385623
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate sales tax using the Invoice journal lines form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Press CTRL+N to create a journal.

3.  Enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Invoice journal lines (form)" and "Journal header (form)" in the Applications and Business Processes Help.</P>



4.  Select the sales tax form type in the **India sales tax form type** field.

5.  Click the **General** tab.

6.  Select the sales tax group in the **Sales tax group** field.

7.  Select the group of sales tax codes that is used to calculate tax for an item in the **Item sales tax group** field. You can view the amount in the journal line in one of the following fields based on the taxable basis:
    
      - **Assessable value** – The value of the journal line is displayed automatically in this field. The calculation of tax is based on the assessable value of the journal line.
    
      - **Max. retail price** – Enter the value if the basis of calculation for sales tax is on the maximum retail price of the value of the journal line.

8.  Click the **Tax information** tab. Select the address code in the **Name** field. The address of the company is displayed in the **Address** field. The tax registration number that is attached to the company is displayed in the **Registration number** field.

9.  Click **Sales tax** to open the **Temporary sales tax transactions** form, where you can view the details of the sales tax amount for the tax code.

10. Click the **Adjustment** tab to adjust the sales tax amount, if needed, and click **Apply**.

11. Click **Formula designer** to open the **Formula designer** form. View the calculation expressions that are defined for the item sales tax group that is selected for the journal. The fields in this form cannot be modified. The sequence of calculation of the tax codes and the basis of calculation of each tax code is determined by the formula that is defined for the selected item sales tax group.

12. Close the **Formula designer** and the **Temporary sales tax transaction** form to return to the **Journal voucher** form.

13. Post the invoice.

## See also

[(IND) Journal voucher - Invoice journal (modified form)](https://technet.microsoft.com/library/jj664791\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

  


