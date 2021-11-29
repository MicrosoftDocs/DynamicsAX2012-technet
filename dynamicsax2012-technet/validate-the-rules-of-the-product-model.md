---
title: Validate the rules of the product model
TOCTitle: Validate the rules of the product model
ms:assetid: 93ff7d80-a5ba-41fb-b165-73224bc3c449
ms:mtpsurl: https://technet.microsoft.com/library/Ff395358(v=AX.60)
ms:contentKeyID: 36058589
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Validate the rules of the product model 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides instructions for using the **Rule debugger** to test the product model. The **Rule debugger** must be enabled to use it. For instructions, see [Enable/disable the rule debugger](enable-disable-the-rule-debugger.md).


> [!NOTE]
> <P>This information applies only to Product builder.</P>



## Validate your rules

1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Click **Product model** to open the **Product models** form.

3.  Select the product model that you want to test, and then click **Functions** \> **Test model** to open the **Product Builder configuration** form.

4.  Test the model by selecting appropriate values for the variables. Whenever a value is added, set, or changed, the **Rule debugger** is triggered.

5.  View a selection in the **Rule debugger**. For each selection that you make in the **Product Builder configuration** form, the **Rule debugger** reflects the result in the background. In this manner, you can validate immediately whether your choices trigger the correct actions.

## Restart rule validation

To retest new rules or variables in the **Product Builder configuration** form, you can restart the rule-validation session for the product model.

  - Click the **Restart** button. All variables are cleared, and the validation restarts.

## See also

[Enable/disable the rule debugger](enable-disable-the-rule-debugger.md)

[About the rule debugger](about-the-rule-debugger.md)

  


