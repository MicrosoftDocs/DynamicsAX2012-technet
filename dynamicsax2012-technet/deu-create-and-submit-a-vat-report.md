---
title: (DEU) Create and submit a VAT report
TOCTitle: (DEU) Create and submit a VAT report
ms:assetid: 4609b89f-0e8d-49d0-8d30-ec877b658132
ms:mtpsurl: https://technet.microsoft.com/library/Hh242385(v=AX.60)
ms:contentKeyID: 36056899
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Germany
- VAT report
audience: Application User
ms.search.region: Germany
---

# (DEU) Create and submit a VAT report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Sales tax payment** form to create the VAT declaration as an .xml file. The declaration is also updated to the log in the **Electronic tax declaration log** form. Use the **Electronic tax declaration log** form to create and submit the **German VAT declaration** by using Elektronische Steuereklärungen (ELSTER).

## Copy new certificates and style sheets for ELSTER

Before you create a VAT report, you must copy the additional certificates and style sheet files to submit the VAT declaration by using ELSTER. To complete the ELSTER setup, follow these steps:

1.  After the Microsoft Dynamics AX client is set up, copy all the files in the ElsterTransferHandler.DLL library to the Application folder\\Client\\Bin folder to replace the existing ElsterTransferHandler.DLL library in the \\Client\\Bin folder.

2.  Double-click the **Coala2019.PERM** file, and then install the new COALA2019.PERM certificate on your computer.

3.  In the **Certificate import wizard** form, select **Trusted Root Certification Authorities** in the **Certificate store** field.

4.  Copy the style sheet files, such as **elsteranmeldung**, **elsterbasis**, **geldbetraege**, **steuernummer**, and **ustva** for ELSTER in the Application folder\\Client\\Bin folder. These files are required so that the VAT declaration can be displayed correctly.

## Prerequisites

Complete the following setup procedures to generate the electronic tax declaration:

  - Set up the electronic tax declaration to be submitted by using ELSTER. For more information, see [(DEU) Set up electronic tax declaration](deu-set-up-electronic-tax-declaration.md).

  - Set up a sales tax authority with the German report layout. For more information, see [Set up sales tax authorities](set-up-sales-tax-authorities.md).

  - Set up a settlement period that contains a sales tax authority with the German report layout. For more information, see [Set up a sales tax settlement period](set-up-a-sales-tax-settlement-period.md).

  - Set up the sales tax reporting codes for the German report layout. For more information, see [Sales tax reporting codes (form)](https://technet.microsoft.com/library/aa588316\(v=ax.60\)).

  - Set up sales tax codes, sales tax groups, and item sales tax groups. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md), [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md), and [Create item sales tax groups](create-item-sales-tax-groups.md).

## Create the VAT declaration as an .xml file

1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.

2.  In the **Settlement period** field, select the sales tax settlement period that contains a sale tax authority with the German report layout.

3.  In the **From date** field, specify the first day of the sales tax settlement period to be calculated. This corresponds to the date in the **From date** field on the **Sales tax settlement periods** form.

4.  In the **Transaction date** field, select the sales tax settlement posting date.

5.  In the **Sales tax payment version** field, select the version of the sales tax payment to be settled:
    
      - **Original** – Sales tax transactions of the first posted settlement calculation for the period interval.
    
      - **Corrections** – Sales tax transactions that are not included in the first posted settlement calculation for the period interval. The report includes all subsequent payments that are posted for the settlement period.
    
      - **Latest corrections** – Sales tax transactions that are included in the most recent settlement calculation made for the period. If you select the **Update** check box and this option, the settlement calculation of the current job is the most recent settlement calculation.
    
      - **Total list** – All sales tax transactions to be settled in the current period.

6.  Select the **Update** check box to update the sales tax payment settlement before it is printed.

7.  Click **OK** to open the **German sales tax report** form.

8.  Select the **Create electronic tax document** check box to generate the electronic file of the VAT declaration report.

9.  Select the **Documents submitted separately** check box to indicate that the tax documents are submitted separately.

10. In the **Style sheet for preview** field, specify the path of the style sheet that is used to preview the electronic VAT declaration report.

11. Click **OK** to create the VAT declaration as an .xml file, and then add it to the electronic tax declaration log in the **Electronic tax declaration log** form.

12. Close the forms to save your changes.

## Submit the German VAT declaration

1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Electronic tax declaration log**.

2.  Select a document to be submitted.
    

    > [!NOTE]
    > <P>You can select a document, and then click the <STRONG>Preview</STRONG> tab to view the VAT declaration by using the specified style sheet. You can also click <STRONG>File transactions</STRONG> to view the transactions of the selected document.</P>



3.  Click **Submit** to submit the electronic tax declaration.
    

    > [!NOTE]
    > <P>If the <STRONG>Use of proxy server</STRONG> and <STRONG>Proxy server authentication required</STRONG> check boxes are selected in the <STRONG>Electronic tax declaration setup</STRONG> form (Click <STRONG>General ledger</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Sales tax</STRONG> &gt; <STRONG>Electronic tax declaration setup</STRONG>.), you must enter proxy credentials to submit the electronic tax declaration.</P>



4.  Close the form to save your changes.

## See also

[Sales tax payment (class form)](https://technet.microsoft.com/library/aa598539\(v=ax.60\))

[(DEU) Electronic tax declaration log (form)](https://technet.microsoft.com/library/aa620200\(v=ax.60\))

  


