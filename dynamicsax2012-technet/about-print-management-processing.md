---
title: About print management processing
TOCTitle: About print management processing
ms:assetid: 1cffff79-b864-4ba6-a622-5c0128745c1e
ms:mtpsurl: https://technet.microsoft.com/library/Dd309615(v=AX.60)
ms:contentKeyID: 36056138
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- duplicate
- print
- copies
- footer
- original
- invoices
- override
- settings
- copy
- condition
- report
- reports
- conditional
- invoice
- printing
- order
- orders
- conditions
- duplicates
- footers
- inherited
- management
- originals
- printer
- printers
- setting
audience: Application User
ms.search.region: Global
---

# About print management processing 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you post or reprint business documents such as sales orders and purchase orders, the resulting documents, such as invoices or picking lists, can be printed by using the defined settings for the effective original or copy records in print management. The effective records are the original and copy records that apply to the document that is generated. This topic explains how Microsoft Dynamics AX determines which original records, copy records, and conditional settings are effective during the posting and printing process.

The print management setup information for each document type is defined in a hierarchical list that consists of modules, accounts, and transactions. At each level of the hierarchy, you can define print management original records, copy records, and settings for any of the available document types. When a document is generated, it is printed according to the effective original record and effective copy records. An effective record can be inherited from a higher level in the hierarchy or created as a new record for the current level in the hierarchy, or it can override an inherited record that has the same name.

Each original record or copy record can have a default setting associated with it, which specifies the footer text, printer destination, and number of identical copies to print. If the **Default setting** check box in the **Print management setup** form is selected, a document is printed according to the specifications for the default setting. If this check box is not selected, a document is printed only if a query for an associated conditional setting successfully returns results.

Each original record or copy record can have up to 19 conditional settings associated with it. Each conditional setting has a related query. When the document is generated during posting, the queries that are associated with the conditional settings are evaluated in the order in which the settings appear in the **Print management setup** form. The setting that is associated with the first successful query is used to print the document.


> [!NOTE]
> <P>While conditional settings and queries provide flexibility in your print management settings, complex queries or many conditional settings can affect posting performance.</P>



For more information about how original records, copy records, and conditional settings work together at the module and account levels, see the following examples. For this series of examples, print management is set up for free text invoice documents.

If you print a document to the screen, you can view up to five reports, each in a separate report window. For example, if you print customer statements to the screen, statements for only the first five customers are displayed. Additional reports are saved as PDF files in the location that is specified in the **Directory** field in the **File store** area of the **System parameters** form. (Click **System administration** \> **Setup** \> **System parameters**.)

## Example: Set up an original record at the module level

You can set up print management for all free text invoices that are printed from the legal entity that you are logged on to. To do this, set up print management at the module level.

1.  From the Accounts receivable **Form setup** form, open the **Print management setup** form, expand the **Free text invoice** list in the left pane, and select the **Original** record.

2.  In the right pane, enter Original as the footer text.

For more information, see [Set up print management for a module](set-up-print-management-for-a-module.md) and [Set up footer text for documents](set-up-footer-text-for-documents.md).

## Example: Create a copy record at the module level

You likely will have to create a copy of each free text invoice to send to your customers, and you might want to include the words "Customer Copy" on those copies. To do this, you can set up print management at the module level.

1.  In the **Print management setup** form, right-click the **Free text invoice** document and select **New**. A new record is displayed in the list in the left pane.

2.  In the right pane, enter a name for the copy record, such as Customer Copy, and enter Customer Copy as the footer text.

## Example: Copy an inherited copy record at the account level

The previous examples illustrate setting up print management at the module level, such as for Accounts receivable. By setting up print management at the module level, future maintenance of printer specifications is simplified. However, you might have customers who require special treatment with regard to their free text invoices. For example, you might want to print an additional copy of the free text invoice to send to your sales manager whenever an invoice is generated for a particular account. To do this, you can copy an inherited module-level copy record that contains the print management specification for the additional copy.

1.  Select a customer in the **Customers** form, and from that form, open the **Print management setup** form.

2.  Expand the **Free text invoice** list, right-click the copy record titled **Customer Copy**, and select **Copy**. A new copy record is created, which is effective only for the selected customer.

3.  Enter a name for the copy, such as Sales Manager Copy, and enter Sales Manager Copy as the footer text.

For more information, see [Set up print management for a customer or vendor](set-up-print-management-for-a-customer-or-vendor.md).

## Example: Override an inherited copy record at the account level

You might decide that for the same customer as in the previous example, the footer text should be "Preferred Customer Copy" instead of "Customer Copy." To make this change, you can override an inherited copy record at the account level.

1.  Select a customer in the **Customers** form, and from that form, open the **Print management setup** form.

2.  Expand the **Free text invoice** list, right-click the copy record titled **Customer Copy**, and select **Override**. The icon next to the copy record in the list changes to indicate that the record has been overridden. The account-level record also has the name **Customer Copy**.

3.  Change the footer text to Preferred Customer Copy.


> [!NOTE]
> <P>If you override an original record, copy record, or conditional setting and then change the parent record in the hierarchy, the changes to the parent record do not update the override records or settings that you created.</P>



You can also override print management settings for individual transactions. For more information, see [Set up print management for a transaction](set-up-print-management-for-a-transaction.md).

## Example: Specify conditional settings at the module level

You might have a group of customers who are considered preferred customers. Instead of setting up print management at the account level for each customer, you can use conditional settings to print "Preferred Customer Copy" on documents for preferred customers and "Customer Copy" for all other customers. To do this, set up conditional settings at the module level.

1.  From the Accounts receivable **Form setup** form, open the **Print management setup** form.

2.  Expand the **Free text invoice** list, right-click the copy record titled **Customer Copy**, and select **New**. A conditional setting is displayed in the list.

3.  In the right pane, enter a description for the setting, such as Preferred Customers.

4.  Click **Select**, select the range of customers that includes your preferred customers, and then click **OK**.

5.  Enter Preferred Customer Copy as the footer text.

When you post free text invoices, the customer copy for customers who are included in the query results for the conditional setting will display "Preferred Customer Copy" as the footer text. The customer copy for all other customers will display "Customer Copy," because that is the footer text that is associated with the default setting for the **Customer Copy** record.

## Example: Specify a custom report format at the account level

You might use a custom report format for specific accounts. For example, you might have a format that includes more detailed line information when an invoice is generated for a specific account. To do this, you must have a developer create a custom report format and add it to the Application Object Tree (AOT). Then, you can create a copy record that contains the print management specification for the customer account.

1.  Select a customer in the **Customers** list or form, and from that list or form, open the **Print management setup** form.

2.  Expand the **Free text invoice** list, right-click the copy record titled **Customer Copy**, and select **Copy**. A new copy record is created, which is effective only for the selected customer.

3.  Enter a name for the copy, such as Custom Format Copy.

4.  Select a report format. The options in the list include custom reports that have been created by a developer and added to the AOT.

## See also

[About print management originals, copies, and settings](about-print-management-originals-copies-and-settings.md)

[About print management document types and modules](about-print-management-document-types-and-modules.md)

[Print management setup (form)](https://technet.microsoft.com/library/hh209383\(v=ax.60\))

  


