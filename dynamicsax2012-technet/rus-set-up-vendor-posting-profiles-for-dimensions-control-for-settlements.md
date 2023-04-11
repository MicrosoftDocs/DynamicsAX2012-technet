---
title: (RUS) Set up vendor posting profiles for dimensions control for settlements
TOCTitle: (RUS) Set up vendor posting profiles for dimensions control for settlements
ms:assetid: 5700540f-f6cc-4cce-b8ab-ff55de75cb42
ms:mtpsurl: https://technet.microsoft.com/library/JJ665395(v=AX.60)
ms:contentKeyID: 49387483
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Set up
- vendor posting profiles
- (RUS)
- dimensions control for settlements
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up vendor posting profiles for dimensions control for settlements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up vendor posting profiles for dimension control for settlements by using the **Vendor posting profiles** form. For required groups or for a vendor, you must specify a dimension set for dimension control. You must also allow empty values at settlement control for the posting profile.

1.  Click **Accounts payable** \> **Setup** \> **Vendor posting profiles**.

2.  Press CTRL+N to create a new vendor posting profile, and then enter the required details. For more information, see [Vendor posting profiles (form)](https://technet.microsoft.com/library/aa551972\(v=ax.60\)).

3.  Click the **Table restrictions** FastTab.

4.  In the **Allow empty dimension value** field, select the condition under which settlements can be processed if dimension values are not specified. The following options are available:
    
      - **No** – Do not allow transaction settlement, whether the dimension values are specified or not.
    
      - **Auto** – Allow automatic transaction settlement, whether the dimension values are specified or not.
    
      - **Manual** – Allow manual transaction settlement, whether the dimension values are specified or not.
    
      - **Always** – Allow transaction settlement, whether the dimension values are specified or not.
    

    > [!NOTE]
    > <P>This parameter lets you ignore the setting of dimensions when individual transactions are created.</P>



5.  Click the **Setup** FastTab.

6.  In the **Set** field, select the dimension set for settlement control. The specified dimension set indicates that dimension control is activated.

## See also

[(RUS) Set up a dimension set for dimensions control for settlements](rus-set-up-a-dimension-set-for-dimensions-control-for-settlements.md)

  


