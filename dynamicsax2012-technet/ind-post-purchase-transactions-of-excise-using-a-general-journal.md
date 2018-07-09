---
title: (IND) Post purchase transactions of excise using a general journal
TOCTitle: (IND) Post purchase transactions of excise using a general journal
ms:assetid: 7bf559d8-0910-4956-982b-b0cd4be2c2dd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677931(v=AX.60)
ms:contentKeyID: 49385894
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Post purchase transactions of excise using a general journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new journal and click **Lines**.

3.  Enter the details for the voucher line on the **Overview** tab in the **Journal voucher** form.

4.  In the lower pane, select the excise tariff code for the transaction in the **Excise tariff code** field.

5.  Click the **General** tab. Select the sales tax group in the **Sales tax group** field and the item sales tax group in the **Item sales tax group** field.
    

    > [!NOTE]
    > <P>The sales tax group and the item sales tax group for a journal line must have common tax codes of the <STRONG>Excise</STRONG> tax type.</P>



6.  Modify the amount in the **Assessable value** field, if required.
    

    > [!NOTE]
    > <P>Assessable value is one of the base values that the excise duty can be calculated on. The amount that is entered in the journal line, either in the <STRONG>Credit</STRONG> or <STRONG>Debit</STRONG> field, is displayed in the <STRONG>Assessable value</STRONG> field.</P>



7.  Modify the amount for the maximum retail price of the item in the **Max. retail price** field. The maximum retail price is one of the base values that the excise duty can be calculated on.

8.  Click the **Tax information** tab. You can view the name and current address of the company. You can modify the value in the **Name** field.

9.  Select the excise registration number of the company in the **ECC number** field. The ledger accounts to post the excise tax amounts are identified, based on the ECC number. The excise registration number is based on the value that you select in the **Name** field and if the registration number is attached to the address.

10. Select the type of excise register in the **Excise record type** field. If the excise category is **Trader** for the address of the company that you selected, you can select from the following options in the **Excise record type** field:
    
      - **None**
    
      - **RG23D**

11. Click the **Sales tax** to view the calculation of excise in the **Temporary sales tax transactions** form.

12. Click the **Formula designer** to view the formula that is defined for each excise tax component for an item sales tax group for the calculation of excise.

13. Post the journal. The Excise Register - Part II is updated with the excise amount.

## See also

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

