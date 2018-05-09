---
title: About registering serial numbers in the sales process
TOCTitle: About registering serial numbers in the sales process
ms:assetid: d42d86d5-08cd-41e9-8535-0858ba42303e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497833(v=AX.60)
ms:contentKeyID: 62200165
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales order
- tracking
- track
- sale
- serial number
---

# About registering serial numbers in the sales process 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic provides information about how to register serial numbers in the sales process. Rather than maintaining serial numbers for products in inventory from receipt to issue, you can register serial numbers on the packing slips or invoices when products are sold. For example, this is useful if you only use serial numbers to handle product returns. You can then trace a product to an invoice to determine whether you sold the product, and whether the service or warranty obligations are valid.

## Are there any prerequisites?

You must enable serial numbers for the sales process on the tracking dimension group by selecting the **Active in sales process** check box. When you do this, Microsoft Dynamics AX does the following:

  - The **Serial number control** check box is selected. If this check box is selected, you must register one serial number for each item on the packing slip or invoice.

  - All selections on the tracking dimension group for serial numbers are cleared, except the **Blank issue allowed** check box. You can select the **Blank issue allowed** check box to override the serial number control and allow products to be packed and invoiced without registering serial numbers.

## When do I register serial numbers in the sales process?

You can register serial numbers on the packing slip for a sales order or on the invoice.

When you prepare an invoice for a serialized item that has shipped with a packing slip, you can select which of the serial numbers on the packing slip to invoice. The number of registered serial numbers must not exceed the quantity of items shipped. If you are creating a partial invoice, you can select fewer serialized items than were registered on the packing slip.

When you print a packing slip or an invoice, the serial numbers that were registered are included.

## Can I enter serial numbers by scanning them, or do I have to type them in?

You can either scan or type serial numbers, depending on what works best for you. However, you must specify the scan mode for both methods. The scan mode determines whether to add or remove serial numbers from the list of serial numbers on the invoice or packing slip.

If you want to scan serial numbers, for example by using a hand-held bar code scanner, configure the scanner to send an **Enter** command after the serial number. This will indicate the end of the data stream. Otherwise, you must press **Enter** on the keyboard after scanning each serial number.

## If I enable serial numbers for the sales process, do I need to register all serial numbers for all items?

Registering serial numbers for all items on a packing slip or invoice depends on the setup for the tracking dimension group that is assigned to the product. When you enable serial numbers for the sales process, the **Serial number control** check box is automatically selected. This means that you must register one serial number, or register a blank registration for an unreadable number, for each item on the packing slip or invoice. If you do not want to require a serial number for each item, select the **Blank issue allowed** check box on the tracking dimension group that is assigned to the item. You can then register fewer serial numbers than the quantity of the items that are being shipped.

If you register more serial numbers than the quantity of items being shipped, you will not be able to post the packing slip or invoice.

## Can I register serial numbers for partial invoices and partial shipments?

You can create partial invoices and packing slips for sales orders, and register only the serial numbers for the items that they include.

If you want to create a partial invoice and you have more than one packing slip for the sales order, you can include serial numbers from more than one packing slip. However, there can only be one packing slip where all serial numbers are not included. For example, if you have three packing slips and each includes two serialized items, you cannot create a partial invoice for one item from each packing slip.

## What do I do when a serial number is not readable?

If a serial number cannot be read or scanned, you can create a blank line for the item by clicking **Not readable**. If the serial number becomes available, you can update the invoice or packing slip. For more information, see the section titled “Can I correct or change the serial numbers I’ve registered for a sales order?” in this document, or the section titled “Change a registered serial number” in [Register serial numbers for a sales order](register-serial-numbers-for-a-sales-order.md).

## Can I correct or change the serial numbers that I’ve registered for a sales order?

Yes, you can correct serial numbers when the following conditions are true:

  - **Invoices** - You can change the serial numbers for the items that you have not yet invoiced. When you do this, the packing slip is also updated. However, if a sales order line was corrected by registering a negative quantity, you cannot change serial numbers for the sales order line.

  - **Packing slips** - You cannot partially correct a packing slip line that contains serialized items. You must reverse the full quantity for the line. If a packing slip has been canceled or corrected, you do not have to register the reversed serial numbers again when you create a new packing slip for the same serialized items. The numbers that were registered will be used.

## Can I view the serial numbers that were shipped with a specific packing slip, or were included in an invoice?

Yes, you can run an inquiry on the packing slip journal line or invoice journal line to view a list of all serial numbers that were included in the document. For more information, see the section titled “View the serial numbers that were registered for a packing slip or invoice” in [Register serial numbers for a sales order](register-serial-numbers-for-a-sales-order.md).

## Can I view the serialized items that I have on hand?

No, you cannot view the serialized items that you have on hand because serial numbers are not registered for items until the items are sold.

## Can I register serial numbers for catch weight items?

No, in the sales process you cannot register serial numbers for catch weight items. You also cannot assign a product that is set up as a catch weight item to a tracking dimension group that is set up for using serial numbers only.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Register serial numbers for a sales order](register-serial-numbers-for-a-sales-order.md)

[Serial numbers (form)](https://technet.microsoft.com/en-us/library/aa552300\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

