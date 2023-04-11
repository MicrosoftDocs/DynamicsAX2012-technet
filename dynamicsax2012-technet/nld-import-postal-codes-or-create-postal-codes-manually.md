---
title: (NLD) Import postal codes or create postal codes manually
TOCTitle: (NLD) Import postal codes or create postal codes manually
ms:assetid: eebd1bde-b212-4189-a70b-444983b3806f
ms:mtpsurl: https://technet.microsoft.com/library/Hh227503(v=AX.60)
ms:contentKeyID: 36059914
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Netherlands
- postal codes
- zip codes
audience: Application User
ms.search.region: Netherlands
---

# (NLD) Import postal codes or create postal codes manually 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Import ZIP/postal codes** form to import new Dutch postal codes into Microsoft Dynamics AX 2012. The new code format consists of four digits followed by a space and two letters. When you import the codes, the existing zip or postal codes are replaced with the new format, and any new codes are added.

The import process allows you to update the company Global Address Book (GAB) for a specific country or region. You can also create postal codes manually.

## Import ZIP/postal codes

1.  Click **Organization administration** \> **Setup** \> **Addresses** \> **Import ZIP/postal codes**.

2.  In the **Country/region** field, select **Netherlands**.

3.  In the **File name** field, enter the name of the address file or select the address file to be imported. The address file is a TXT file that contains fixed length fields.

4.  Select the **Delete** check box to replace the existing zip or postal codes. If the selected address file is an update to an existing file, the existing zip or postal codes (NNNNAA) are updated with the new zip or postal codes in the new format (NNNN AA). This update is performed whether the **Delete** check box is selected or not. If the selected address file is new, one of the following actions take place:
    
    1.  If the **Delete** check box is selected, all existing Dutch zip or postal codes are deleted and the new codes are added.
    
    2.  If the **Delete** check box is cleared, the existing zip or postal codes are retained and the new zip or postal codes are added, even if the codes are duplicated.

5.  Click **OK** to import the codes.

## Create ZIP/postal codes manually

1.  Click **Organization administration** \> **Setup** \> **Addresses** \> **Address setup**.

2.  On the left pane, select **ZIP/postal codes**.

3.  In the **Country/region** field, select a country or region. All existing addresses for the country/region are shown.

4.  Click **New** to add a new code manually.

5.  In the **ZIP/postal code** field, enter the new postal code (four digits, followed by a space and two letters) in the format NNNN AA.

6.  Enter the address information in the **State**, **County**, **City**, **District**, and **Street** fields.

7.  In the **From** and **To** fields, enter the lowest and highest street numbers that are within the postal code, if applicable.

8.  In the **All/Even/Odd** field, specify whether the new postal code applies to all, even, or odd street numbers.

9.  In the **Time zone** field, select the time zone for the country or region.

10. Close the form to save your changes.

## See also

[Import ZIP/postal codes (form)](https://technet.microsoft.com/library/aa591460\(v=ax.60\))

  


