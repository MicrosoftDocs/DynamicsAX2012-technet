---
title: (IND) Post purchase transactions of excise using the Invoice approval journal form
TOCTitle: (IND) Post purchase transactions of excise using the Invoice approval journal form
ms:assetid: 9f1bc90e-d89f-4b94-847e-004208508558
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664718(v=AX.60)
ms:contentKeyID: 49386048
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Post purchase transactions of excise using the Invoice approval journal form 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you fetch a voucher from the invoice register journal and post it in the invoice approval journal, the taxes posted in the invoice register journal are reversed. When you credit the vendor account and debit the ledger account, the excise amounts calculated will be debited to the accounts as defined in the tax ledger posting group for the ECC number.

The excise register Part II is updated with the excise amount according to the type of register that you select in the **Excise record type** field on the **Tax information** tab in the **Invoice approval journal** form.

The ledger accounts that will be debited with the excise amounts will depend on the excise record type that you select in the **Excise record type** field.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

2.  Press CTRL+N to create a new journal and click the **Lines**.

3.  Click **Fetch vouchers** to fetch the voucher or vouchers posted in the invoice register journal.

4.  Click the **General** tab. Select the sales tax group in the **Sales tax group** field and the item sales tax group in the **Item sales tax group** field.

5.  Enter the amounts in the **Assessable value** field or the **Max. retail price** field.
    

    > [!NOTE]
    > <P>If the <STRONG>Taxable basis</STRONG> is <STRONG>Assessable</STRONG> or <STRONG>Max.retail price</STRONG>, modify the <STRONG>Assessable value</STRONG> and <STRONG>Max.retail price.</STRONG></P>



6.  Click the **Tax information** tab.

7.  Select the ECC number of the company in the **ECC number** field.

8.  Select the excise tariff code in the **Excise tariff codes** field.

9.  Select the type of excise record in the **Excise record type** field.

10. Click **Sales tax** to view the calculation of excise in the **Temporary sales tax transactions** form.

11. Validate and post the journal.

## See also

[(IND) Journal voucher - Invoice approval journal (modified form)](https://technet.microsoft.com/en-us/library/jj678033\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

