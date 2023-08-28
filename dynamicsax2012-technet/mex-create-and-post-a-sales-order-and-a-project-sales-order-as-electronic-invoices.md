---
title: (MEX) Create and post a sales order and a project sales order as electronic invoices
TOCTitle: (MEX) Create and post a sales order and a project sales order as electronic invoices
ms:assetid: c7050d39-6467-49a2-88de-a3710128861a
ms:mtpsurl: https://technet.microsoft.com/library/Hh242845(v=AX.60)
ms:contentKeyID: 36059309
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create
- electronic invoices
- post
- project sales order
audience: Application User
ms.search.region: Mexico
---

# (MEX) Create and post a sales order and a project sales order as electronic invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Sales order** form to create and post a sales order as an electronic invoice. You can create and post multiple sales orders as electronic invoices and send the .pdf and .xml files as email attachments to customers.

You can also create and post a sales order for an imported item or a leasing service. In the **Create product** form, the **Product type** field must be **Item** for the imported item and **Service** for the leasing service. Specify all customs information, such as the customs document number, date of import, and customs authority name, when you create the sales order for an imported item. The customs information is provided by the Mexican customs authority when an item is imported. When you create the sales order for a leasing service, specify the property registration number provided by the Mexican government.


> [!NOTE]
> <P>You can assign a project to the sales order, and then post the sales order as an electronic invoice.</P>



1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    \-or-

2.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Double-click a project, and then in the **Projects** form, click **Manage** \> **Item task** \> **Sales order** to create a project sales order.

3.  Click **Sales order** to create a new sales order.
    

    > [!NOTE]
    > <P>You can also assign a project to the sales order in the <STRONG>Project ID</STRONG> field on the <STRONG>General</STRONG> FastTab in the <STRONG>Create sales order</STRONG> form.</P>



4.  Click **Header view**, and then click the **Setup** FastTab.

5.  In the **Sales tax group** field, select the sales tax group assigned to the sales tax code for the electronic invoice.

6.  Click **Line view**, and then click the **Line details** FastTab.

7.  Click the **Setup** tab, and then in the **Item sales tax group** field, select the item sales tax group assigned to the sales tax code for the electronic invoice.

8.  Click the **Product** tab, and then in the **Custom number** field, enter the number of the customs document that was generated when the item was imported.

9.  In the **Custom date** field, select the date when the item was imported.

10. In the **Custom name** field, enter the name of the customs authority in the country/region that the item was imported from. If you enter values in the **Custom number**, **Custom date**, and **Custom name** fields, you cannot enter a value in the **Property number** field.

11. In the **Property number** field, enter the registration number provided by the Mexican government for the leased property. If you enter a value in the **Property number** field, you cannot enter values in the **Custom number**, **Custom date**, and **Custom name** fields.

12. Click **Invoice** \> **Invoice**.

13. In the **Posting invoice** form, select the **Print invoice** check box to print the sales order invoice after the invoice is posted.

14. Select the **Send e-mail** check box to send the .pdf and .xml files as email attachments to the customer.

15. Click **OK** to post the sales order as an electronic invoice. The .pdf and .xml files of the electronic invoice are sent as email attachments to the customer. A copy of the .xml file of the electronic invoice is archived.
    

    > [!NOTE]
    > <P>Click <STRONG>Batch</STRONG> to post the sales order as an electronic invoice by using a batch process.</P>



16. Close the forms.

## See also

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

[Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\))

[(MEX) Set up a sales tax code for an electronic invoice](mex-set-up-a-sales-tax-code-for-an-electronic-invoice.md)

  


