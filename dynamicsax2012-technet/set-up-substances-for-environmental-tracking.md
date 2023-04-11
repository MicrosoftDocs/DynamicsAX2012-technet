---
title: Set up substances for environmental tracking
TOCTitle: Set up substances for environmental tracking
ms:assetid: 848fcd7f-3a20-4c53-bd99-95a07841ad7f
ms:mtpsurl: https://technet.microsoft.com/library/Hh209320(v=AX.60)
ms:contentKeyID: 36058392
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up substances for environmental tracking 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A substance is any material or type of energy that enters, moves through, or leaves your organization. You can define the substances that you want to track. For example, you can track electricity that is purchased from a utility company, gasses that are emitted into the air from burning fuel, or manufacturing waste that is generated during the manufacturing process. You can also define and track substances such as delivery trucks and container mileage. For example, if you are tracking a delivery truck, in addition to tracking the gasoline that is used, you can also track oil and anti-freeze consumption. All of these components are included in the carbon footprint of your organization.

## Set up a substance

1.  Click **Compliance and internal controls** \> **Setup** \> **Environmental sustainability** \> **Substances**.

2.  Click **New**.

3.  Enter the name and a brief description of the substance.

4.  Select a category and unit of measure for the substance. Use the **Units** form to define units of measure.
    

    > [!IMPORTANT]
    > <P>You cannot modify the unit for a substance after you save the record.</P>



5.  Select the color that you want to use to represent the substance in the process map.

6.  Enter the substance mass and volume per unit.
    
    The unit of measure is a standard base or derived division of quantity that is used for measurement or exchange. System units are used for measurement or exchange. For example, if the substance is water, the unit of measure is gallons. The system units for mass and volume are measured in kilograms and liters, respectively. The values that you enter are:
    
      - **Mass (%1) per unit** = 3.6 kilograms
    
      - **Volume (%1) per unit** = 3.79 liters
    
    Setting these values correctly ensure that your reporting is accurate and comparable.

7.  In the **Item number** field, enter information to link the substance to an inventory item. When you enter a linked item in a **Purchase order** form, lines that contain the order quantity are created on the **Environment** tab.

8.  Enter amounts in the **Percent post-consumer** field and the **Percent pre-consumer** field.
    
    Pre-consumer recycled material is material that is recycled from industrial sources, such as scrap on the production line or defective products. Post-consumer recycled material is material that is recycled from used consumer goods, such as water bottles or newspaper.

## Delete a substance

  - Click **Compliance and internal controls** \> **Setup** \> **Environmental sustainability** \> **Substances**.

  - In the **Substances** form, on the **Overview** tab, select a substance, and then click **Delete**.
    

    > [!NOTE]
    > <P>You cannot delete a substance if it has been added to a substance flow.</P>



## See also

[Substances (form)](https://technet.microsoft.com/library/hh227552\(v=ax.60\))

[Set up environmental parameters](set-up-environmental-parameters.md)

[Set up substance categories](set-up-substance-categories.md)

  


