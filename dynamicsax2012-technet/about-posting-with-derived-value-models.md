---
title: About posting with derived value models
TOCTitle: About posting with derived value models
ms:assetid: b779e5cd-9d80-4452-ad6f-c3928c3340e9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa572244(v=AX.60)
ms:contentKeyID: 36059104
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About posting with derived value models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This information describes how to use derived value models.

  - When you post transactions for a value model that contains derived value models, the derived value model transactions are posted automatically in journals, purchase orders, or free text invoices. However, if you prepare the primary value model transactions in the **Fixed assets** journal, you can view and modify the amounts of the derived transactions before you post them.

  - Certain accounts, such as sales tax and customer or vendor accounts, are updated only once by postings of the primary value model. The derived value model transactions are posted to the accounts that have been defined for the derived value model in the **Fixed asset posting profiles** form.

  - **Acquisition** is often used as the transaction type for the derived value models. You use this when the value model and the derived value model should be applied to the fixed asset from the time of the acquisition of the fixed asset.

  - Other values for the transaction type can also apply. For example, if the primary value model and the derived value models have the same intervals regarding sale or disposal, all fixed asset transaction types are available for the setup of a derived value model.


> [!WARNING]
> <P>Depreciation posted in the derived value model will be the same amount as was posted for the primary value model. If the depreciation methods are different between the value models, you should not generate depreciation transactions using the derived process.</P>



**Example**

The following information describes how to set up acquisition transactions with the derived value model functionality.

1.  Create the value models in the **Value models** form.
    
      - The value model for accounting: VM 1, **Current** posting layer
    
      - The value model for tax purposes: VM 2, **Tax** posting layer

2.  On VM 1, click the **Derived value models** tab. Select VM 2 in the **Value model** field, and **Acquisition** in the **Transaction type** field.

The value models then can be attached to specific fixed assets.

When an acquisition is posted for a fixed asset with value model VM 1, the acquisition is posted not only on VM 1, but also on the derived value model VM 2. The status of both fixed asset value models is updated to **Open**.


> [!NOTE]
> <P>If you do not use derived value models, you must post the acquisition of the fixed asset both for value model VM 1 and value model VM 2.</P>



## See also

[About derived value models](about-derived-value-models.md)

[Set up value models](set-up-value-models.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

