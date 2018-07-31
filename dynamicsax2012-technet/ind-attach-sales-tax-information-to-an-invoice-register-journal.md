---
title: (IND) Attach sales tax information to an Invoice register journal
TOCTitle: (IND) Attach sales tax information to an Invoice register journal
ms:assetid: ba3c890f-704a-43df-8c8b-5e05cc78dbed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664840(v=AX.60)
ms:contentKeyID: 49386170
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Attach sales tax information to an Invoice register journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.

2.  Click **Lines** to open the **Journal voucher** form.

3.  Press CTRL+N on the **Overview** tab to create a new line.

4.  Enter the required details to create a new journal.

5.  Click the **General** tab and select a purchase order in the **Purchase order** field.

6.  Select the sales tax group in the **Sales tax group** field.

7.  Select the group of sales tax codes that is calculated for an item in the **Item sales tax group** field.

8.  You can view the amount in the journal line in one of the following fields, based on the taxable basis that is defined:
    
      - **Assessable value** – You can view the amount in the journal line updated in the **Assessable value** field. Modify the assessable value, if it is required. If the taxable basis for a common tax code is defined as assessable value in the formula designer, the calculation of that tax code is based on the value in the **Assessable value** field.
    
      - **Max. retail price** – Enter a value in the **Max. retail price** field, if the taxable basis for a common sales tax code is set as Max. retail price in the **Formula designer** form.
    

    > [!NOTE]
    > <P>The debit or credit type of value in the <STRONG>Assessable value</STRONG> field or the <STRONG>Max. retail price</STRONG> field is based on the value in the <STRONG>Debit</STRONG> field or the <STRONG>Credit</STRONG> field in which the journal line amount is entered, with or without the negative (–) sign.</P>



9.  Click **Sales tax** to open the **Temporary sales tax transactions** form. The details of the sales tax amount of the transaction are displayed on the **Overview** tab.

10. Click the **Adjustment** tab to adjust the sales tax amount, if it is required, and click **Apply**.

11. Click **Formula designer** to open the **Formula designer** form.

12. In the **Formula designer** form, you can view the calculation expression that is defined for each tax code in the item sales tax group.

13. Close the form to return to the **Invoice register** form.

14. Validate and post the journal.

## See also

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

  


