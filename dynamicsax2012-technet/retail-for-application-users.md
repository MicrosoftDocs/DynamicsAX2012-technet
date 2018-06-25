---
title: Retail for application users
TOCTitle: Retail for application users
ms:assetid: fc996ae0-4ef9-4321-805c-dc2e49c095d2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597299(v=AX.60)
ms:contentKeyID: 39519387
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- retail
---

# Retail for application users [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

**Retail** is an integrated solution that is designed for Microsoft Dynamics AX. You can use Microsoft Dynamics AX to manage a retail business from the head office to the stores.

**Retail** includes the following programs:

  - The **Retail** module in Microsoft Dynamics AX.

  - Microsoft Dynamics AX for Retail POS – The point of sale (POS) program for the registers in the stores.

  - Commerce Data Exchange: Synch Service – The program that periodically sends transaction information between the head office and the stores.

  - Commerce Data Exchange: Real-time Service – The program that sends real-time information between the head office and the stores.

  - The Microsoft Dynamics AX Commerce Runtime delivers multi-channel commerce capability that has uniform extensibility. It facilitates business processing between the head office and online stores and between the head office and retail (brick-and-mortar) stores.

## Retail module

Use Retail to configure and manage stores, online stores and online marketplaces, registers, retail products, retail product catalogs and other information. You can also use this module to generate reports, perform inquiries, and complete other day-to-day business processes.

## Prerequisites

Before you can fully use **Retail**, you must complete the following tasks in Microsoft Dynamics AX:

  - Set up parameters.

  - Import seed data.

  - Create tax codes and sales tax groups.

  - Set up number sequences.

  - Define currencies.

  - Select a language.


> [!NOTE]
> <P>Parameters and number sequences must also be set up for <STRONG>Retail</STRONG>. For more information, see <A href="configuring-parameters-and-initial-settings.md">Configuring parameters and initial settings</A>.</P>
> <P>For information about how to deploy the retail components, see the <A href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</A> section on TechNet.</P>



## Business processes

The following process flow illustrates the business process for **Retail**.

![Retail Business Process](images/Hh597299.RetailBusinessProcess(AX.60).gif "Retail Business Process")


> [!NOTE]
> <P>If you have Microsoft Dynamics AX 2012 Feature Pack installed, the business processes diagram includes managing concessions, and does not include creating and publishing a product catalog.</P>



## Retail at a glance

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Important tasks</p></th>
<th><p>Primary forms</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="configuring-parameters-and-initial-settings.md">Configuring parameters and initial settings</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597194(v=ax.60)">Retail parameters (form)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-retail-channels.md">Setting up retail channels</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580646(v=ax.60)">Stores (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/jj713630(v=ax.60)">Online store (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/jj728732(v=ax.60)">Online marketplace (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="setting-up-payment-methods-retail.md">Setting up payment methods (Retail)</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597294(v=ax.60)">Payment methods (form) (Retail)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-taxes.md">Setting up taxes</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597168(v=ax.60)">Sales tax override group (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="setting-up-functionality-profiles.md">Setting up functionality profiles</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597181(v=ax.60)">POS functionality profile (form)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-retail-products.md">Setting up retail products</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580615(v=ax.60)">Released product details (form) (Retail)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="setting-up-retail-product-catalogs.md">Setting up retail product catalogs</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/jj728740(v=ax.60)">Attribute groups (form) (Retail)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-bar-codes.md">Setting up bar codes</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580637(v=ax.60)">Item–bar code (form) (Retail)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="setting-up-loyalty-programs.md">Setting up loyalty programs</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580612(v=ax.60)">Loyalty schemes (form)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-shipping-for-online-stores.md">Setting up shipping for online stores</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/aa619881(v=ax.60)">Modes of delivery (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/aa582856(v=ax.60)">Auto charges (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="setting-up-retail-pos.md">Setting up Retail POS</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597141(v=ax.60)">POS registers (form)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-info-codes.md">Setting up info codes</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580638(v=ax.60)">Info codes (form) (Retail)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="setting-up-price-adjustments-and-discounts.md">Setting up price adjustments and discounts</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597227(v=ax.60)">Price adjustments (form)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-competitors.md">Setting up competitors</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597346(v=ax.60)">Competitors (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="setting-up-prices-using-price-groups.md">Setting up prices using price groups</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580635(v=ax.60)">Retail price groups (form)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="setting-up-email-receipts.md">Setting up email receipts</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597228(v=ax.60)">Receipt formats (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="create-and-post-statements-overview.md">Create and post statements overview</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597288(v=ax.60)">Statements (form)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="create-and-print-labels-overview.md">Create and print labels overview</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597343(v=ax.60)">Shelf label printing (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="import-vendor-products-overview.md">Import vendor products overview</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580615(v=ax.60)">Released product details (form) (Retail)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="manage-retail-product-catalogs-overview.md">Manage retail product catalogs overview</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/jj728723(v=ax.60)">Catalogs (form) (Retail)</a></p></td>
</tr>
<tr class="odd">
<td><p><a href="replenish-inventory-overview.md">Replenish inventory overview</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597340(v=ax.60)">Replenishment rules (form)</a></p></td>
</tr>
<tr class="even">
<td><p><a href="manage-store-inventory-overview.md">Manage store inventory overview</a></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597323(v=ax.60)">Buyer's push (form)</a></p></td>
</tr>
</tbody>
</table>


## Integration of Retail

Microsoft Dynamics AX can be integrated with the following Microsoft products:

  - Commerce Services for Microsoft Dynamics ERP

  - Payment Services for Microsoft Dynamics ERP

  - Sites Services for Microsoft Dynamics ERP

## See also

[Setting up and maintaining Retail](setting-up-and-maintaining-retail.md)

[Working with Retail](working-with-retail.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

