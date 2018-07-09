---
title: (ESP) Transfer sales and purchase transactions for EU sales list reporting
TOCTitle: (ESP) Transfer sales and purchase transactions for EU sales list reporting
ms:assetid: a5859c8c-6cc8-43c2-9200-f08bad1c766b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242681(v=AX.60)
ms:contentKeyID: 36058864
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Spain
- EU sales list
---

# (ESP) Transfer sales and purchase transactions for EU sales list reporting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sales and purchase transactions between European Union (EU) countries or regions must be reported to the government on the EU sales list. After you create and post invoices for EU trade transactions, you can transfer the invoice data to the EU sales list form for reporting. Before you transfer invoice information, you must set up sales tax groups and sales tax codes. For more information, see [Transfer transactions for EU sales list (form)](https://technet.microsoft.com/en-us/library/aa499405\(v=ax.60\)).


> [!NOTE]
> <P>The <STRONG>List code</STRONG> field is available only if the <STRONG>Transfer purchases</STRONG> check box is selected in the <STRONG>Foreign trade parameters</STRONG> form.</P>



## Create and post a purchase order for an EU vendor

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Create a purchase order. For more information, see [Create purchase order (form)](https://technet.microsoft.com/en-us/library/aa570189\(v=ax.60\)).

3.  Click the **Foreign trade** tab.

4.  In the **List code** field, select one of the following list codes for the vendor invoice:
    
      - **Not included** – No list code in the invoice.
    
      - **EU trade** – Trade with another EU country/region.
    
      - **Production on toll** – Value-added work for a customer in another EU country/region.
    
      - **Triangular/EU trade** – Trade between several EU countries/regions.
    
      - **Triangular/Prod. on toll** – Value-added work for customers in several EU countries/regions.

5.  Close the form to save your changes.

## Post a vendor invoice for an EU vendor

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.
    
    \-or-
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.
    
    \-or-
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.

2.  Click **Lines**.

3.  Click the **Invoice** tab.

4.  In the **List code** field, select one of the following list codes for the vendor invoice that is used to report to the EU sales list:
    
      - **Not included** – No list code in the invoice.
    
      - **EU trade** – Trade with a customer in another EU country/region.
    
      - **Production on toll** – Value-added work for a customer in another EU country/region.
    
      - **Triangular/EU trade** – Trade between customers in several EU countries/regions.
    
      - **Triangular/Prod. on toll** – Value-added work for customers in several EU countries/regions.

5.  Click **Validate** \> **Validate** to validate the journal.

6.  Click **Post** \> **Post** to post the vendor invoice.

7.  Close the form to save your changes.

## Create and post a sales invoice for an EU customer

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Click the **Foreign trade** tab.

3.  In the **List code** field, select one of the following list codes:
    
      - **Not included** – No list code in the invoice.
    
      - **EU trade** – Trade with a customer in another EU country/region.
    
      - **Production on toll** – Value-added work for a customer in another EU country/region.
    
      - **Triangular/EU trade** – Trade between customers in several EU countries/regions.
    
      - **Triangular/Prod. on toll** – Value-added work for customers in several EU countries/regions.

4.  Click **Invoice** \> **Invoice**.

5.  In the **Posting invoice** form, select the **Posting** and **Print invoice** check boxes.

6.  Click **OK** to post the sales invoice.

7.  Close the form to save your changes.

## Transfer the sales and purchase transactions to the EU sales list

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.

2.  Click **Transfer** to specify the selection criteria and to open the **Transfer transactions for EU sales list** form.

3.  Select reporting types for the sales and vendor invoices to limit the transactions that are transferred to the EU sales list:
    
      - **Item** – Select this check box to transfer an item sale or purchase transaction.
    
      - **Service** – Select this check box to transfer a service sale or purchase transaction.
    
      - **Investment** – Select this check box to transfer an investment sale or purchase transaction.
    
      - **Not assigned** – Select this check box to transfer an unassigned sale or purchase transaction.

4.  Click **Select** and then specify the selection criteria for the invoices to be transferred to the EU sales list.

5.  Click **Transfer** to transfer the transactions.

6.  Close the form to save your changes.

## Export the EU sales list

You can export the EU sales list in an ASCII file.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.

2.  Click **Transfer** to open the **Transfer transactions for EU sales list** form.

3.  Click **Transfer** to transfer invoice details to the EU sales list.

4.  Click **Reporting** to open the **EU reporting** form.

5.  In the **Reporting period** field, select the type of reporting period from the following options:
    
      - **Monthly** – The EU sales list report is generated monthly.
    
      - **Bimonthly** – The EU sales list report is generated bi-monthly.
    
      - **Quarterly** – The EU sales list report is generated quarterly.
    
      - **Yearly** – The EU sales list report is generated annually.

6.  In the **From date** and **To date** fields, select the start date and the end date of the reporting period.

7.  Select the **Generate file** check box to generate the EU sales list in a specific file format.

8.  In the **File name** field, enter the file path and the name for the EU sales list export file.

9.  Click **OK** to generate the EU sales list.

10. Close the form to save your changes.

## See also

[About purchase order posting types](about-purchase-order-posting-types.md)

[About sales order posting types](about-sales-order-posting-types.md)

[Generate the EU sales list](generate-the-eu-sales-list.md)

[EU sales list (form)](https://technet.microsoft.com/en-us/library/aa596355\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

