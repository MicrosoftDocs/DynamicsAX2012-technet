---
title: (HUN) Create and submit the EU sales list
TOCTitle: (HUN) Create and submit the EU sales list
ms:assetid: b2583bc2-55fe-4b2b-a3bc-da9ef3fb34dd
ms:mtpsurl: https://technet.microsoft.com/library/JJ728744(v=AX.60)
ms:contentKeyID: 49556654
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Create and submit the EU sales list 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Businesses that supply goods to companies in other European Union (EU) countries/regions must submit periodic reports to the appropriate authorities in their own countries/regions. Quarterly reports are typically required to be submitted no later than 10 days after the end of the quarter. For example, first-quarter reports are due April 10.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.

2.  Click **Transfer** to transfer the customer invoices or project invoices that have been entered for customers in other EU countries/regions to this form.

3.  In the **Transfer transactions for EU sales list** form, select one or more reporting types.
    
      - **Item** – Select this option to include information for transaction lines for products that have a product type of **Item**. This option also includes transaction lines that are identified by descriptions and categories, and that use an item sales tax group that has a reporting type of **Item**.
    
      - **Service** – Select this option to include information for transaction lines for products that have a product type of **Service**. This option also includes transaction lines that are identified by descriptions and categories, and that use an item sales tax group that has a reporting type of **Service**.
    
      - **Investment** – Select this option to include information for transaction lines that use an item sales tax group that has a reporting type of **Investment**. This option is used only if you are printing the EU sales list for Belgium.
    
      - **Not assigned** – Select this option to include information for transaction lines that are not assigned to any of the other three reporting types. This option includes transaction lines that use an item sales tax group that has a blank reporting type.

4.  Click **Select** to specify information for the fields in the **Customer invoice journal** and **Project invoice** field groups.
    
    1.  In the **Date** field, enter the period for which the invoices should be selected.
    
    2.  In the **List code** field, type an exclamation mark (\!) and select **Not included** to exclude invoices that are not for EU sales.

5.  Click **Transfer** to close the **Transfer transactions for EU sales list** form. Transactions are transferred to the **EU sales list** form.

6.  To specify that a transaction contains a correction, do the following:
    
    1.  Select the transaction that you want to mark as a correction.
    
    2.  On the **Correction** tab, select the **Corrected** check box.
    
    3.  To specify that the reason for the correction is an incorrect registration number, amount, or period, select the appropriate check box in the **Correction reason** field group.

7.  In the **EU sales list** form, click **Validate**, select criteria, and then click **OK**. Make any corrections that are needed.

8.  Click **Reporting**.

9.  Enter information in the fields in the form and then click **OK** to print the report or generate an electronic file. The options in the form differ depending on the country/region of the legal entity’s primary address.

10. Submit the report or file to the authority.

## See also

[EU sales list (form)](https://technet.microsoft.com/library/aa596355\(v=ax.60\))

[(HUN) EU sales list (modified form)](https://technet.microsoft.com/library/jj664282\(v=ax.60\))

[Transfer transactions for EU sales list (form)](https://technet.microsoft.com/library/aa499405\(v=ax.60\))

  


