---
title: (BRA) Create a quotation
TOCTitle: (BRA) Create a quotation
ms:assetid: 1f9fdcbf-1ddc-4619-aaa4-ae5efadf2ae6
ms:mtpsurl: https://technet.microsoft.com/library/JJ710431(v=AX.60)
ms:contentKeyID: 49384323
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales quotations
- BRA
- Brazil
- create sales quotations
- BR - 00030
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create a quotation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a quotation by specifying fiscal information, such as the operation type and the Código Fiscal de Operações E Prestações (CFOP) code.

When you create a quotation line, you can select a CFOP code in the **CFOP** field. The CFOP codes that are available in this field depend on the fiscal establishment of the site that you selected in the **Site** field. The tax groups in the **Sales tax group** and **Item sales tax group** fields are also updated based on the tax matrix.

1.  Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**.

2.  Create a quotation.

3.  Click **Header view**, and then click the **Fiscal information** FastTab.

4.  In the **Operation type** field, select the operation type for the sales quotation.

5.  Select the **Final user** check box to indicate that the customer is the final user. If you select this check box, the Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) tax includes the Imposto Sobre Produtos Industrializados (IPI) tax and any freight charges.

6.  Click **Line view**, and then create a quotation line.

7.  In the **Lines** grid, in the **Site** field, select the site for the quotation line. The tax groups in the **Sales tax group** and **Item sales tax group** fields on the **Setup** tab on the **Line details** FastTab are updated based on the tax matrix. You can also select different tax groups.
    

    > [!NOTE]
    > <P>If the <STRONG>Site</STRONG> field is not available, in the <STRONG>Lines</STRONG> grid, click <STRONG>Sales quotation line</STRONG> &gt; <STRONG>Dimensions</STRONG>, and then select the <STRONG>Site</STRONG> check box. Click <STRONG>OK</STRONG>.</P>



8.  In the **CFOP** field, select the CFOP code for the quotation line.
    

    > [!NOTE]
    > <P>The CFOP codes that are available depend on the fiscal establishment of the site that you selected in the <STRONG>Site</STRONG> field.</P>



9.  In the **SUFRAMA discount** field, enter the discount percentage for the customer from the Superintendência da Zona Franca de Manaus (SUFRAMA) region.

When you receive an approval from the customer or prospective customer, you can confirm the quotation. For more information, see [Update a quotation](update-a-quotation.md). After you confirm the sales quotation, a sales order is created for the quotation in the **Sales order** form.

  


