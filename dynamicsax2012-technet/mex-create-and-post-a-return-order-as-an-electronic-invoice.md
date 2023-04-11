---
title: (MEX) Create and post a return order as an electronic invoice
TOCTitle: (MEX) Create and post a return order as an electronic invoice
ms:assetid: 0beffe39-4e06-4ad1-8601-2b4c9a57846f
ms:mtpsurl: https://technet.microsoft.com/library/Hh242125(v=AX.60)
ms:contentKeyID: 36055991
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create and post
- electronic invoice
- return order
audience: Application User
ms.search.region: Mexico
---

# (MEX) Create and post a return order as an electronic invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Return order** form to create a return order when a customer returns an item. Register the arrival of the returned item in the **Arrival overview** form. The details of the return order are then updated in the **Sales order** form. You can use the **Sales order** form to select and post the return order as an electronic invoice.

When you create the return order for an imported item, you must specify the pertinent customs information, such as the customs document number, date of import, and customs authority name. You must set the **Product type** field to **Item** in the **Create product** form.

1.  Click **Sales and marketing** \> **Common** \> **Return orders** \> **All return orders**.

2.  Click **Return order** to create a return order. For more information, see [(IND) Recoverable certificates (form)](https://technet.microsoft.com/library/jj664816\(v=ax.60\))

3.  Close the forms.

4.  Click **Inventory management** \> **Periodic** \> **Arrival overview**.

5.  In the **Arrival overview** form, register the item arrival. For more information, see [Register the receipt of returned items](register-the-receipt-of-returned-items.md).

6.  Close the form.

7.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

8.  Double-click a sales order that has the **Order type** field as **Returned order**, and then click **Edit**.

9.  In the **Sales order** form, click **Header view**.

10. On the **General** FastTab, in the **RMA number** field, verify that the return merchandise authorization (RMA) number of the return order to be posted has been updated.

11. Click **Line view**, and then click the **Line details** FastTab.

12. Click the **Product** tab, and then in the **Custom number** field, enter the number of the customs document that was generated when the item was imported.

13. In the **Custom date** field, select the date when the item was imported, and then in the **Custom name** field, enter the name of the customs authority in the country that the item was imported from.

14. Click the **Invoice** tab, and then click **Invoice**.

15. In the **Posting invoice** form, select the **Print invoice** check box to print the return order invoice after the invoice is posted, and then select the **Send e-mail** check box to send the .pdf and .xml files of the return order invoice as email attachments to the customer.

16. Click **OK** to post the return order as an electronic invoice. The .pdf and .xml files of the electronic invoice are sent as email attachments to the customer. A copy of the .xml file of the electronic invoice is archived.
    

    > [!NOTE]
    > <P>Click <STRONG>Batch</STRONG> to post the return order as an electronic invoice by using a batch process.</P>



17. Close the forms.

## See also

[Return orders (form)](https://technet.microsoft.com/library/hh803010\(v=ax.60\))

[Arrival overview (form)](https://technet.microsoft.com/library/hh227654\(v=ax.60\))

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

  


