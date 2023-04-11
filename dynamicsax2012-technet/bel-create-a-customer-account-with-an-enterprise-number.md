---
title: (BEL) Create a customer account with an enterprise number
TOCTitle: (BEL) Create a customer account with an enterprise number
ms:assetid: a40bd09e-d781-47ec-8d13-4543f8d7bd3d
ms:mtpsurl: https://technet.microsoft.com/library/Hh209463(v=AX.60)
ms:contentKeyID: 36058815
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- belgium
- enterprise number
- customer account
audience: Application User
ms.search.region: Belgium
---

# (BEL) Create a customer account with an enterprise number 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The enterprise number is a unique identification code assigned by the Belgian government to each Belgian company to replace the nine-digit VAT number. The enterprise number, which must appear in customer account records, contains text and a ten-digit number. The abbreviations TVA or BTW in the text of the customer’s unique enterprise number indicate that the company is required to pay VAT. If the company has an Intrastat obligation, the abbreviation BE is also included in the text.

The enterprise number is used to generate the EU sales list and Annual sales list and to declare VAT when you post an invoice for a customer.

Use this procedure to create a customer account and specify the enterprise number assigned to the customer by the Belgian government.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Click **Customer** to create a new customer account. For more information, see [Create a customer record](create-a-customer-record.md).

3.  Click the **Addresses** FastTab, and then click **Add** to open the **Address** form. Enter the required details.
    

    > [!NOTE]
    > <P>The <STRONG>Primary</STRONG> check box for the customer account in the <STRONG>Address</STRONG> form must be cleared.</P>



4.  Close the form to save your changes.

5.  Click the **Details** FastTab, and in the **Country/region** field, select **BEL**.

6.  Click the **Invoice and delivery** FastTab, and in the **Enterprise number** field, enter the customer's unique identification code. The identification code entered in this field is updated in the **Tax exempt number** field.

7.  Close the form to save your changes.

## See also

[Tax exempt numbers (form)](https://technet.microsoft.com/library/aa583706\(v=ax.60\))

[(BEL) Create a vendor account with an enterprise number](bel-create-a-vendor-account-with-an-enterprise-number.md)

[Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\))

  


