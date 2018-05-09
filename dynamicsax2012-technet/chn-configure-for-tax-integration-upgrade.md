---
title: (CHN) Configure for tax integration upgrade
TOCTitle: (CHN) Configure for tax integration upgrade
ms:assetid: ba1c5dd4-56df-4dce-9a4e-482133758048
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ714199(v=AX.60)
ms:contentKeyID: 49651308
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Configure for tax integration upgrade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Configure for tax integration upgrade** task of the **Preprocessing upgrade checklist** allows configuration for improved integration of the Chinese tax structure into Microsoft Dynamics AX.

## Chinese tax integration

In releases before Microsoft Dynamics AX 2012 R2, exporting value-added tax (VAT) invoices data to the Chinese Golden Tax system required the following one-time manual operations:

  - Line-by-line setup of Microsoft Dynamics AX invoices to support the VAT invoice file format provided by the tax authorities.

  - Mapping of data relations for each invoice data source type, defining which fields to export to the text file.

Microsoft Dynamics AX 2012 R2 simplifies handling of the Chinese tax structure by integrating this information into the new tax integration function. Support is provided for free text invoices, project sales invoices, and use of the Application Integration Framework (AIF) to generate VAT export and import invoices.

The Microsoft Dynamics AX 2012 R2 upgrade process makes the following changes on the target system during data upgrade:

1.  Identifies from the data sources whether the exported or imported file is an invoice or credit note.

2.  Determines whether the data source of an exported or imported file is a sales order, return order, free text, or project invoice.

3.  Removes existing redundant tax profiles and links one sales tax code with one tax profile.
    

    > [!NOTE]
    > <P>In Microsoft Dynamics AX 2012 R2, the configuration for tax integration upgrade checklist task is available only when the <STRONG>System parameter</STRONG> checklist task is complete.</P>



## Configure tax integration for upgrade

Click the **Configure for tax integration upgrade** task to open the **Set up for tax integration profile upgrade** form. Use the form to set up tax integration profiles for a company. Each company can have multiple VAT tax codes that are specified in export invoices. However, you must map one tax integration profile to one tax code.

1.  In the **Set up for tax integration profile upgrade** form, select a partition.

2.  For each company in the partition, in the **Sales tax code** field, select a VAT code percentage.

3.  Repeat steps 1 and 2 until profiles have been configured for all companies.

4.  When you have finished, click **Set to ready for upgrade** to close the form and mark the task as complete.

## See also

[(CHN) Configure for tax integration upgrade (form)](https://technet.microsoft.com/en-us/library/jj713619\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

