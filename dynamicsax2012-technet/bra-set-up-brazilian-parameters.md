---
title: (BRA) Set up Brazilian parameters
TOCTitle: (BRA) Set up Brazilian parameters
ms:assetid: 8d8fb2f6-6a27-4abe-8585-78391de8bf2e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853381(v=AX.60)
ms:contentKeyID: 50396750
ms.date: 07/08/2015
mtps_version: v=AX.60
f1_keywords:
- parameters
- BRA
- Brazil
- Brazilian parameters
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up Brazilian parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to set up parameters for Brazilian features.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3.</P>



1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Brazilian parameters**.

2.  Select the **Enable CFPS code** check box to activate fiscal operation of services (CFPS) codes.

3.  In the **Financial dimension for cost center** field, select the financial dimension to use for the cost center.

4.  In the **Purchase requisition** field group, in the **Operation type** field, select the default operation type for purchase requisitions.

5.  In the **Requests for quotations** field group, in the **Operation type** field, select the default operation type for requests for quotations.

6.  Click **Fiscal document**, and then in the **Fiscal document** area, set up the following parameters for fiscal documents:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Primary method of payment</strong></p></td>
    <td><p>Select <strong>Duplicate</strong>, <strong>Check</strong>, <strong>Promissory note</strong>, <strong>Receipt</strong>, or <strong>Other</strong> as the primary method of payment for purchases.</p>
    <p>If you selected <strong>Other</strong> in the <strong>Primary method of payment</strong> field in the <strong>Purchase method</strong> field group, in the <strong>Description</strong> field, enter the description of the primary method of payment for purchases.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Text ID</strong> (<strong>SUFRAMA text for issue fiscal document</strong> field group)</p></td>
    <td><p>Select the identification code for the default fiscal document text to print on the fiscal documents that are issued to customers from the Superintendência da Zona Franca de Manaus (SUFRAMA) region.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Text ID</strong> (<strong>Withholding tax text for issue fiscal document</strong> field group)</p></td>
    <td><p>Select the identification code of the default fiscal document text for withholding tax to print on the fiscal documents.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Primary method of payment</strong>(<strong>Sales method</strong> field group)</p></td>
    <td><p>Select <strong>Duplicate</strong>, <strong>Check</strong>, <strong>Promissory note</strong>, <strong>Receipt</strong>, or <strong>Other</strong> as the primary method of payment for sales.</p>
    <p>If you selected <strong>Other</strong> in the <strong>Primary method of payment</strong> field in the <strong>Purchase method</strong> field group, in the <strong>Description</strong> field, enter the description of the primary method of payment for sales.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Product type</strong></p></td>
    <td><p>Select the default product type for items that are used for consumption.</p>
    <p>For an item that is purchased for consumption, you can select this product type in the <strong>Product type</strong> field on the <strong>Fiscal information</strong> FastTab in the <strong>Released product details</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Volume type</strong> and <strong>Volume quantity</strong> fields</p></td>
    <td><p>Enter the default volume type and volume quantity for items in the fiscal documents.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Enable fix issue date</strong> check box</p></td>
    <td><p>Select this check box to set up the fixed fiscal document issue date for fiscal document types.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Item</strong> field (<strong>Free text invoice</strong> field group)</p></td>
    <td><p>Select the identification code for the item that is used to post fiscal documents from free text invoices.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Service</strong> field (<strong>Free text invoice</strong> field group)</p></td>
    <td><p>Select the identification code for the service that is used to post fiscal documents from free text invoices that have free text invoice lines for which the <strong>Service invoice</strong> check box is selected on the <strong>Fiscal information invoice line</strong> tab on the <strong>Line details</strong> FastTab in the <strong>Free text invoice</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document type</strong></p></td>
    <td><p>Select the identification code for the default document type for fiscal document texts. You can select a document type that is not assigned to the fiscal document text that is attached to a fiscal document.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>You cannot modify the document type if a fiscal document text is attached to a fiscal document.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Item</strong> field (<strong>Tax fiscal documents</strong> field group)</p></td>
    <td><p>Select the identification code for the item that is used to create tax fiscal documents.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Sales tax code for PIS</strong> field (<strong>Tax fiscal documents</strong> field group)</p></td>
    <td><p>Select the default sales tax code for Programa de Integração Social (PIS) that is used for tax fiscal documents.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Sales tax code for COFINS</strong> field (<strong>Tax fiscal documents</strong> field group)</p></td>
    <td><p>Select the default sales tax code for Contribuição para o financiamente da securidade social (COFINS) that is used for tax fiscal documents.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Fiscal document source text</strong></p></td>
    <td><p>Select the identification code for the fiscal document source text that is printed on the complementary fiscal documents.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Line amount is based on</strong> field (<strong>Import declaration</strong> field group)</p></td>
    <td><p>Select whether the line amounts in import fiscal documents are based on the Freight on Board (FOB) or Carriage, Insurance, and Freight (CIF).</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Text ID</strong> field (<strong>Import declaration</strong> field group)</p></td>
    <td><p>Select the identification code for the fiscal document text that is printed on import fiscal documents.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Sales tax code for COFINS</strong> field (<strong>Tax complementary fiscal document</strong> field group)</p></td>
    <td><p>Select the default sales tax code for COFINS that is used for tax complementary fiscal documents.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Sales tax code for PIS</strong> field (<strong>Tax complementary fiscal document</strong> field group)</p></td>
    <td><p>Select the default sales tax code for PIS that is used for tax complementary fiscal documents.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Unit</strong> field (<strong>Tax complementary fiscal document</strong> field group)</p></td>
    <td><p>Select the default unit to use in fiscal document lines that are created for hour, expense, on-account, or item project transactions.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax basic rate field group</strong></p></td>
    <td><p>Indicate the tax rate value for each tax regime of PIS and COFINS assessments. This information allows the identification of regime cumulative and non-cumulative for each tax transaction.</p>
    <ul>
    <li><p><strong>Basic tax value for PIS in cumulative regime</strong> – Enter the percentage of tax rate.</p></li>
    <li><p><strong>Basic tax value for PIS in non cumulative regime</strong> – Enter the percentage of tax rate.</p></li>
    <li><p><strong>Basic tax value for COFINS in cumulative regime</strong> – Enter the percentage of tax rate.</p></li>
    <li><p><strong>Basic tax value for COFINS in non cumulative regime</strong> – Enter the percentage of tax rate.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


7.  Click **Taxation code**, and then in the **Taxation code** area, select the **Mandatory** check box for the tax types that require taxation codes.
    

    > [!NOTE]
    > <P>You must select the <STRONG>Mandatory</STRONG> check box for <STRONG>ICMS</STRONG> and <STRONG>IPI</STRONG> tax types.</P>



8.  In AX 2012 R3: Click **Retail**, and then in the **Retail** area, specify the values in the following fields:
    
      - **Sales tax code for PIS** – Select the default sales tax code for PIS that is used for the referenced fiscal document model 02.
    
      - **Sales tax code for COFINS** – Select the default sales tax code for COFINS that is used for the referenced fiscal document model 02.
    
      - **Sales tax code for ICMS** – Select the default sales tax code for Imposto sobre Circulação de Mercadorias e Serviços (ICMS) that is used for the referenced fiscal document model 02.

## See also

[(BRA) Brazilian parameters (form)](https://technet.microsoft.com/en-us/library/jj822920\(v=ax.60\))

  


