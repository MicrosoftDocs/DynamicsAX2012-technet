---
title: Set up and transfer the transfer order transactions for Intrastat reporting
TOCTitle: Set up and transfer the transfer order transactions for Intrastat reporting
ms:assetid: 3756a936-6228-442f-9a84-7593cef76784
ms:mtpsurl: https://technet.microsoft.com/library/Dn304986(v=AX.60)
ms:contentKeyID: 54899963
author: tonyafehr
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- intrastat
- Forms.IntrastatTransactionCode
- Forms.InventTransferParmShip
- Forms.Intrastat
- transfer orders
- Forms.IntrastatParameters
- Forms.InventTransferParmReceive
- Forms.InventTransferOrders
audience: Application User
ms.search.region: Global
---

# Set up and transfer the transfer order transactions for Intrastat reporting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Follow the steps in this topic to set up and include the Intrastat transactions for the internal transfer of items for a European Union (EU) legal entity on the Intrastat report.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Set up Intrastat reporting. For more information, see <a href="about-intrastat.md">About Intrastat</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Set up the parameters for transfer orders. For more information, see <a href="set-up-transfer-order-parameters.md">Set up transfer order parameters</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up a transaction code for transfer orders

Use the **Transaction codes** form to create a transaction code for transfer orders.

To set up a transaction code for transfer orders, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Transaction codes**.

2.  In the **Transaction code** field, specify the identification code for the transaction code. This identification code is used for Intrastat reporting.

3.  In the **Name** field, specify a name for the transaction code.

4.  Select the **Invoice amount** check box to prevent the printing of the invoice amount on the preprinted form.

5.  In the **Invoiced amount** field, specify the method that is used to calculate the invoiced amount to transfer. Use the following table to decide what method to use for transfer orders.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Considerations</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Empty</strong></p></td>
    <td><p>Select this option to exclude the invoiced amount from the Intrastat value.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Financial cost amount</strong></p></td>
    <td><p>Select this option to use the financial cost amount from the related inventory transaction to calculate the invoiced amount.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Total cost</strong></p></td>
    <td><p>Select this option to use the total cost amount from the related inventory transaction to calculate the invoiced amount.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Manual</strong></p></td>
    <td><p>Select this option to specify the invoiced amount in the transfer order line.</p></td>
    </tr>
    </tbody>
    </table>


6.  In the **Statistical value** field, specify the method that is used to calculate the statistical value to transfer. Use the following table to decide what method to use for transfer orders.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Considerations</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Empty</strong></p></td>
    <td><p>Select this option to exclude the statistical value from the Intrastat value.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Financial cost amount</strong></p></td>
    <td><p>Select this option to use the financial cost amount from the related inventory transaction to calculate the statistical value.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Total cost</strong></p></td>
    <td><p>Select this option to use the total cost amount from the related inventory transaction to calculate the statistical value.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Manual</strong></p></td>
    <td><p>Select this option to specify the statistical value in the transfer order line.</p></td>
    </tr>
    </tbody>
    </table>


## 2\. Set up the foreign trade parameter for transfer orders

Use the **Foreign trade parameters** form to set up the transaction code for transfer orders and the compression details for Intrastat reporting.

To set up the foreign trade parameter for transfer orders, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  In the **Transfer order** field, select the transaction code that you created for transfer orders. For more information, see 1. Set up a transaction code for transfer orders.

