---
title: Generate web forms for customer self-service
TOCTitle: Generate web forms for customer self-service
ms:assetid: 0b402c8a-7b5b-4222-aaa5-92f81b7c4117
ms:mtpsurl: https://technet.microsoft.com/library/Aa569743(v=AX.60)
ms:contentKeyID: 36055987
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Generate web forms for customer self-service 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can use **Customer self-service** with a product model, you must generate the Web forms from the product model.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



Generate two Web forms for each language that is available in **Customer self-service**. By generating two Web forms for each language, you guarantee that the names of modeling variables and other text are correctly translated in the **Product Builder configuration** and **Product Builder approval** Web forms.

1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Select the line for a product model. Then, on the **Develop** tab, click **Generate form**.

3.  Select the language that you want to use in the Web form. You can select any of the language codes that are currently defined for your company.

4.  Click **OK** to generate the **Product Builder configuration** and **Product Builder approval** Web forms.


> [!NOTE]
> <P>If the setup of the product model's modeling variable is changed after you generate the Web forms, you must generate new Web forms. Otherwise, your changes do not take effect.</P>
> <P>Refresh the cached information for the application object every time that you change the setup of the product model's modeling variable.</P>


  


