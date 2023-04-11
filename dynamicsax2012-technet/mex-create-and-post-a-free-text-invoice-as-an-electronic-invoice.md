---
title: (MEX) Create and post a free text invoice as an electronic invoice
TOCTitle: (MEX) Create and post a free text invoice as an electronic invoice
ms:assetid: 7477c323-24e6-4a1a-9aca-ae13d5979e5d
ms:mtpsurl: https://technet.microsoft.com/library/Hh209236(v=AX.60)
ms:contentKeyID: 36058157
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create and post
- electronic invoice
- free text invoice
audience: Application User
ms.search.region: Mexico
---

# (MEX) Create and post a free text invoice as an electronic invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Free text invoice** form to create and post a free text invoice for a leasing service as an electronic invoice. You must set the **Product type** field to **Service** in the **Create product** form. You must specify the property registration number provided by the Mexican government when you create the free text invoice for a leasing service. For more information, see [Free text invoice (form)](https://technet.microsoft.com/library/aa556897\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Click **Free text invoice**.

3.  In the **Free text invoice** form, create a free text invoice for a leasing service. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

4.  Click the **Invoice lines** FastTab, and then in the **Sales tax group** field, select the sales tax group that is assigned to the sales tax code for electronic invoices. For more information, see [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md).

5.  In the **Item sales tax group** field, select the item sales tax group that is assigned to the sales tax code for electronic invoices. For more information, see [Create item sales tax groups](create-item-sales-tax-groups.md).

6.  Click the **Line details** FastTab, and then click the **CFD - Electronic invoices** tab.

7.  In the **Property number** field, enter the registration number provided by the Mexican government for the leased property.

8.  Click **Post** \> **Post**.

9.  In the **Post free text invoice** form, select the **Print invoice** check box to print the free text invoice after the invoice is posted.

10. Select the **Send e-mail** check box to send the .pdf and .xml files of the free text invoice as email attachments to the customer after the invoice is posted.

11. Click **OK** to post the free text invoice as an electronic invoice. The .pdf and .xml files of the electronic invoice are sent as email attachments to the customer. A copy of the .xml file of the electronic invoice is archived.

12. Close the forms.


> [!NOTE]
> <P>You can also use the <STRONG>Free text invoice</STRONG> and <STRONG>Post free text invoice</STRONG> forms to create a credit note for a posted free text invoice, and then post the credit note as an electronic invoice. Select the customer account, invoice account, and ledger account that you entered in the posted free text invoice that you are creating a credit note for. On the <STRONG>Invoice lines</STRONG> FastTab, in the <STRONG>Amount</STRONG> field, enter a negative amount, and then post the credit note as an electronic invoice.</P>



## See also

[(MEX) Set up a sales tax code for an electronic invoice](mex-set-up-a-sales-tax-code-for-an-electronic-invoice.md)

  


