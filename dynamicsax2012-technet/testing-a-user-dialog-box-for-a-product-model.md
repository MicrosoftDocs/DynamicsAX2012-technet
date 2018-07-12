---
title: Testing a user dialog box for a product model
TOCTitle: Testing a user dialog box for a product model
ms:assetid: e18e1fc1-6acc-4f23-91d5-d451f192ef44
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551347(v=AX.60)
ms:contentKeyID: 36059709
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Testing a user dialog box for a product model 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The way that the **Product Builder configuration** form functions depends on the setup of the modeling variables, variable groups, validation rules, user profiles, and default values for the model. Together, these structures define the appearance and behavior of the user dialog box with its tabs, sections, and fields.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



Click **Product information management** \> **Common** \> **Released products**. Select a product. On the Action Pane, click **Engineer** tab \> **Configuration** group \> **Maintain configurations** \> **Configure**.

Until nodes are added to the modeling tree, the product model cannot be used to configure items. This is because the modeling tree, which determines the configuration process, is missing. However, you can test the design of the user dialog box by creating an order, item requirement, or quotation, and then configuring it (as a test) in the **Production**, **Accounts receivable**, **Procurement and sourcing**, **Create or maintain projects**, or **Enterprise Portal** section. You can then verify that the user dialog box for the product model works as expected.

To test the **Product Builder configuration** form, click **Functions** \> **Test model** in the **Product model details** form, or click **Test model** in the **Product model** form. In both cases, the user dialog box for the product model will be displayed.

  


