---
title: (SWE) Generate an Intrastat file for an EU customer
TOCTitle: (SWE) Generate an Intrastat file for an EU customer
ms:assetid: 14061d84-3bdc-44c3-a3c6-b622d743be1c
ms:mtpsurl: https://technet.microsoft.com/library/Hh242145(v=AX.60)
ms:contentKeyID: 36056051
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Sweden
- EU
- intrastat
audience: Application User
ms.search.region: Sweden
---

# (SWE) Generate an Intrastat file for an EU customer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Intrastat declaration is the compulsory monthly declaration of movements of goods between European Union (EU) member states. Swedish companies can export Intrastat details for vendor transactions in a specific file format, and then submit the formatted file to Statistiska centralbyrån (SCB) using the Intrastat Data Entry Package (IDEP).


> [!NOTE]
> <P>You can generate the Intrastat file only for the legal entities whose primary address is in Sweden.</P>



Before generating the Intrastat file, complete the following tasks:

  - Select the **Foreign trade** configuration key.

  - Set up Intrastat parameters in order to generate Intrastat transaction details and compression details.

  - Create an item, and then specify the **Commodity**, **Additional units**, and **Net weight** fields for the Intrastat transaction. For more information, see [Foreign trade parameters (form)](https://technet.microsoft.com/library/aa620385\(v=ax.60\)), [Compression of Intrastat (form)](https://technet.microsoft.com/library/aa584795\(v=ax.60\)), [Released product details (form)](https://technet.microsoft.com/library/aa615563\(v=ax.60\)), and [Create items](create-items.md).

## Set up an EU customer

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  On the **Action Pane**, in the **New** section click **Customer** to create a new EU customer.

3.  In the **Name** and **Customer group** fields, enter the customer name and select the customer group.

4.  Click the **Address** FastTab and then click **Add** to open the **Address** form. For more information, see [Address setup (form)](https://technet.microsoft.com/library/hh209301\(v=ax.60\)).

5.  Select the **Primary** check box to indicate that the address is the customer's primary address. The check box is available only when you clear the **Private** check box.

6.  Click **OK** to save the new address.

7.  Close the form to save your changes.

## Generate the Intrastat file

To generate the Intrastat file, create and post a sales invoice for the selected EU customer and then transfer the Intrastat details for the customer transaction.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**. If any Intrastat transactions are present in the **Intrastat** form, select them and click **Delete**. For more information, see [About Intrastat](about-intrastat.md) and [Intrastat (form)](https://technet.microsoft.com/library/aa619055\(v=ax.60\)).

2.  In the **Intrastat** form, click **Transfer SE** to open the **Dialog** form.

3.  Select the appropriate check boxes to indicate the document types that the transactions are to be transferred from.

4.  Click **Select** to open the **Intrastat** form and select the transfer criteria, and then click **OK**.

5.  In the **Dialog** form, click **OK** to transfer the transactions to the **Intrastat** form.
    

    > [!NOTE]
    > <P>If similar information is contained in multiple lines in the <STRONG>County</STRONG>, <STRONG>Tariff number</STRONG>, and <STRONG>Direction</STRONG> fields, click <STRONG>Update</STRONG> &gt; <STRONG>Compress</STRONG> to compress the transaction lines into a single line.</P>



6.  Click **Output** \> **Diskette SE** to open the **Create Intrastat diskette in Swedish layout** form.
    

    > [!NOTE]
    > <P>Click <STRONG>Output</STRONG> &gt; <STRONG>List SE</STRONG> or <STRONG>Output</STRONG> &gt; <STRONG>Form SE</STRONG> to print the Intrastat file.</P>



7.  In the **File name** field, specify the file name and path of the report file.

8.  In the **Direction** field, select **Dispatches** to generate details about sales and shipment of items to customers in EU member states. Select **Arrivals** to generate details about purchase and shipment of items from vendors in EU member states.

9.  In the **From** and **To** fields, select the starting and ending dates for the Intrastat transactions file.

10. Click **Select** to open the **Intrastat** form, select the filter criteria, and then click **OK**.

11. In the **Create Intrastat diskette in Swedish layout** form, click **OK** to generate and export the Intrastat transaction file, which contains the sales transactions and item details. Semicolons are used as the field delimiters in the exported file.

12. Close the form to save your changes. The exported file is imported into the IDEP program, approved, and submitted to SCB.

## See also

[(SWE) Make diskette for Intrastat in Swedish layout (class form)](https://technet.microsoft.com/library/hh242715\(v=ax.60\))

[(SWE) Generate an Intrastat file for an EU vendor](swe-generate-an-intrastat-file-for-an-eu-vendor.md)

  


