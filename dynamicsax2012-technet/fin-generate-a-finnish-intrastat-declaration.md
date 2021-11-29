---
title: (FIN) Generate a Finnish Intrastat declaration
TOCTitle: (FIN) Generate a Finnish Intrastat declaration
ms:assetid: 984fe965-37bc-4c34-9812-8c6d2c8a2c4c
ms:mtpsurl: https://technet.microsoft.com/library/Hh209415(v=AX.60)
ms:contentKeyID: 36058675
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- declaration
- Intrastat
- Finland
audience: Application User
ms.search.region: Finland
---

# (FIN) Generate a Finnish Intrastat declaration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Intrastat declaration is used to report the movement of goods between European Union (EU) member states. Finnish companies can use the Intrastat form to generate an Intrastat declaration in CSV format for submittal to the Finnish customs authority. For more information, see [About Intrastat](about-intrastat.md).

Before you generate an Intrastat declaration, complete the following tasks:

  - Set up Intrastat parameters to generate Intrastat transaction details and compression details. You can compress export transactions based on commodity code, transaction code, transport, or country/region. Import transactions can be compressed on the basis of commodity, country/region, or country/region of origin. For more information, see [Compress (class form)](https://technet.microsoft.com/library/aa590820\(v=ax.60\)), [Compression of Intrastat (form)](https://technet.microsoft.com/library/aa584795\(v=ax.60\)) and [Foreign trade parameters (form)](https://technet.microsoft.com/library/aa620385\(v=ax.60\)).

  - Create an item and specify the **Commodity**, **Additional units**, and **Net weight** fields for the Intrastat transaction. For more information, see [Commodity codes (form)](https://technet.microsoft.com/library/aa617816\(v=ax.60\)).

  - Create an Intrastat service point. For more information, see [(FIN) Intrastat service point (form)](https://technet.microsoft.com/library/aa600293\(v=ax.60\)) and [Intrastat (form)](https://technet.microsoft.com/library/aa619055\(v=ax.60\)).

## Generate the Intrastat declaration

Use this procedure to generate the Intrastat declaration. If you selected the **Intrastat** check box for a charge in the **Charges code** form, the charge is included in the Intrastat amount. For more information, see [Charges code (form)](https://technet.microsoft.com/library/aa598932\(v=ax.60\)), [Create charges codes](create-charges-codes.md), and [About sales order information for shipping carriers](about-sales-order-information-for-shipping-carriers.md).

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.
    

    > [!NOTE]
    > <P>If any Intrastat transactions are present in the <STRONG>Intrastat</STRONG> form, select them and click <STRONG>Delete</STRONG>. For more information, see <A href="https://technet.microsoft.com/library/aa619055(v=ax.60)">Intrastat (form)</A> and <A href="about-intrastat.md">About Intrastat</A>.</P>



2.  Click **Transfer FI** to open the **Dialog** form.

3.  Select one or all of the following check boxes to transfer the transactions to the **Intrastat** form.
    
      - **Customer invoice** – Transfer the customer invoice transactions.
    
      - **Customer packing slips** – Transfer the customer packing slip transactions.
    
      - **Vendor invoice** – Transfer the vendor invoice transactions.
    
      - **Vendor product receipts** – Transfer the vendor product receipt transactions.
    
      - **Project invoice** – Transfer the project invoice transactions.

4.  Click **Select** to open the **Intrastat** form and select the criteria for transferring the transactions. Click **OK** to close the **Intrastat** form.

5.  In the **Dialog** form, click **OK** to close the **Dialog** form and transfer the selected transactions to the **Intrastat** form.

6.  In the **Intrastat** form, click **Output** \> **Diskette FI** to open the **Create Intrastat diskette in Finnish layout** form.

7.  In the **File name** field, specify the file name and path for the Intrastat file. The file name should have a .csv extension.

8.  In the **Direction** field, select **Dispatches** to generate details about supply and shipment of items to customers in EU member states.
    

    > [!NOTE]
    > <P>Select <STRONG>Arrivals</STRONG> to generate details about acquisition and receipt of items from vendors in EU member states.</P>



9.  In the **From** and **To** fields, select the starting and ending dates for the Intrastat transaction file.

10. Click **Select** to open the **Intrastat** form, select the criteria, and then click **OK** to return to the **Create Intrastat diskette in Finnish layout** form.

11. Click **OK** to generate and export the Intrastat transaction details.

12. Click **Output** \> **List FI** to open the **Intrastat transactions** form, and then specify the required details and print the Intrastat report.

13. Click **Output** \> **Form FI** to print the Intrastat file.

14. Close the form to save your changes.

## See also

[Intrastat (form)](https://technet.microsoft.com/library/aa619055\(v=ax.60\))

[(FIN) Make diskette for Intrastat in Finnish layout (class form)](https://technet.microsoft.com/library/hh209641\(v=ax.60\))

  


