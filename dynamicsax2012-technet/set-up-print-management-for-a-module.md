---
title: Set up print management for a module
TOCTitle: Set up print management for a module
ms:assetid: 4522e64a-8235-4a6b-bb1b-30d9ed6e035b
ms:mtpsurl: https://technet.microsoft.com/library/Dd309660(v=AX.60)
ms:contentKeyID: 36056890
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- print
- module
- printing
- printer
- printers
- modules
audience: Application User
ms.search.region: Global
---

# Set up print management for a module 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up print management original or copy records and conditional settings for modules such as Accounts receivable and Accounts payable. The print management setup information that you enter is used when documents such as sales orders and purchase orders are printed during the posting process.


> [!NOTE]
> <P>Print management settings can also be used when you reprint documents. Select <STRONG>Preview/Print</STRONG> &gt; <STRONG>Use print management</STRONG> to reprint a document by using the current print management settings.</P>



By default, an original record is set up for each type of document. You can either modify this original, or delete it and create a new one.

To modify an existing original record, copy record, or conditional setting, select the record or setting and make changes.

## Create original or copy records

This procedure explains how to create new original or copy records.

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.
    
    –or–
    
    Click **Accounts payable** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.
    
    –or–
    
    Click **Project management and accounting** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.

2.  In the left pane of the **Print management setup** form, right-click a module name and select **Expand all**. All the document types for that module are displayed.

3.  To create a new record, right-click a document name and select **New**. A new original or copy record is created and is displayed in the list.

4.  In the right pane, select whether to create an original or copy record. If you are creating a copy, enter a name for it.

5.  By default, the document will be sent to the printer destination that is specified by clicking **Printer setup** from the posting form for the document. To change the printer destination, click **Destination** lookup button \> **Printer setup** and select a destination. When you have finished making changes, click **OK** to return to the **Print management setup** form.

6.  Select a report format.
    
    The report format must be created by a developer and be added to the Application Object Tree (AOT) before it is available for selection in the **Print management setup** form. Report formats can be specific to a country/region.

7.  Enter the number of identical copies to print.

8.  Enter the footer text to include at the bottom of the document. For example, for a customer copy, enter Customer Copy. To print footer text in other languages, depending on the language of the document, click the **Footer text** lookup button and set up footer text for the additional languages.

9.  Repeat steps 3 through 8 for the remaining documents in the list.

## Specify conditional settings for an original or copy record

This procedure explains how to specify conditional settings, which are applied based on the results of a query. You must set up at least one original or copy record before you can specify conditional settings for the record. You cannot assign conditional settings directly to a document.


> [!NOTE]
> <P>If you specify multiple conditional settings, make sure that you arrange them in the order in which the queries should be evaluated. For more information, see <A href="about-print-management-processing.md">About print management processing</A>.</P>



If you will be emailing the documents to a group of email addresses that have the same business purpose or worker title, you must set up the purposes or titles before you specify the settings. For more information, see [Address purpose (form)](https://technet.microsoft.com/library/hh242741\(v=ax.60\)).

You set up purposes in the **Address and contact information purpose** form. Click **Organization administration** \> **Setup** \> **Global address book** \> **Address and contact information purpose**. You assign purposes in the **Customers** or **Vendors** form, on the **Contact information** FastTab, in the **Purpose** field.

You assign worker titles in the **Worker** form, in the **Title** field. Click **Human resources** \> **Setup** \> **Workers** \> **Titles**.

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.
    
    –or–
    
    Click **Accounts payable** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.
    
    –or–
    
    Click **Project management and accounting** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.

2.  In the left pane of the **Print management setup** form, right-click a module name and select **Expand all**. All the document types for that module, and all the original or copy records for each document type, are displayed.

3.  Right-click an original or copy record and select **New**. A new conditional setting is created and is displayed in the list.

4.  In the right pane, enter a description for the setting, such as Customers 4000 to 4050.

5.  Click **Select** and enter the query condition that must be fulfilled in order to print the document by using the current settings. For example, you might select a range of customer accounts. Click **OK** to return to the **Print management setup** form.

6.  By default, the document will be sent to the default printer. To change the printer destination, click **Destination** lookup button \> **Printer setup** and select a destination. When you have finished making changes, click **OK** to return to the **Print management setup** form.

7.  If you want to email the documents, complete the following steps:
    
    1.  In the **Print destination settings** form, select **E-mail** as the print destination.
    
    2.  Click the **Edit** button.
        
        This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.
    
    3.  In the **Assign email addresses** form, in the **%1 purpose** field, you can select a business purpose to send the document to a group of email addresses that have the same assigned purpose.
    
    4.  Select the **%1 primary contact** check box to email the report to the primary contact assigned to the customer or vendor.
    
    5.  In the **Worker title** field, you can select a title to send the report to a group of workers who have the same assigned title.
    
    6.  In the **Additional email addresses, separated by ";"** field, you can enter additional email addresses to send the document to.

8.  Select a report format.
    
    The report format must be created by a developer and be added to the Application Object Tree (AOT) before it is available for selection in the **Print management setup** form. Report formats can be specific to a country/region.

9.  Enter the number of identical copies to print.

10. Enter the footer text to include at the bottom of the document. To print footer text in other languages, depending on the language of the document, click the **Footer text** lookup button and set up footer text for the additional languages.

11. Repeat steps 3 through 10 for the remaining documents in the list.

## See also

[Print management setup (form)](https://technet.microsoft.com/library/hh209383\(v=ax.60\))

[Set up print management for a customer or vendor](set-up-print-management-for-a-customer-or-vendor.md)

[Set up print management for a transaction](set-up-print-management-for-a-transaction.md)

[About print management originals, copies, and settings](about-print-management-originals-copies-and-settings.md)

[About print management document types and modules](about-print-management-document-types-and-modules.md)

[About print management processing](about-print-management-processing.md)

[Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\))

[Advanced filtering and query options](advanced-filtering-and-query-options.md)

  


