---
title: (NOR) Set up the layout for an eInvoice
TOCTitle: (NOR) Set up the layout for an eInvoice
ms:assetid: 7011a4b5-5ae4-4797-94ca-54470bbe4a68
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231825(v=AX.60)
ms:contentKeyID: 36058053
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Norway
---

# (NOR) Set up the layout for an eInvoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Accounts receivable** \> **Setup** \> **e-Invoice** \> **e-invoice**.

2.  In the **e-invoice** field, enter an identification code for the eInvoice layout, and enter a descriptive name in the **Name** field.

3.  Specify the template for the eInvoice in the **Template** field.
    

    > [!NOTE]
    > <P>The templates are predefined in the system, and the formats are based on the Bankenes Betalingssentral (BBS) standards.</P>



4.  Select the query for the eInvoice in the **Query name** field. The information that you enter in the eInvoice comes from the tables that are defined in this query.

5.  Enter the heading to use for the eInvoice in the **Heading** field.
    

    > [!NOTE]
    > <P>You can specify text titles in the <STRONG>Phone title</STRONG>, <STRONG>Telefax title</STRONG>, and <STRONG>E-mail title</STRONG> fields on the <STRONG>General</STRONG> tab.</P>



6.  Click the **eInvoice header** tab to define fields for the eInvoice header. In the **eInvoice field** field, select the header field for the eInvoice. You must define the layout for the **Invoice amount** and **Payment ID** in the **eInvoice field** field.
    

    > [!NOTE]
    > <P>If you select <STRONG>Free text top</STRONG> or <STRONG>Free text bottom</STRONG>, you can provide additional details, such as the website of your company, in the <STRONG>Text</STRONG> field.</P>



7.  In the **Table name** field, select the table for the **eInvoice field**, and then select the field name for the table in the **Field name** field.

8.  Specify a heading for the field in the **Heading** field.

9.  Click the **eInvoice lines** tab to define the length and alignment for the field in the eInvoice. Enter the starting position of the text for the field in the **From position** field and the length of the text in the **Length** field.
    

    > [!NOTE]
    > <P>The ending position for the text is the last position in the defined length, and it is displayed in the <STRONG>To position</STRONG> field.</P>



10. Select the table for the field in the **Table name** field, and then select the field name for the table in the **Field name** field.

11. In the **Alignment** field, select the alignment type for the text in the field. Specify a heading for the field in the **Heading** field.

12. Close the form to save your changes.

## See also

[(NOR) e-invoice (form)](https://technet.microsoft.com/en-us/library/hh209548\(v=ax.60\))

  


