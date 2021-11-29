---
title: (BRA) Attach fiscal document texts to a fiscal document
TOCTitle: (BRA) Attach fiscal document texts to a fiscal document
ms:assetid: a3cee143-2f9b-43cc-b218-da5825832c40
ms:mtpsurl: https://technet.microsoft.com/library/JJ710582(v=AX.60)
ms:contentKeyID: 49384471
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Brazil
- (BRA)
- fiscal document
- fiscal document text
- Attach fiscal document text
audience: Application User
ms.search.region: Brazil
---

# (BRA) Attach fiscal document texts to a fiscal document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can attach fiscal document texts to fiscal documents, such as sales orders, sales order lines, purchase orders, purchase order lines, vendor invoices, and vendor invoice lines. You can also attach fiscal document texts to customer accounts, vendor accounts, and items. The fiscal document texts are printed on the fiscal documents when you post and print the fiscal documents.

The fiscal document text for a purchase order for a foreign vendor is updated based on the fiscal document text that is selected in the **Text ID** field in the **Import declaration** field group in the **Fiscal document** area in the **Brazilian parameters** form. You can also attach other fiscal document texts to the purchase order for a foreign vendor.

You must set up fiscal document source texts and document types for fiscal document texts before you attach the fiscal document texts to the fiscal documents. For more information, see [(BRA) Set up a fiscal document source text](bra-set-up-a-fiscal-document-source-text.md) and [(BRA) Set up the document type for fiscal document texts](bra-set-up-the-document-type-for-fiscal-document-texts.md).

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Select a sales order, and then on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Select a sales order, and then on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order, and then on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order, and then on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order. Select a sales order line, and then in the **Sales order lines** area, click **Sales order line** \> **Fiscal document texts**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order. Select a sales order line, and then in the **Sales order lines** area, click **Sales order line** \> **Fiscal document texts**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Double-click a purchase order. Select a purchase order line, and then in the **Purchase order lines** area, click **Purchase order line** \> **Fiscal document texts**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Double-click a purchase order. Select a purchase order line, and then in the **Purchase order lines** area, click **Purchase order line** \> **Fiscal document texts**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**. In the **Vendor invoice** form, on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**. In the **Vendor invoice** form, on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**. In the **Vendor invoice** form, in the **Lines** area, select a vendor invoice line, and then click **Invoice line** \> **Fiscal document texts**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**. In the **Vendor invoice** form, in the **Lines** area, select a vendor invoice line, and then click **Invoice line** \> **Fiscal document texts**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select a customer account, and then on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Customers** \> **All customers**. Select a customer account, and then on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select a vendor account, and then on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**. Select a vendor account, and then on the **Action Pane**, click **Fiscal document texts**.
    
    –or–
    
    Click **Product information management** \> **Common** \> **Released products**. Select an item, and then on the **Action Pane**, click **Fiscal document texts**.

2.  In the **Fiscal document texts** form, create a new record to add a fiscal document text to the fiscal document.

3.  In the **Fiscal document text** field, select an identifier for the fiscal document source text. The **Description**, **Note**, **Restriction**, **Fiscal information**, **Agency**, and **Reference process number** fields are updated with details of the fiscal document source text in the **Fiscal document source texts** form. The **Fiscal document text type** field is updated to **Inventory** or **User-defined**.
    

    > [!NOTE]
    > <P>If required, you can also modify the details in the <STRONG>Description</STRONG>, <STRONG>Note</STRONG>, <STRONG>Restriction</STRONG>, and <STRONG>Fiscal information</STRONG> fields. You can also modify or add information about fiscal processes in the <STRONG>Agency</STRONG> and <STRONG>Reference process number</STRONG> fields in the <STRONG>Process reference</STRONG> field group. You can modify the fiscal document text details only if the status of the sales order, purchase order, or vendor invoice is <STRONG>Open order</STRONG>.</P>



## See also

[(BRA) Fiscal document source texts (form)](https://technet.microsoft.com/library/jj663934\(v=ax.60\))

  


