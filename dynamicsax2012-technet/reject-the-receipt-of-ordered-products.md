---
title: Reject the receipt of ordered products
TOCTitle: Reject the receipt of ordered products
ms:assetid: 8b285ee4-4ba6-4b4b-ac47-0786589cb9c0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271589(v=AX.60)
ms:contentKeyID: 36384220
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPPurchCORList
- EPPurchCORReject
---

# Reject the receipt of ordered products [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

On Enterprise Portal for Microsoft Dynamics AX, you can reject the receipt of ordered products. You do so on the **Unconfirmed product receipts** page. An example of why you would reject a receipt could be that the product is broken on receipt.

1.  Click **Procurement** on the top link bar, and then click **Unconfirmed product receipts** on the Quick Launch.

2.  From the list of product receipts, select the product receipt that you want to reject. On the **Action Pane**, on the **Confirmation of product receipt** tab, in the **Update** group, click **Reject**.

3.  Change the quantity in the **Purchase quantity** field to indicate how many items that you want to reject. For example, if one out of the five ordered products was broken, the number given as received, in this case 5 must be changed to the number that is rejected, in this case 1. The change of number must indicate the number of items you want to reject.

4.  Enter the reason why you reject the product receipt in the **Reject comment** field.

5.  Click **Save and close** to save the changes, and return to the **Unconfirmed product receipts** page. If you reject all of the delivered products, the product receipt disappears from the list of unconfirmed receipts.
    

    > [!NOTE]
    > <P>The product receipt for the rejected product is now listed in the client. It states the number of rejected products. The product receipt is handled by a designated person who resolves issues with received products.</P>



## See also

[View a list of product receipts that are unconfirmed](view-a-list-of-product-receipts-that-are-unconfirmed.md)

[Confirm the receipt of products](confirm-the-receipt-of-products.md)

[Change delivery date for the receipt of products](change-delivery-date-for-the-receipt-of-products.md)

[About confirmation of product receipts](about-confirmation-of-product-receipts.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

