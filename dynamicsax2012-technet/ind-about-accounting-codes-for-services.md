---
title: (IND) About accounting codes for services
TOCTitle: (IND) About accounting codes for services
ms:assetid: f3653dee-5ddd-4ac3-8f3a-3c334d182edf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn344876(v=AX.60)
ms:contentKeyID: 56117709
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) About accounting codes for services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Set up service codes for the payment of service tax, primary education cess (PE Cess), and secondary and higher secondary education cess (SHE Cess) in the **Service codes** form. You can then define accounting codes for service codes. When you select a service code for a transaction, the accounting code that is related to the service code is automatically updated for the transaction. You can also generate a service tax payable report that contains service tax payable information for each accounting code based on the services that are provided. The report includes service code, accounting code, service tax, PE Cess, and SHE Cess tax components for a service. The accounting code for PE Cess and SHE Cess is the same for all services.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



Depending on whether you post an invoice or make the payment first, the accounting code that is attached to either the invoice or the payment is used. For example, when you settle a vendor invoice, the accounting code that you select for the invoice is used. However, if the payment is received before you post the invoice, the accounting code that you select for the payment is used. If you do not select a service code in either the vendor invoice or the payment journal, the accounting code for the service code that you select for the purchase transaction for the vendor is used.

When you settle a customer invoice, the accounting code for the service code that you select for the invoice is used.

Perform the following tasks to set up and use accounting codes for service codes in transactions:

  - Create a service code, and then define an accounting code for the service code. For more information, see [(IND) Set up service codes for service goods](ind-set-up-service-codes-for-service-goods.md).

  - Specify a service code in a purchase or sales transaction line in the **Service code** field. The accounting code for the service code is updated in the **Accounting code** field based on the service code that you select. For more information, see [(IND) Calculate service tax for a purchase order](ind-calculate-service-tax-for-a-purchase-order.md) and [(IND) Calculate service tax for a sales order](ind-calculate-service-tax-for-a-sales-order.md).

  - Run the service tax settlement process. For more information, see [(IND) About setting up service tax settlements](ind-about-setting-up-service-tax-settlements.md).

  - Generate the service tax payable report for accounting codes. For more information, see [(IND) Generate the service tax payable report](ind-generate-the-service-tax-payable-report.md).

## See also

[(IND) Calculate service tax in an Invoice journal form](ind-calculate-service-tax-in-an-invoice-journal-form.md)

[(IND) Calculate service tax using a vendor payment journal](ind-calculate-service-tax-using-a-vendor-payment-journal.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

