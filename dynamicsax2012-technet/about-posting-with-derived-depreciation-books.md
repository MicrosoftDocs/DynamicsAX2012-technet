---
title: About posting with derived depreciation books
TOCTitle: About posting with derived depreciation books
ms:assetid: fbac9d71-cea0-471a-8104-0eb09e233b70
ms:mtpsurl: https://technet.microsoft.com/library/Aa499878(v=AX.60)
ms:contentKeyID: 36060080
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About posting with derived depreciation books 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This information describes posting transactions using derived depreciation books.

  - When you post transactions for a value model that contains derived depreciation books, the derived depreciation book transactions are posted automatically from journals, purchase orders, or free text invoices. If you prepare the primary value model transactions in the **Fixed assets** journal, however, you can view and modify the amounts of the derived transactions before you post them.

  - **Acquisition** is often used as the transaction type for the derived depreciation book. You use this when the value model and the derived depreciation book should be applied to the fixed asset from the time of acquisition of the fixed asset.

  - Other values for the transaction type also can apply. For example, if the value model and the derived depreciation book have the same intervals regarding sale or disposal, all fixed asset transaction types are available for the setup of a derived depreciation book.


> [!WARNING]
> <P>Depreciation posted in the derived depreciation book will be the same amount as was posted for the value model. If the depreciation methods are different between the value model and the depreciation book, you should not generate depreciation transactions using the derived process.</P>



**Example**

Refer to the following information to see how to set up acquisition transactions using derived depreciation books.

1.  Create the value model and depreciation book in the **Value models** form.
    
      - The value model for accounting: VM 1, **Current** posting layer
    
      - The depreciation book for tax purposes: VM 2, **Tax** posting layer

2.  For VM 1, click the **Derived value models** tab, and select VM 2 in the **Value model** field, and **Acquisition** in the **Transaction type** field.

The value model and depreciation book then can be attached to specific fixed assets. When an acquisition is posted for a fixed asset with value model VM 1, the acquisition is posted not only on VM 1, but also on the derived depreciation book VM 2.

The fixed asset can then be depreciated in the value model and the depreciation book.


> [!NOTE]
> <P>If you do not use derived depreciation books, you must post the acquisition of the fixed asset for both value model VM 1 and depreciation book VM 2.</P>



## See also

[About derived depreciation books](about-derived-depreciation-books.md)

[Fixed asset posting profiles (form)](https://technet.microsoft.com/library/aa571467\(v=ax.60\))

[Value models setup (form)](https://technet.microsoft.com/library/aa582567\(v=ax.60\))

  