3.  Click **Compress** to open the **Compression of Intrastat** form, where you can specify the compression details for Intrastat reporting. For more information, see [Compression of Intrastat (form)](https://technet.microsoft.com/library/aa584795\(v=ax.60\)).

## 3\. Create and ship a transfer order for an EU legal entity

Use the **Transfer orders** form to create a transfer order by specifying the details for Intrastat, and then use the **Shipment** form to ship this transfer order.

The Intrastat generation process operates based on the countries/regions that are specified on the **From warehouse** and **To warehouse** fields in the **Transfer orders** form. The process also considers the scrapped quantity for arrivals.

To create and ship a transfer order for an EU legal entity, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create a transfer order. For more information, see [Transfer orders (form)](https://technet.microsoft.com/library/aa634530\(v=ax.60\)).

3.  In the upper pane, on the **Foreign trade** tab, specify the Intrastat details for the transfer order.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Transaction code</strong></p></td>
    <td><p>Select or update the transaction code for the transfer order. By default, this field is updated with the transaction code that you specified in the <strong>Transfer order</strong> field in the <strong>Foreign trade parameters</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Transport</strong></p></td>
    <td><p>Select the mode of transportation to transfer the items for the transfer order.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Port</strong></p></td>
    <td><p>Select the identification code of the port where the items for the transfer order are loaded.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Statistics procedure</strong></p></td>
    <td><p>Select the identification code of the statistics procedure that is used for the transfer order.</p></td>
    </tr>
    </tbody>
    </table>


4.  In the lower pane, create a transfer order line. For more information, see [Set up transfer order lines](set-up-transfer-order-lines.md).

5.  On the **Foreign trade** tab, specify the Intrastat details for the transfer order line.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Transaction code</strong></p></td>
    <td><p>Select or update the transaction code for the transfer order line. By default, this field is updated with the transaction code that you specified in the <strong>Transaction code</strong> field on the <strong>Foreign trade</strong> tab in the <strong>Transfer orders</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Transport</strong></p></td>
    <td><p>Select or update the mode of transportation to transfer the items for the transfer order line. By default, this field is updated with the code for the mode of transport that you specified in the <strong>Transport</strong> field on the <strong>Foreign trade</strong> tab in the <strong>Transfer orders</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Port</strong></p></td>
    <td><p>Select or update the identification code of the port where the items for the transfer order line are loaded. By default, this field is updated with the code for the port that you specified in the <strong>Port</strong> field on the <strong>Foreign trade</strong> tab in the <strong>Transfer orders</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Statistics procedure</strong></p></td>
    <td><p>Select or update the identification code of the statistics procedure that is used for the transfer order line. By default, this field is updated with the code for the statistics procedure that you specified in the <strong>Statistics procedure</strong> field on the <strong>Foreign trade</strong> tab in the <strong>Transfer orders</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Commodity</strong></p></td>
    <td><p>Select or update the product code for Intrastat reporting. For more information, see <a href="https://technet.microsoft.com/library/aa619055(v=ax.60)">Intrastat (form)</a>. By default, this field is updated with the commodity code for the product that you specified in the <strong>Commodity</strong> field on the <strong>Foreign trade</strong> FastTab in the <strong>Released product details</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Country/region</strong></p></td>
    <td><p>Select or update the country or region of origin for the product. By default, this field is updated with the country or region of origin for the product that you specified in the <strong>Country/region</strong> field on the <strong>Foreign trade</strong> FastTab in the <strong>Released product details</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>State/province</strong></p></td>
    <td><p>Select or update the state or province of origin for the product. By default, this field is updated with the state or province of origin for the product that you specified in the <strong>State/province</strong> field on the <strong>Foreign trade</strong> FastTab in the <strong>Released product details</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Invoiced amount</strong></p></td>
    <td><p>If you select a transaction code in the <strong>Transaction code</strong> field, for which you selected the <strong>Manual</strong> option in the <strong>Invoiced amount</strong> field in the <strong>Transaction codes</strong> form, enter the transaction amount in the transaction currency.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Statistical value</strong></p></td>
    <td><p>If you select a transaction code in the <strong>Transaction code</strong> field, for which you selected the <strong>Manual</strong> option in the <strong>Statistical value</strong> field in the <strong>Transaction codes</strong> form, enter the statistical value for the transaction.</p></td>
    </tr>
    </tbody>
    </table>


6.  Click **Posting**, and then click **Ship transfer order** to open the **Shipment** form, where you can ship the transfer order. For more information, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).

## 4\. Receive a transfer order for an EU legal entity

Use the **Transfer orders** form to specify or update the Intrastat details for a transfer order, and then use the **Receive** form to receive this transfer order.

The Intrastat generation process operates based on the countries that are specified on the **From warehouse** and **To warehouse** fields in the **Transfer orders** form. The process also considers the scrapped quantity for arrivals.

To receive a transfer order for an EU legal entity, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Select a transfer order to receive. You can receive a transfer order that has a status of **Shipped**.

3.  In the upper pane, on the **Foreign trade** tab, specify or update the Intrastat details for the transfer order.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Transaction code</strong></p></td>
    <td><p>Select or update the transaction code for the transfer order.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Transport</strong></p></td>
    <td><p>Select or update the mode of transportation to transfer the items for the transfer order.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Port</strong></p></td>
    <td><p>Select or update the identification code of the port where the items for the transfer order are loaded.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Statistics procedure</strong></p></td>
    <td><p>Select or update the identification code of the statistics procedure that is used for the transfer order.</p></td>
    </tr>
    </tbody>
    </table>


4.  In the lower pane, select or create a transfer order line.

5.  On the **Foreign trade** tab, specify or update the Intrastat details for the transfer order line.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Transaction code</strong></p></td>
    <td><p>Select or update the transaction code for the transfer order line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Transport</strong></p></td>
    <td><p>Select or update the mode of transportation to transfer the items for the transfer order line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Port</strong></p></td>
    <td><p>Select or update the identification code of the port where the items for the transfer order line are loaded.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Statistics procedure</strong></p></td>
    <td><p>Select or update the identification code of the statistics procedure that is used for the transfer order line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Commodity</strong></p></td>
    <td><p>Select or update the product code for Intrastat reporting.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Country/region</strong></p></td>
    <td><p>Select or update the country or region of origin for the product.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>State/province</strong></p></td>
    <td><p>Select or update the state or province of origin for the product.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Invoiced amount</strong></p></td>
    <td><p>If you select a transaction code in the <strong>Transaction code</strong> field, for which you selected the <strong>Manual</strong> option in the <strong>Invoiced amount</strong> field in the <strong>Transaction codes</strong> form, enter or update the transaction amount in the transaction currency.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Statistical value</strong></p></td>
    <td><p>If you select a transaction code in the <strong>Transaction code</strong> field, for which you selected the <strong>Manual</strong> option in the <strong>Statistical value</strong> field in the <strong>Transaction codes</strong> form, enter or update the statistical value for the transaction.</p></td>
    </tr>
    </tbody>
    </table>


6.  Click **Posting**, and then click **Receive** to open the **Receive** form, where you can receive the transfer order. For more information, see [Receive transfer orders](receive-transfer-orders.md) and [Receive (form)](https://technet.microsoft.com/library/aa552649\(v=ax.60\)).

## 5\. Transfer the transfer order transactions and generate the Intrastat report

You can transfer the Intrastat transactions for the internal transfer of items for an EU legal entity to the **Intrastat** form, and then generate the Intrastat report.

To include transfer order transactions on the Intrastat report, follow these steps:

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Click **Transfer** to transfer Intrastat transactions to the **Intrastat** form.
    
    The name of this button includes the country code for the country or region where the legal entity is located. This button is displayed only if the primary address of the legal entity is in an EU country or region.

3.  Select the **Transfer order** check box to transfer the transfer order transactions to the **Intrastat** form. You can also select other transactions to transfer.

4.  In the **Intrastat** form, click **Output**, and then click **Diskette**. The name of this button includes the country code for the primary address of the legal entity.

5.  Specify the details to generate the report, and then click **OK** to generate the Intrastat report that includes transfer orders.

## Related tasks

[Transfer order transactions for Intrastat reporting](transfer-order-transactions-for-intrastat-reporting.md)

[Intrastat transactions report (IntrastatFormLetter)](intrastat-transactions-report-intrastatformletter.md)

[Intrastat transactions report (IntrastatList)](intrastat-transactions-report-intrastatlist.md)

[About transfer orders](about-transfer-orders.md)

  


