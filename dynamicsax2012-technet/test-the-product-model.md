---
title: Test the product model
TOCTitle: Test the product model
ms:assetid: ebea7c4b-7cf8-4daa-9519-51a758e94dd0
ms:mtpsurl: https://technet.microsoft.com/library/Aa551514(v=AX.60)
ms:contentKeyID: 36059890
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Test the product model 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When the modeling tree is completed and the product model contains all the features that you want, it is time to test how it configures items. This testing phase is very important. You might have to go back to your model design several times to fix errors or add features before you are satisfied with the way in which the product model configures items. Remember that when the product model is released for general use, any errors that it might still contain are likely to cause both wrongly configured items and unhappy users or customers.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Compile the product model.
    

    > [!NOTE]
    > <P>See <A href="compile-the-product-model.md">Compile the product model</A> for the description of this procedure.</P>

    
    This is the first test. Any node in the modeling tree that produces compilation errors will be marked with a red dot. You will then have to find the cause of each error and correct it. When the product model can be compiled without errors, you are ready to test how it works.

2.  Approve the product model by clicking **Approve** in the **Product model details** form.
    
    You must make the product model active for an appropriate modeling-enabled item from the **Released product details** form. You can do this from the lower pane of the **Product model details** form. Select the item that you want to use for the test phase. Preferably, select a designated test item. Then and select a date interval.
    

    > [!NOTE]
    > <P>Select no dates if you want to make the product model active for this item on all dates.</P>

    
    Approve the version by clicking **Approve** in the lower pane of the **Product model details** form, and make it active by selecting the **Active** check box in the lower pane.

3.  Create a sales order, purchase order, production order, sales quotation, project quotation, or item requirement for the item that you just made configurable with your new product model. By doing this, you can configure it in different ways. For more information about item configuring, see [About configuring items](about-configuring-items.md).

4.  Verify that the bills of materials (BOMs) and routes that are created by the product model are correct and contain all required information.

  


