---
title: 'Key tasks: Set up address formats'
TOCTitle: 'Key tasks: Set up address formats'
ms:assetid: 4dd2cde8-11a8-4607-9054-c9683f00d730
ms:mtpsurl: https://technet.microsoft.com/library/Gg731791(v=AX.60)
ms:contentKeyID: 35132631
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Key tasks: Set up address formats 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Because there are multiple address format types, for example countries and regions and states and provinces, your organization must have the flexibility to adjust to an address format when displaying a postal address. You can use the **Address setup** form to set up all postal address information for your organization. Click **Organization administration** \> **Setup** \> **Addresses** \> **Address setup**.

## What do you want to do?

Set up address formats

Set up country/region information

Set up state/province information

Set up county information

Set up city information

Set up district information

Set up ZIP/postal code information

## Set up address formats

Use this section of the form to enter and set up address component information and formatting. As you enter address information for a selected address type, the **Address** field in the upper-right pane displays how the address will appear.

1.  In the **Address setup** form, select **Address format** in the left pane.

2.  In the upper pane, click **New** to add a new address format type.

3.  Enter the address format type name and a brief description.
    
    For example, you might enter NO in the **Address format** field and enter Norway in the **Description** field.

4.  In the lower pane, click **New** to configure a new address component for the address format type that is selected in the upper pane.

5.  In the **Address application object** field, select the first object that must appear when an address for this format is displayed. For example, **Street** .

6.  In the **Separator** field, enter the character that should separate this object from the next object when the address is displayed. For example, a comma.

7.  Select the check boxes to indicate the following:
    
      - **New line** – Display this object on a new line.
    
      - **Data entry only** – Display this object only when entering the address. If this check box is selected, the object will not be displayed when the address is printed.
    
      - **Not active** – Do not use this object in an address for the selected format type.
    
      - **Expand** – Display the name of the country/region, state, or county instead of the assigned code.
    
      - **Special** – Indicates that the field contains the same separator characters.

Back to top

## Set up country/region information

When you installed or upgraded to Microsoft Dynamics AX 2012, country/region information may have been added to this form. If it was not, or if you have to add a new country/region, follow these steps.

1.  In the **Address setup** form, select **Country/region** in the left pane.

2.  Click **New** to create a new line.

3.  Enter the code for the country/region, a short name, and the full name of the country/region. For example, DEU, Germany, and Federal Republic of Germany.

4.  Select the address format and the time zone for the country/region.

5.  Select the **Use ZIP + 4 postal code validation rules** check box to enable only valid 5-digit or 9-digit ZIP/postal codes.

Back to top

## Set up state/province information

As with country/region information, state/province information may have been added to this form when you upgraded to or implemented Microsoft Dynamics AX 2012. Use this procedure to add a new state/province to a country/region’s information.

1.  In the **Address setup** form, select **State/province** in the left pane.

2.  In the **Country/region** filter, select the country/region that you are adding a state/province for.

3.  Click **New** to create a new line.

4.  Enter the state/province code and the name of the state/province.

5.  Select the time zone for the state/province.

Back to top

## Set up county information

Use the following procedure to add county information to any existing country/regions or states.

1.  In the **Address setup** form, select **County** in the left pane.

2.  In the **Country/region** filter, select the country/region that you are adding county information to.

3.  In the **State or province** filter, select the state where the county is located.

4.  Click **New** to create a new line.

5.  Enter the name and a brief description of the county.

Back to top

## Set up city information

1.  In the **Address setup** form, select **City** in the left pane.

2.  In the **Country/region** filter, select the country/region that you are adding city information to.

3.  Click **New** to create a new line.

4.  Enter the name of the city and a brief description.

5.  Select the state or county where the city is located.

Back to top

## Set up district information

1.  In the **Address setup** form, select **District** in the left pane.

2.  Use the filters to select the **Country/region**, **State or province**, **County**, and **City**, as appropriate, that the district is located in.

3.  Click **New** to create a new line.

4.  Enter the name of the district and a brief description.

Back to top

## Set up ZIP/postal code information

1.  In the **Address setup** form, select **ZIP/postal codes** in the left pane.

2.  Use the filter to select the **Country/region** location for the ZIP/postal code.

3.  Click **New** to create a new line.

4.  Enter the ZIP/postal code and select the corresponding city.

5.  Enter the street name, where the ZIP/postal code is effective.

6.  Enter the lowest and highest street numbers that use the ZIP/postal code, and enter the number types. For example, the ZIP/postal code may apply only to odd numbered street addresses.

7.  Select the **State or province**, **County**, **District**, and **Time zone** for the ZIP/postal code.

Back to top

  


