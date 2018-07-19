---
title: (IND) Enter VAT in purchase orders
TOCTitle: (IND) Enter VAT in purchase orders
ms:assetid: d837e97f-3dfe-406c-b48a-d896720d804d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710874(v=AX.60)
ms:contentKeyID: 49386287
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Enter VAT in purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action pane**, click **New** \> **Purchase order**, or double-click a purchase order.

2.  Enter the required details. For more information, see [Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\)).
    

    > [!NOTE]
    > <P>You can view the default sales tax group set up for the vendor in the <STRONG>Sales tax group</STRONG> field in the <STRONG>Setup</STRONG> FastTab.</P>



3.  Click **Line view**.

4.  Click the **Line details** FastTab, and then click the **Tax information** tab.

5.  Select the Tax identification number (TIN) in the **Tax Identification Number (TIN)** field.

6.  Select the category of goods for the transactions in the **VAT goods type** field from the following options:
    
      - **Input** – The goods are input goods. The calculated VAT amount is debited to the VAT recoverable account.
    
      - **Capital goods** – The goods are capital goods. The calculated VAT amount is debited to the VAT deferred account.

7.  Enter the percentage usage of the purchased goods that is used for the production or manufacturing of nontaxable goods in the **Non recoverable pct.** field.
    

    > [!NOTE]
    > <P>The percentage of the tax amount defined in the <STRONG>Non recoverable pct.</STRONG> field is posted to the ledger account (debit type) or loaded on inventory. The remaining amount is posted to the recoverable account or the deferred account for the specified TIN, based on the VAT goods type selected.</P>



8.  Post the purchase order.
    

    > [!NOTE]
    > <P>The VAT amount is calculated and posted to the VAT recoverable account when the VAT goods type is <STRONG>Input</STRONG> in step 7. However, if the transaction is for capital goods, the VAT amount is calculated and posted to the VAT-deferred account, and the VAT deferment installments are created, based on the deferment schedule set up for the TIN.</P>



## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

  


