---
title: (FRA) Generate a bill of exchange remittance file
TOCTitle: (FRA) Generate a bill of exchange remittance file
ms:assetid: f6ee8359-2083-43a9-9a1c-0430acae76fe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243292(v=AX.60)
ms:contentKeyID: 36060021
ms.date: 04/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: France
---

# (FRA) Generate a bill of exchange remittance file 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use a **Remittance journal** to generate a bill of exchange remittance file for transactions that are posted, but that you have not generated a bill of exchange remittance file for.

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Remittance journal**.

2.  Select or create a customer remittance journal.

3.  On the **Bill of exchange** tab, in the **Remittance type** field, select **Discount**.

4.  In the **Bank account** field, select the bank account that is affected by the bill of exchange. The bank account must use the standard French bank account number.

5.  Click **Lines**, and then click **Functions** \> **Generate remittance** to open the **Generate remittance** form.

6.  In the **Payment method** field, select a method of payment that uses the **French bill of exchange remittance** remittance format, and then click **Dialog** to open the **Dialog** form.

7.  In the **Remittance date** field, select the date when the file is to be remitted. The date is included in the remittance file.

8.  In the **Discount type** field, select the discount type for the remittance file.

9.  In the **Value date** field, select the date when the payment must be remitted to be eligible for the discount.

10. In the **File name** field, enter the path and file name where the remittance file is created.
    

    > [!NOTE]
    > <P>If you selected <STRONG>Collection</STRONG> in the <STRONG>Remittance type</STRONG> field, you must specify the remittance date, the file name, and the file path to create the bill of exchange remittance file in the <STRONG>Dialog</STRONG> form.</P>



11. Select the **Control report** check box to print a control report when the remittance file is generated.

12. Click **OK** to generate the bill of exchange remittance file. If the **Control report** check box is selected, a control report is printed.

You can print a remittance file for customers by clicking **File** \> **Print** \> **Print…** in the **Remittance files for customers** form. For more information, see [Remittance files for customers (form)](https://technet.microsoft.com/en-us/library/aa596345\(v=ax.60\)).

## See also

[View remittance files for customers](view-remittance-files-for-customers.md)

[Set up bills of exchange](set-up-bills-of-exchange.md)

  


