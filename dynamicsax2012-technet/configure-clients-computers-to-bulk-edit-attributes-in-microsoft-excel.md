---
title: Configure clients computers to bulk edit attributes in Microsoft Excel
TOCTitle: Bulk edit attributes in Microsoft Excel
ms:assetid: ef325d7a-c26e-404f-86b5-616908cc202a
ms:mtpsurl: https://technet.microsoft.com/library/Dn292561(v=AX.60)
ms:contentKeyID: 55119962
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure clients computers to bulk edit attributes in Microsoft Excel 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Microsoft Dynamics AX users can bulk edit product attributes for a retail catalog by using Microsoft Excel. The bulk-edit process uses a macro created specifically for Microsoft Dynamics AX. By default, macros are disabled in Excel. This topic describes how to enable signed macros in Excel and how to verify that Microsoft is a trusted macro publisher. After you perform the steps in this topic, Microsoft Dynamics AX users can perform a bulk edit, as described in [Bulk edit product attributes by using Excel](bulk-edit-product-attributes-by-using-excel.md).


> [!IMPORTANT]
> <P>You must perform the following procedures on each computer that will bulk edit attributes.</P>



## Enable signed macros in Excel

A signed macro includes a digital signature that identifies the creator and verifies the safety of the macro. Microsoft Dynamics AX 2012 R2 includes a macro signed by Microsoft for bulk editing catalog attributes. You must enable signed macros in Excel before Microsoft Dynamics AX users can use the macro. Configuring macros with the following procedure has the following effect:

Macros are disabled, but security alerts appear if there are macros present. However, if the macro is digitally signed by a trusted publisher, the macro runs if you have trusted the publisher. If you have not trusted the publisher, you are notified to enable the signed macro and trust the publisher.

1.  On the client computer that will be used to bulk edit attributes, open Excel.

2.  Click **File**, and then click **Options**.

3.  In the Excel Options form, click **Trust Center**, and then click the **Trust Center Settings** button.

4.  In the Trust Center form, click **Macro Settings**.

5.  Click **Disable all macros except digitally signed macros**, and then click **OK**.

## Verify that Microsoft is listed as a trusted publisher

If Microsoft is listed a trusted publisher in Excel, Microsoft Dynamics AX users can use the bulk edit macro without being prompted to enable the macro.

1.  On the client computer that will be used to bulk edit attributes, open Excel.

2.  Click **File**, and then click **Options**.

3.  In the Excel Options form, click **Trust Center**, and then click the **Trust Center Settings** button.

4.  In the Trust Center form, click **Trusted Publishers**. Verify that Microsoft Corporation and Microsoft Code Signing PCA are listed in the form. There could be several Microsoft certificates listed on the form. Verify that at least one Microsoft certificate has not expired. If a valid certificate exists, click **OK**. Microsoft Dynamics AX users on the local computer can now use the bulk edit macro in Excel. If no Microsoft certificate is listed, import a valid excel-cert.cer certificate into the local computer certificate store.

5.  From the Windows desktop, click **Start** and then click **Run**.

6.  Type MMC and press Enter.

7.  Click **Certificates** and then click the Add button (**\>**).

8.  Click **Computer account** and then click **Local computer**.

9.  In MMC, expand **Certificates** and right-click **Trusted Publishers**.

10. Click **All Tasks** and then click **Import**.

11. Use the Certificate Import wizard to import a valid excel-cert.cer file and then click **OK**.

12. Accept the default values.

13. In the Excel Trust Center form, click **Trusted Publishers**. Verify that Microsoft Corporation and Microsoft Code Signing PCA are listed in the form. There could be several Microsoft certificates listed on the form. Verify that at least one Microsoft certificate has not expired. If a valid certificate exists, click **OK**.

## See also

[Online Store](online-store.md)

  


