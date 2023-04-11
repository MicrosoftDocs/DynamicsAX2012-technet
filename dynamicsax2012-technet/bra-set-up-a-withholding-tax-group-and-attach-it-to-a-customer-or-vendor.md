---
title: (BRA) Set up a withholding tax group and attach it to a customer or vendor
TOCTitle: (BRA) Set up a withholding tax group and attach it to a customer or vendor
ms:assetid: a844d15b-8e3c-4260-aea1-bd3716dfdac7
ms:mtpsurl: https://technet.microsoft.com/library/Dn126106(v=AX.60)
ms:contentKeyID: 52075264
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up a withholding tax group and attach it to a customer or vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedures to create a withholding tax group. After you create a group, you can assign multiple withholding tax codes and calculate multiple withholding tax rates for transactions. You can also attach a withholding tax group to a vendor or a customer. For more information, see [Withholding tax groups (form)](https://technet.microsoft.com/library/aa591973\(v=ax.60\)).

## Create a withholding tax group

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax groups**.

2.  Click **New** to create a withholding tax group.

3.  In the **Withholding tax group** field, enter the identification code for the group.

4.  In the **Description** field, enter a description of the group.

5.  On the **Setup** FastTab, in the **Withholding tax code** field, select withholding tax codes for the Programa de Integração Social (**PIS**), Contribuição para o Financiamente da Securidade Social (**COFINS**), or Contribuição Social sobre Lucro Líquido (**CSLL**) tax types to attach to the group. You can create new lines and attach multiple codes to the group.

## Attach the withholding tax group to a vendor

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor, and then on the **Action Pane**, click **Edit** to open the **Vendors** form.

3.  On the **Invoice and delivery** FastTab, select the **Calculate withholding tax** check box to calculate the withholding tax for vendor payment transactions.

4.  In the **Withholding tax group** field, select the withholding tax group and attach it to the vendor.

5.  On the **Fiscal information** FastTab, in the Inscrição Estadual (**IE**) field, enter the state registration number of the vendor.

## Attach the withholding tax group to a customer

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor, and then on the **Action Pane**, click **Edit** to open the **Vendors** form.

3.  On the **Invoice and delivery** FastTab, select the **Calculate withholding tax** check box to calculate the withholding tax for vendor payment transactions.

4.  In the **Withholding tax group** field, select the withholding tax group and attach it to the vendor.

5.  On the **Fiscal information** FastTab, in the Inscrição Estadual (**IE**) field, enter the state registration number of the vendor.

## See also

[(BRA) Calculate withholding tax for the purchase of services](bra-calculate-withholding-tax-for-the-purchase-of-services.md)

[(BRA) Calculate withholding tax for the sale of services](bra-calculate-withholding-tax-for-the-sale-of-services.md)

[(BRA) Withholding tax codes (modified form)](https://technet.microsoft.com/library/dn126109\(v=ax.60\))

[(BRA) Customers (modified form)](https://technet.microsoft.com/library/jj933537\(v=ax.60\))

  


