---
title: Update country/region codes
TOCTitle: Update country/region codes
ms:assetid: 368ea61f-7bab-4911-b0c9-71f3868b94ea
ms:mtpsurl: https://technet.microsoft.com/library/Gg731776(v=AX.60)
ms:contentKeyID: 35132603
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Update country/region codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A list of default country/region codes is delivered in Microsoft Dynamics AX 2012. This list also includes 18 default address formats and component information for the countries/regions, such as state/province, county, city, district, and ZIP/postal code.

If you want to change the default address format that is assigned to a country/region code, you can select another address format in the **Address format** column. For example, the country/region for Antarctica has a default address format of 0001. This means that the address components are displayed in the following way:

  - Street name

  - City\_State\_ZIP/postal code

  - Country/region

You might select to change the default address format to 0013. After you make the change, the address components are displayed in the following way:

  - Street name

  - City, ZIP/postal code

  - Country/region

Use this form to view default country/region codes and the corresponding address formats. You can also add new country/region codes and select corresponding address formats for them. The country/region codes and address formats will be used for address records in Microsoft Dynamics AX 2012.


> [!NOTE]
> <P>In the <STRONG>Map country/region codes</STRONG> form, you will map the countries/regions from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 to the countries/regions that are displayed in the form. You cannot map more than one country/region code from the same company to a country/region code listed in the <STRONG>Country/region codes</STRONG> form. You must manually create a unique country/region code for all countries/regions in the same company before the upgrade.</P>



1.  In the **Preprocessing upgrade checklist**, click **Update country/region codes** to open the **Country/region codes** form.

2.  Review the list and verify the short name, long name, and address format for the countries/regions.
    
      - You can modify the short name and long name by editing the field. The countries/regions that you add to this list will appear in Microsoft Dynamics AX 2012 in the user language. Any other translations must be entered manually in Microsoft Dynamics AX 2012 after upgrade is completed.
    
      - You can select a different address format in the **Address format** field. This list includes default address formats and any address formats from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009.

3.  To add a country/region code that was used in Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 but does not appear in the list, press CTRL+N and do the following:
    
    1.  In the **Country/region code** field, enter the country/region code that you want to add.
    
    2.  Enter the short name and long name for the country/region, and then in the **Address format** field, select the address format that corresponds to the selected country/region.

4.  Click **Set to ready for upgrade**.

  


