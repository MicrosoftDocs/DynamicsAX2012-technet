---
title: (BRA) Post a sales delivery slip
TOCTitle: (BRA) Post a sales delivery slip
ms:assetid: b717f74d-6cf3-4da3-8ef5-9cfd82eeec5a
ms:mtpsurl: https://technet.microsoft.com/library/JJ863735(v=AX.60)
ms:contentKeyID: 50396418
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Post a sales delivery slip 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post a delivery slip for a sales order that has multiple sales order lines with a delivery Código Fiscal de Operações e Prestações (CFOP) code. For each sales order line, you must specify the CFOP code that has a delivery CFOP code assigned to it. A delivery slip is used when you deliver items to a customer who is different than the one invoiced. That is, when customer and invoice accounts are different. Delivery slips are posted in chronological order. You must attach fiscal references to delivery slips before you post them. Use the **Posting delivery slip** form to post and print delivery slips.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Item tasks** \> **Project sales orders**.

2.  Double-click a sales order, or create a sales order. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

3.  On the **Action pane**, click the **Pick and pack** tab, and then click **Delivery slip**.
    

    > [!NOTE]
    > <P>This button is available only if a delivery Código Fiscal de Operações e Prestações (CFOP) code is assigned to each CFOP code that is specified for every sales order line of the sales order.</P>



4.  In the **Posting delivery slip** form, select the **Posting** and **Print delivery slip** check boxes to post and print delivery slips.

5.  In the lower pane, click the **Setup** tab, and then click **Fiscal reference** to open the **Fiscal reference** form.

6.  To reference a fiscal document that is not available in Microsoft Dynamics AX:
    
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

7.  To select an existing fiscal document that is issued or received by the same fiscal establishment that issues or receives the fiscal document that is about to be posted:
    
    1.  Click **Fiscal document** to open the **Choose fiscal reference based fiscal documents** form.
    
    2.  On the **Customer** tab, select the customer fiscal document to reference.
        
        –or–
        
        Click the **Vendor** tab, and then select the vendor fiscal document to reference.
        
        –or–
        
        Click the **Fiscal establishment** tab, and then select the transfer fiscal document to reference.
    
    3.  Close the form.

8.  In the **Text ID** field, select the fiscal document source text for the referenced fiscal document.

9.  Close the form.

10. In the **Posting delivery slip** form, click **OK** to post the delivery slips.

## See also

[(BRA) Sales posting (modified form)](https://technet.microsoft.com/library/jj853383\(v=ax.60\))

[(BRA) Fiscal reference (form)](https://technet.microsoft.com/library/jj710558\(v=ax.60\))

  


