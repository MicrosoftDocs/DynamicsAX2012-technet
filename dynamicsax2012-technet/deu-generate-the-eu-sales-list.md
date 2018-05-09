---
title: (DEU) Generate the EU sales list
TOCTitle: (DEU) Generate the EU sales list
ms:assetid: 83f84853-150e-4f27-8f1a-e5ef919928ea
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn304980(v=AX.60)
ms:contentKeyID: 54899954
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.EUSalesList
- SSRS_Reports.Reports.EUSalesListReporting
- DE - 00009
- MsDynAx060.Forms.EUSalesList
---

# (DEU) Generate the EU sales list 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

German businesses that supply items to other companies in European Union (EU) countries or regions can generate periodic reports that itemize their sales transactions. The EU sales list report contains the value of items that are sold to value-added tax (VAT) registered customers in other EU countries or regions. You can generate the EU sales list as an ELMA5 text file. You can generate the EU sales list on a monthly, bimonthly, quarterly, or yearly basis.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 5 for AX 2012.</P>



You must perform the following tasks before you can generate the EU sales list.

  - Set up a country or region code. For more information, see [Key tasks: Set up address formats](key-tasks-set-up-address-formats.md).

  - Create a customer group and a customer record. For more information, see [Create a customer group](create-a-customer-group.md) and [Create a customer record](create-a-customer-record.md).

  - Create products and services. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

  - Set up Intrastat parameters for the EU sales list. For more information, see [About Intrastat](about-intrastat.md) and [Set up Intrastat from a free text invoice](set-up-intrastat-from-a-free-text-invoice.md).

  - Create and post sales orders. For more information, go to [Create or edit a sales order](create-or-edit-a-sales-order.md) and [Key tasks: Customer invoices](key-tasks-customer-invoices.md).

  - Create and post free text invoices. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

  - Create project invoices. For more information, see [About invoicing](about-invoicing.md) and [Create and post invoice proposals](create-and-post-invoice-proposals.md).

Use the **EU reporting** form to generate the EU sales list as an ELMA5 text file.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.

2.  Click **Transfer** to open the **Transfer transactions for EU sales list** form.

3.  Select the criteria to transfer the customer invoices or project invoices to the EU sales list, and then click **Transfer** to transfer the invoices to the **EU sales list** form. For more information, see [Transfer transactions for EU sales list (form)](https://technet.microsoft.com/en-us/library/aa499405\(v=ax.60\)) and [EU sales list (form)](https://technet.microsoft.com/en-us/library/aa596355\(v=ax.60\)).

4.  In the **EU sales list** form, click **Validate**, select criteria, and then click **OK**. Make any corrections that are needed.

5.  Click **Reporting** to open the **EU reporting** form.

6.  In the **Reporting period** field, select the period to generate the report for.

7.  In the **From date** field, select the starting date to generate the report for.

8.  Select the **Generate file** check box to generate the report as an ELMA5 text file, and then in the **File name** field, specify a path and a file name for the report.

9.  In the **EU Sales List Registration ID** field, enter the identification code of the EU sales list registration.

10. Select the **Correction** check box to indicate that the report is a correction report.

11. In the **Notification type** field, select one of the following options as the type of notification for the report:
    
      - **Notice** – Submit the EU sales list on a monthly basis in the future.
    
      - **Revocation** – Submit the EU sales list for the period that you specify in the **Reporting period** field.

12. Click **OK** to generate the EU sales list as an ELMA5 text file.

## See also

[EU reporting (report) EUSalesListReporting](eu-reporting-report-eusaleslistreporting.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

