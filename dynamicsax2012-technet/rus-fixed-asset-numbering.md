---
title: (RUS) Fixed asset numbering
TOCTitle: (RUS) Fixed asset numbering
ms:assetid: 7ed8077d-9de7-48cb-8993-27d727c674c1
ms:mtpsurl: https://technet.microsoft.com/library/JJ678404(v=AX.60)
ms:contentKeyID: 49387634
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Fixed asset numbering 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Select an option for assigning numbers to fixed assets:

  - Manual selection: This is appropriate for a company with few fixed assets. No setup is required for manual selection. You can simply enter the fixed asset number when you create fixed assets in the **Fixed assets** form.
    

    > [!NOTE]
    > <P>For more information, see in the Applications and Business Processes Help.</P>



  - Automatic numbering of all fixed assets from one default number sequence: To use this method, you must set up at least one number series. Specify a default number series when you set up a fixed asset.

  - Automatic numbering of fixed assets based on fixed asset group: This method is appropriate for a company with a large number of fixed assets. You can create many Account/Group numbers for fixed assets, and attach a number series to each group. You must specify a default number series when you set up fixed assets.
    

    > [!NOTE]
    > <P>You can set up numbering for fixed assets only when you set up the journal name for the asset transactions in the <STRONG>Journal names</STRONG> form. For more information, see "Journal names setup (form)" in the Applications and Business Processes Help.</P>



## Automatic numbering of all fixed assets from one default number sequence

1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.

2.  Click **Fixed assets (Russia)** \> **Setup** \> **Parameters**. to open the **Fixed Asset Parameters** form.

3.  On the **Number sequences** tab, select a number sequence code for the FA number reference.

4.  Press CTRL+S or close the form.

When you create a fixed asset in the **Fixed assets** form, the next number in the sequence is automatically entered into the fixed asset number field.


> [!NOTE]
> <P>You can assign special number sequences for selected fixed asset groups while applying the default number sequence to fixed assets that do not have group-specific number sequences.</P>



## Automatic numbering of fixed assets based on fixed asset group

1.  Click **Fixed assets** \> **Setup** \> **FA group table** to open the **FA group table** form.

2.  Select the **Autonumeration FA** check box for the selected FA group, and then select the appropriate number sequence in the **FA autonumber sequence** field.

This number sequence is used for all fixed assets that are assigned to the fixed asset group.


> [!NOTE]
> <P>To create a fixed asset group, press CTRL+N, and then enter the required details.</P>



## See also

[(RUS) Fixed asset parameters (form)](https://technet.microsoft.com/library/jj721462\(v=ax.60\))

[(RUS) Fixed assets (modified form)](https://technet.microsoft.com/library/jj923580\(v=ax.60\))

[(RUS) FA groups (form)](https://technet.microsoft.com/library/jj853159\(v=ax.60\))

  


