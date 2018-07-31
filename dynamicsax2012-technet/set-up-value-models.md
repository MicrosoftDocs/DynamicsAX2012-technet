---
title: Set up value models
TOCTitle: Set up value models
ms:assetid: 436a5ae0-c108-4f9b-b5df-c144608bbc1e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496964(v=AX.60)
ms:contentKeyID: 36676384
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up value models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Value models track the financial value of a fixed asset over time for various purposes, such as accounting depreciation, tax depreciation, revaluation, and disposal. Each value model represents an independent financial life cycle, and each fixed asset can have several value models assigned to it.

Before you set up value models, you must set up depreciation profiles to assign to the value model. You must also set up a fiscal calendar to assign to the value model.

1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  Enter a unique identifier in the **Value model** field, and enter a short description of the value model in the **Description** field.

3.  If the value model is used for depreciation of the fixed asset, enter values in the **Depreciation** field group.

4.  Select the posting layer. The default value is **Current**, but you can also select **Operations** or **Tax**.

5.  Select additional options, as applicable. For more information, see [Posting layer](https://technet.microsoft.com/en-us/library/aa575927\(v=ax.60\)).

6.  You can attach other existing value models to use at the same time as the new value model. On the **Derived value models** FastTab, create a line for each value model, select the value model, and then specify the transaction type.

7.  You can attach existing depreciation books that will be used at the same time as the new value model. On the **Derived depreciation books** FastTab, create a line for each depreciation book, select the depreciation book, and then specify the transaction type.

8.  To attach the new value model to one or more fixed asset groups, click **Fixed asset groups**. For more information, see [Fixed asset group/value model (form)](https://technet.microsoft.com/en-us/library/aa554698\(v=ax.60\)).

## See also

[Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md)

[About derived value models](about-derived-value-models.md)

[About posting with derived value models](about-posting-with-derived-value-models.md)

[Set up depreciation profiles](set-up-depreciation-profiles.md)

  


