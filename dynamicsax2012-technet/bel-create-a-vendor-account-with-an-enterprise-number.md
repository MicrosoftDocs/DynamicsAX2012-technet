---
title: (BEL) Create a vendor account with an enterprise number
TOCTitle: (BEL) Create a vendor account with an enterprise number
ms:assetid: 2a4a15db-6576-4947-8f5f-00fc1cba7f0b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208495(v=AX.60)
ms:contentKeyID: 36056232
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- belgium
- enterprise number
- vendor account
---

# (BEL) Create a vendor account with an enterprise number 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The enterprise number is a unique identification code assigned by the Belgian government to each Belgian company to replace the nine-digit VAT number. The enterprise number, which must appear in vendor account records, contains text and a ten-digit number. The abbreviations TVA or BTW in the text of the vendor’s unique enterprise number indicate that the company is required to pay VAT. If the company has an Intrastat obligation, the abbreviation BE is also included in the text.

The enterprise number is used to generate the EU sales list and Annual sales list and to declare VAT when you post an invoice for a vendor.

Use this procedure to create a vendor account and specify the enterprise number assigned to the vendor by the Belgian government.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Click **Vendor** to create a new vendor account. For more information, see [Create a vendor account](create-a-vendor-account.md) and [Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\)).

3.  Click the **Addresses** FastTab, and then click **Add** to open the **Address** form.

4.  In the **Country/region** field, select **BEL**.

5.  Enter the required details and then click **OK**.
    

    > [!NOTE]
    > <P>The <STRONG>Primary</STRONG> check box for the vendor account in the <STRONG>Party details</STRONG> form must be cleared.</P>



6.  Click the **Invoice and delivery** FastTab, and in the **Enterprise number** field, enter the vendor's unique identification code. This code is updated in the **Tax exempt number** field.

7.  Close the form to save your changes.

## See also

[Tax exempt numbers (form)](https://technet.microsoft.com/en-us/library/aa583706\(v=ax.60\))

[Party (form)](https://technet.microsoft.com/en-us/library/hh209008\(v=ax.60\))

[(BEL) Create a customer account with an enterprise number](bel-create-a-customer-account-with-an-enterprise-number.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

