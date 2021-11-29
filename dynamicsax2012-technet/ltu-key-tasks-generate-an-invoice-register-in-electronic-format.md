---
title: '(LTU) Key tasks: Generate an invoice register in electronic format'
TOCTitle: '(LTU) Key tasks: Generate an invoice register in electronic format'
ms:assetid: fae9988f-a417-4744-baf9-ba7cb2b45bd7
ms:mtpsurl: https://technet.microsoft.com/library/Dn528956(v=AX.60)
ms:contentKeyID: 59641345
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Key tasks: Generate an invoice register in electronic format 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX, you can generate information for reporting value-added (VAT) transactions to tax authorities. You can generate a list of customer invoices that contain VAT for reporting on Form FR0672. Also, you can generate a list of vendor invoices that contain VAT for reporting on Form FR0671. You can generate these lists, also referred to as registers, in an XML format that you can send electronically to the tax authorities.

**Prerequisites**

Before you can generate an invoice register, you must do the following:

  - Set up a number sequence for the various types of customer invoices that are available in Microsoft Dynamics AX. You can specify whether a type of invoice is included in the customer invoice register. For example, you can exclude free-text invoices and customer invoices that were created for projects. For more information about how to set up number sequences for customer invoices that you want to include in an invoice register, see [(LTU) Counters management (form)](https://technet.microsoft.com/library/jj911249\(v=ax.60\)).

  - Set up a number sequence for the various types of vendor invoices that are available in Microsoft Dynamics AX. You can specify whether a type of invoice is included in the vendor invoice register. For example, you can exclude purchase advance invoices and vendor invoices that were posted for projects. For more information about how to set up number sequences for vendor invoices that you want to include in an invoice register, see [(LTU) Counters management (form)](https://technet.microsoft.com/library/jj911249\(v=ax.60\)).

  - Set up the system to track customer invoices and vendor invoices that contain VAT amounts. For more information about how to set up tracking for customer invoices, see [Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\)). For more information about how to set up tracking for vendor invoices, see [(LTU) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj665154\(v=ax.60\)).

## What do you want to do?

Select an invoice to include in an invoice register

Create a customer invoice register for the FR072 report

Create a vendor invoice register for the FR071 report

Find form help

## Select an invoice to include in an invoice register

You can select specific invoices in an invoice journal to include in the invoice register.

1.  Open the customer invoice journal. Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.
    
    –or–
    
    Open the vendor invoice journal. Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  In the invoice journal, select the invoice to include in the invoice register. On the top menu, click **Functions** \> **Change dependency to register**.

3.  To clear an invoice from the invoice register, select an invoice, and then click **Functions** \> **Change dependency to register**.

The **Include in register** check box is selected for invoices to include in an invoice register.

Back to top

## Create a customer invoice register for the FR072 report

1.  Click **Accounts receivable** \> **Periodic** \> **Invoice register (FR0672)**.

2.  In the **Invoice register (FR0672)** form, in the **Date interval** field, select a time period for transactions to include in the list of customer invoices. For more information about date intervals, see [Date intervals (form)](https://technet.microsoft.com/library/aa558459\(v=ax.60\)).

3.  The starting and ending dates for the date interval that you selected are displayed in the **From date** and **To date** fields. You can modify the dates.

4.  In the **File name** field, select the file name and location to save the invoice register file to.

Back to top

## Create a vendor invoice register for the FR071 report

1.  Click **Accounts payable** \> **Periodic** \> **Invoice register (FR0671)**.

2.  In the **Invoice register (FR0671)** form, in the **Date interval** field, select a time period for transactions to include in the list of vendor invoices. For more information about date intervals, see [Date intervals (form)](https://technet.microsoft.com/library/aa558459\(v=ax.60\)).

3.  The starting and ending dates for the date interval that you selected are displayed in the **From date** and **To date** fields. You can modify the dates.

4.  In the **File name** field, select the file name and location to save the invoice register file to.

Back to top

## Find form help

[(LTU) Export invoice register (FR0671) (form)](https://technet.microsoft.com/library/jj665056\(v=ax.60\))

[(LTU) Export invoice register (FR0672) (form)](https://technet.microsoft.com/library/jj665044\(v=ax.60\))

  


