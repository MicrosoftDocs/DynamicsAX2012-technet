---
title: (ITA) Generate, print, and export the Intrastat report
TOCTitle: (ITA) Generate, print, and export the Intrastat report
ms:assetid: 120b1e06-8de0-4a80-830f-0b4b72139780
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242141(v=AX.60)
ms:contentKeyID: 36056038
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Intrastat report
- Italy
---

# (ITA) Generate, print, and export the Intrastat report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Legal entities in Italy must submit a periodic list that contains the reverse charges that are calculated on Value Added Tax (VAT) sales transactions with other VAT-registered entities in the European Union (EU). You can generate this Intrastat report based on the purchase and sales of products and services. The transactions are compressed to include services and foreign currency transactions, and the printed Intrastat report will include service information. The Intrastat report is exported as an ASCII file and submitted to the customs office.

You must complete the following tasks before you generate the Intrastat report:

  - Set up the Intrastat transaction code and transport method as single digit codes in the **Transaction codes** and **Transport method** forms.

  - Set up the delivery terms, port, and statistical procedures for Intrastat reporting in the **Modes of delivery**, **Port**, and **Statistics procedure** forms.

  - Assign six-digit commodity codes for services and two, four, or eight digit codes for products in the **Commodity codes** form. The weight, transaction code, additional units, port, terms of delivery, transport mode, and statistical procedure are not required for services.

Use the following procedures to set up Intrastat parameters, transfer Intrastat transactions, and generate the Intrastat report.

## Set up Intrastat parameters

Use the **Foreign trade parameters** form to specify the compression mode and the county of origin or destination for the Intrastat report.

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  On the **Intrastat** link, in the **County of origin/destination** field, select the county of origin or destination for the transactions.

3.  Click **Compress** to open the **Compression of Intrastat** form.

4.  In the list of **Available** fields, select **Currency**, and then click **\<** to add fields in the **Selected** field.

5.  Click **OK** to close the **Compression of Intrastat** form.

6.  In the **Foreign trade parameters** form, click the **Check setup** tab, and then select the **County** check box to include county details.

7.  Close the form to save your changes.

## Transfer Intrastat transactions

You must transfer the purchase and sales transactions to the **Intrastat** form, and then verify the details before you generate the Intrastat report. In the Intrastat report, the products are reported based on the invoice date. The services are reported based on the document date.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Click **Transfer IT** to open the **Selection** form.

3.  Select the purchase or sales transactions, and then click **OK** to transfer the transaction details in the **Intrastat** form.
    

    > [!NOTE]
    > <P>If the selected purchase or sales transactions do not contain the invoice date, method of payment, and mode of delivery, you must manually select these details on the <STRONG>General</STRONG> tab.</P>



4.  Click the **General** tab, and then in the **Invoice date** field, enter the invoice date for the product or the document date for the service. If the document date is not available for the service, enter the invoice date.

5.  In the **Method of payment** and **Mode of delivery** fields, select the method of payment and mode of delivery for a product.

6.  In the **Original Intrastat record**, **Customs code**, and **Statement number** fields, enter the appropriate details if the transaction represents a correction to a previously reported Intrastat transaction.

7.  Click **Validate** to validate the transactions.

## Generate the Intrastat report

You can generate the Intrastat report that contains the Intrastat transactions as an ASCII file. You can also compress the Intrastat details to view as a single transaction based on the selection that you have made in the **Compression of Intrastat** form.

1.  In the **Intrastat** form, click **Output** \> **Diskette IT** to open the **Create Intrastat diskette in Italian layout** form.

2.  In the **File name** field, select the file to import the Intrastat report to.

3.  Select the **Export** and **Import** check boxes to include Intrastat purchase and sales transactions.

4.  In the **Start date** and **End date** fields, select the starting date and the ending date of the reporting period.

5.  Click **OK** to generate the Intrastat report.

## See also

[About Intrastat](about-intrastat.md)

[Intrastat (form)](https://technet.microsoft.com/en-us/library/aa619055\(v=ax.60\))

[(ITA) Make diskette for Intrastat in Italian layout (class form)](https://technet.microsoft.com/en-us/library/aa587754\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

