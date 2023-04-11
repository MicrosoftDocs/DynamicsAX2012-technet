---
title: (IND) Create a tax setoff rule to settle an excise recoverable amount
TOCTitle: (IND) Create a tax setoff rule to settle an excise recoverable amount
ms:assetid: 16a357bd-7ebf-43df-b956-5bf56b7cff7b
ms:mtpsurl: https://technet.microsoft.com/library/Dn344872(v=AX.60)
ms:contentKeyID: 56117708
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxComponentTable_IN
- Forms.TaxSetOffRule_IN
- MsDynAx060.Forms.TaxComponentTable_IN
- MsDynAx060.Forms.TaxSetOffRule_IN
audience: Application User
ms.search.region: India
---

# (IND) Create a tax setoff rule to settle an excise recoverable amount 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Tax setoff rule** form to create a tax setoff rule to settle excise recoverable amounts against service tax. When an excise is recoverable, you define the sequence of taxes against which excise recoverable amounts are settled. You then provide the service codes and accounting codes for the service tax if the service tax is part of the tax hierarchy. Microsoft Dynamics AX settles the excise recoverable amount against the service tax payable amount based on the service codes that you select for the setoff rule in one of the following ways:

  - If you select a service code that has an accounting code assigned to it, the excise recoverable amount is settled against the accounting code.

  - If you select multiple service codes that have accounting codes assigned to them, the excise recoverable amount is settled against the accounting codes based on the sequence that you define for the service codes in the setoff rule.

  - If you select a service code that does not have an accounting code assigned to it, the excise recoverable amount is settled against the service code.
    

    > [!NOTE]
    > <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



<!-- end list -->

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax components**.

2.  Create a tax component for excise tax. For more information, see [(IND) Set up excise tax components](ind-set-up-excise-tax-components.md) and [(IND) Tax components (form)](https://technet.microsoft.com/library/jj664734\(v=ax.60\)).

3.  Click **Tax setoff rule** to open the **Tax setoff rule** form, where you can create or update the tax setoff rule for the tax components. For more information, see [(IND) Tax setoff rule (form)](https://technet.microsoft.com/library/jj677818\(v=ax.60\)).

4.  In the **Setoff component** field, select the tax component for service tax.

5.  Click **Service code** to open the **Tax setoff rule** form for the setoff component.
    

    > [!NOTE]
    > <P>The <STRONG>Service code</STRONG> button is available if you select service tax as the tax component.</P>



6.  Create a service code record. The **Column** field is updated with the order of priority for the service code that is used to set off the original excise tax component.

7.  In the **Service code** field, select the service code against which the selected excise tax component recoverable amount is set off. The accounting code for the service is updated in the **Accounting code** field based on the service code that you select. For more information, see [(IND) Set up service codes for service goods](ind-set-up-service-codes-for-service-goods.md).

8.  Repeat steps 6 and 7 to set up additional service codes.

## See also

[(IND) Generate the service tax payable report](ind-generate-the-service-tax-payable-report.md)

[(IND) Define a service tax component and the tax setoff](ind-define-a-service-tax-component-and-the-tax-setoff.md)

  


