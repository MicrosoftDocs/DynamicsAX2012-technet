---
title: Handle policy rule violations
TOCTitle: Handle policy rule violations
ms:assetid: bc94cb39-d0a3-40cd-8ef2-fbd2da450082
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242770(v=AX.60)
ms:contentKeyID: 36059135
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- policy
- policy rule
- policy rule violation
- policy violation
audience: Application User
ms.search.region: Global
---

# Handle policy rule violations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Vendor invoices are validated against the applicable vendor invoice policies when the invoices are posted using the **Vendor invoice** form, including when they are posted through the vendor self-service portal. The invoices are also validated when the **Policy violations** form is opened, and when the invoices are submitted to an approval workflow that includes a validation task.

## View policy violations for a vendor invoice

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Select the invoice to view policy violations for.

3.  On the **Review** tab of the Action Pane, click **Policy violations** to open the **Policy violations** form.
    
    All policy violations for the selected invoice are listed. To see the details for a violation, select the violation in the list.

## Approve vendor invoices that contain policy violations

You can configure invoice validation settings to require that invoices that have policy violations be approved before they are posted. For more information, see [Key tasks: Vendor invoice policies](key-tasks-vendor-invoice-policies.md).

If the settings require that invoices be approved before they are posted, follow these steps to approve an invoice that has a policy violation without correcting the violation.

1.  Open the invoice that has the policy violation.

2.  On the **Review** tab of the Action Pane, click **Matching details** to open the **Invoice matching details** form.

3.  In the **Invoice matching approval** group, select the **Approve posting with matching discrepancies** check box.
    
    The invoice can then be posted.

## Correct vendor invoices that contain policy violations

1.  Open the invoice that has the policy violation.

2.  On the **Vendor invoice** tab of the Action Pane, click **Edit**.

3.  Make the necessary changes to correct the policy violations.

4.  On the **Review** tab of the Action Pane, click **Policy violations** to open the **Policy violations** form. Verify that all policy violations have been corrected.
    
    The invoice can then be posted.

## See also

[Key tasks: Vendor invoice policies](key-tasks-vendor-invoice-policies.md)

[Invoice matching details (form)](https://technet.microsoft.com/en-us/library/hh209713\(v=ax.60\))

[Policy violations (form)](https://technet.microsoft.com/en-us/library/hh209223\(v=ax.60\))

  


