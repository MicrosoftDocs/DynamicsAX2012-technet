---
title: (BRA) Create and post a sales order
TOCTitle: (BRA) Create and post a sales order
ms:assetid: fea69605-a462-4041-8b29-e6da584c9f0b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ822924(v=AX.60)
ms:contentKeyID: 50117581
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales invoice
- BRA
- Brazil
- create a sales invoice
- post a sales invoice
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a sales order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a sales order by specifying the Código Fiscal de Operações e Prestações (CFOP) code, operation type, and fiscal presence type for the operation. You can summarize the customer invoices before you post the sales order. The presence type of a fiscal operation in a sales order is used as a parameter to group customer invoices, quotations, confirmations, picking lists, and packing slips during posting.

When you post a sales order, a fiscal document is generated with the total amounts, general ledger transactions, and posted sales taxes information.

## Create a sales order

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order.

3.  In the **Sales order** form, on the **Action Pane**, click **Header view**, and then click the **Address** FastTab.

4.  In the **Delivery address** field, select a delivery address for the sales order. The **CNPJ/CPF** and **IE** fields are updated with the Cadastro Nacional da Pessoa Jurídica (CNPJ)/Cadastro de Pessoas Físicas (CPF) and Inscrição Estadual (IE) of the customer, based on the address that is selected as the delivery address for the customer in the **Customers** form. If the CNPJ/CPF and IE are not specified for the address, the **CNPJ/CPF** and **IE** fields in the **Sales order** form are updated with the CNPJ/CPF and IE on the **Fiscal information** FastTab in the **Customers** form.
    

    > [!NOTE]
    > <P>If the delivery address for the customer is changed to an address that is not available in the <STRONG>Customers</STRONG> form, you can enter the taxpayer registration number and the state registration number in the <STRONG>CNPJ/CPF</STRONG> and <STRONG>IE</STRONG> fields on the <STRONG>General</STRONG> FastTab in the <STRONG>New address</STRONG> form.</P>



5.  Click the **Fiscal information** FastTab.

6.  In the **Operation type** field, select the operation type that specifies whether the sales invoice generates accounting entries or inventory movement, or whether it creates customer transactions. You can leave this field blank if the sales invoice generates both inventory movement and customer transactions.

7.  In the **Presence type** field, modify the presence type of the fiscal operation that you specified for the customer on the **Fiscal information** FastTab in the **Customers** form, if required. If you create a new sales order for a vendor by copying an existing sales order, the presence type of the original sales order is applied to the new copied sales order.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



8.  On the **Action Pane**, click **Line view**, and then create a sales order line.

9.  In the **Sales order lines** grid, in the **Site** field, select the site for the selected sales order line. The tax groups in the **Sales tax group** and **Item sales tax group** fields on the **Setup** tab on the **Line details** FastTab are updated based on the tax matrix that is attached to the fiscal establishment of the site. You can also update the sales tax group and item sales tax groups in the **Sales tax group** and **Item sales tax group** fields.

10. In the **CFOP** field, select the CFOP code for the sales order line. CFOP codes are available based on the fiscal establishment of the site, order type, operation type, location of the customer, and delivery address of the customer.

## Post a sales order

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click the sales order to post.

3.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice** to open the **Posting invoice** form.

4.  Select the **Posting** and **Print invoice** check boxes to post the sales order and print the fiscal document.

5.  Click **OK** to post the sales order.
    

    > [!NOTE]
    > <P>You can use the <STRONG>Summary update for</STRONG> field on the <STRONG>Other</STRONG> tab in the <STRONG>Posting invoice</STRONG> form to summarize the customer invoices before posting the sales order. When you post a sales order, one fiscal document is created for every fiscal establishment, and the fiscal document is split based on the information that you set up for invoices in the <STRONG>Split based on</STRONG> field group on the <STRONG>Summary update</STRONG> FastTab in the <STRONG>Accounts receivable parameters</STRONG> form. Gift cards added to the sales order will not generate fiscal documents. For more information, see <A href="https://technet.microsoft.com/en-us/library/jj863738(v=ax.60)">(BRA) Accounts receivable parameters (modified form)</A>.</P>



## See also

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj911252\(v=ax.60\))

[(BRA) Set up fiscal document types](bra-set-up-fiscal-document-types.md)

[(BRA) Fiscal document types (form)](https://technet.microsoft.com/en-us/library/jj710551\(v=ax.60\))

[(BRA) Set up operation types](bra-set-up-operation-types.md)

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[Summary update sales and purchase orders](https://technet.microsoft.com/en-us/library/aa553732\(v=ax.60\))

  


