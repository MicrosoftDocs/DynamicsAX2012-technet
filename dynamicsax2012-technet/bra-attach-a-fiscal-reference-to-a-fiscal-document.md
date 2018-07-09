---
title: (BRA) Attach a fiscal reference to a fiscal document
TOCTitle: (BRA) Attach a fiscal reference to a fiscal document
ms:assetid: a3283b3a-e52a-49f8-b03b-da812efff721
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710581(v=AX.60)
ms:contentKeyID: 49384478
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00014
---

# (BRA) Attach a fiscal reference to a fiscal document [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Brazilian legal entities can submit their fiscal and ledger information as Sistema Público de Escrituração Digital (SPED) fiscal reports. These reports also contain information about fiscal references that link several fiscal documents. These references are reported in Notas fiscais eletrônicas (NF-e) that are issued by Brazilian legal entities.

Before you generate the SPED fiscal report or NF-e, you can create fiscal references that link fiscal document references during the posting of a fiscal document. You can reference only the posted fiscal documents that are issued or received by the same fiscal establishment that issues or receives the fiscal document that is about to be posted.

## Attach a fiscal reference to a customer invoice

You can attach a reference fiscal document to the customer invoice when you post the customer invoice. You can manually set up a referenced fiscal document if the fiscal document is not available in Microsoft Dynamics AX. You can also click **Fiscal document** in the **Fiscal reference** form to select an existing fiscal document that is issued or received by the same fiscal establishment that issues or receives the fiscal document that is about to be posted.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click a sales order, or on the **Action Pane**, click **Sales order** to create a sales order. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

3.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice** to open the **Posting invoice** form.

4.  In the lower pane, click the **Setup** tab, and then click **Fiscal reference** to open the **Fiscal reference** form.

5.  To reference a fiscal document that is not available in Microsoft Dynamics AX:
    
    1.  In the **Document model** field, select the document model for the fiscal document.
    
    2.  In the **Access key** field, enter the access key for the electronic fiscal document (NF-e).
        

        > [!NOTE]
        > <P>This field is available only if you select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is selected for the document model in the <STRONG>Document model</STRONG> form.</P>

    
    3.  In the **Number** and **Series** fields, enter the number and series of the fiscal document.
        

        > [!NOTE]
        > <P>These fields are available only if you select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is not selected for the document model in the <STRONG>Document model</STRONG> form.</P>

    
    4.  In the **Date** field, enter the document date of the fiscal document.
    
    5.  In the **Direction** field, select one of the following options to indicate whether the fiscal document is related to incoming or outgoing products or services:
        
          - **Incoming**
        
          - **Outgoing**
    
    6.  In the **Issuer** field, select an option to indicate whether the fiscal document was issued by the **Fiscal establishment** or by a **Third party**.
    
    7.  In the **Account type** field, select **Customer**, **Vendor**, or **Fiscal establishment** as the account type.
    
    8.  In the **Account** field, select the customer account, vendor account, or fiscal establishment that generated the fiscal document.

6.  To select an existing fiscal document that is issued or received by the same fiscal establishment that issues or receives the fiscal document that is about to be posted:
    
    1.  Click **Fiscal document** to open the **Choose fiscal reference based fiscal documents** form.
    
    2.  On the **Customer** tab, select the customer fiscal document to reference.
        
        –or–
        
        Click the **Vendor** tab, and then select the vendor fiscal document to reference.
        
        –or–
        
        Click the **Fiscal establishment** tab, and then select the transfer fiscal document to reference.
    
    3.  Close the form.

7.  In the **Text ID** field, select the fiscal document source text for the referenced fiscal document.

8.  Close the form.

9.  In the **Posting invoice** form, click **OK** to post the customer invoice.

## Attach a fiscal reference to a vendor invoice

You can attach a reference fiscal document to the vendor invoice when you post the vendor invoice. You can manually set up a referenced fiscal document if the fiscal document is not available in Microsoft Dynamics AX. You can also click **Fiscal document** in the **Fiscal reference** form to select an existing fiscal document that is issued or received by the same fiscal establishment that issues or receives the fiscal document that is about to be posted.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click a purchase order, or on the **Action Pane**, click **Purchase order** to create a purchase order. For more information, see [(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md).

3.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice** to open the **Vendor invoice** form.

4.  On the **Action Pane**, on the **Vendor invoice** tab, click **Add fiscal reference** to open the **Fiscal reference** form.

5.  To reference a fiscal document that is not available in Microsoft Dynamics AX:
    
    1.  In the **Document model** field, select the document model for the fiscal document.
    
    2.  In the **Access key** field, enter the access key for the electronic fiscal document (NF-e).
        

        > [!NOTE]
        > <P>This field is available only if you select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is selected for the document model in the <STRONG>Document model</STRONG> form.</P>

    
    3.  In the **Number** and **Series** fields, enter the number and series of the fiscal document.
        

        > [!NOTE]
        > <P>These fields are available only if you select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is not selected for the document model in the <STRONG>Document model</STRONG> form.</P>

    
    4.  In the **Date** field, enter the document date of the fiscal document.
    
    5.  In the **Direction** field, select one of the following options to indicate whether the fiscal document is related to incoming or outgoing products or services:
        
          - **Incoming**
        
          - **Outgoing**
    
    6.  In the **Issuer** field, select whether the fiscal document was issued by the **Fiscal establishment** or by a **Third party**.
    
    7.  In the **Account type** field, select **Customer**, **Vendor**, or **Fiscal establishment** as the account type.
    
    8.  In the **Account** field, select the customer account, vendor account, or fiscal establishment that generated the fiscal document.

6.  To reference an existing fiscal document that is issued or received by the same fiscal establishment that issues or receives the fiscal document that is about to be posted:
    
    1.  Click **Fiscal document** to open the **Choose fiscal reference based fiscal documents** form.
    
    2.  On the **Customer** tab, select the customer fiscal document to reference.
        
        –or–
        
        Click the **Vendor** tab, and then select the vendor fiscal document to reference.
        
        –or–
        
        Click the **Fiscal establishment** tab, and then select the transfer fiscal document to reference.
    
    3.  Close the form.

7.  In the **Text ID** field, select the fiscal document source text for the referenced fiscal document.

8.  Close the form.

9.  In the **Vendor invoice** form, on the **Action Pane**, on the **Vendor invoice** tab, click **Post** \> **Post** to post the invoice.

## See also

[(BRA) Fiscal reference (form)](https://technet.microsoft.com/en-us/library/jj710558\(v=ax.60\))

[(BRA) Choose fiscal reference based fiscal documents (form)](https://technet.microsoft.com/en-us/library/jj710587\(v=ax.60\))

[(BRA) Sales posting (modified form)](https://technet.microsoft.com/en-us/library/jj853383\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

