---
title: Generate the EU sales list
TOCTitle: Generate the EU sales list
ms:assetid: a0051422-f133-4f56-8140-383f2045250e
ms:mtpsurl: https://technet.microsoft.com/library/Gg213385(v=AX.60)
ms:contentKeyID: 36058766
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EU sales list
- European Union
- sales list
audience: Application User
ms.search.region: Global
---

# Generate the EU sales list 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Businesses that supply goods to companies in other European Union (EU) countries or regions can generate periodic EU sales list reports. You can generate the EU sales list on a monthly, bimonthly, quarterly, or yearly basis.

You must perform the following tasks before you can generate the EU sales list.

  - Set up a country or region code. For more information, see [Key tasks: Set up address formats](key-tasks-set-up-address-formats.md).

  - Create a customer group and a customer record. For more information, see [Create a customer group](create-a-customer-group.md) and [Create a customer record](create-a-customer-record.md).

  - Create products and services. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

  - Set up Intrastat parameters for the EU sales list. For more information, see [About Intrastat](about-intrastat.md) and [Set up Intrastat from a free text invoice](set-up-intrastat-from-a-free-text-invoice.md).

  - Create and post sales orders. For more information, go to [Create or edit a sales order](create-or-edit-a-sales-order.md) and [Key tasks: Customer invoices](key-tasks-customer-invoices.md).

  - Create and post free text invoices. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

  - Create project invoices. For more information, see [About invoicing](about-invoicing.md) and [Create and post invoice proposals](create-and-post-invoice-proposals.md).

Use the **EU reporting** form to generate the EU sales list.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.

2.  Click **Transfer** to transfer the customer invoices or project invoices that are created for customers in other EU countries or regions to the **EU sales list** form.

3.  In the **Transfer transactions for EU sales list** form, select one or more reporting types.
    
      - **Item** – Select this check box to include information for transaction lines for products that have a product type of **Item**. This option also includes transaction lines that are identified by descriptions and categories, and that use an item sales tax group that has a reporting type of **Item**.
    
      - **Service** – Select this check box to include information for transaction lines for products that have a product type of **Service**. This option also includes transaction lines that are identified by descriptions and categories, and that use an item sales tax group that has a reporting type of **Service**.
    
      - **Investment** – Select this check box to include information for transaction lines that use an item sales tax group that has a reporting type of **Investment**. This option is used only if you are printing the EU sales list for Belgium.
    
      - **Not assigned** – Select this check box to include information for transaction lines that are not assigned to any of the other three reporting types. This option includes transaction lines that use an item sales tax group that has a blank reporting type.

4.  Click **Select** to specify information for the fields in the **Customer invoice journal** and **Project invoice** field groups.
    
    1.  In the **Date** field, enter the period for which the invoices are selected.
    
    2.  In the **List code** field, type an exclamation mark (\!) and select **Not included** to exclude invoices that are not for EU sales.

5.  Click **OK**, and then click **Transfer** to close the **Transfer transactions for EU sales list** form. Transactions are transferred to the **EU sales list** form.

6.  In the **EU sales list** form, click **Validate**, select criteria, and then click **OK**. Make any corrections that are required.

7.  Click **Reporting**.

8.  Specify the criteria, such as reporting period, date interval, and notification type to generate the report. The options in the form differ depending on the country or region of the primary address of the legal entity. Click **OK** to generate the EU sales list report.

## See also

[EU sales list (form)](https://technet.microsoft.com/library/aa596355\(v=ax.60\))

[Transfer transactions for EU sales list (form)](https://technet.microsoft.com/library/aa499405\(v=ax.60\))

[EU reporting (report) EUSalesListReporting](eu-reporting-report-eusaleslistreporting.md)

  


