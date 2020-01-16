---
title: (RUS) Temporarily inactivate and reactivate a fixed asset
TOCTitle: (RUS) Temporarily inactivate and reactivate a fixed asset
ms:assetid: 4b46c72c-e223-4a38-a6aa-17ddb33ed67c
ms:mtpsurl: https://technet.microsoft.com/library/JJ665354(v=AX.60)
ms:contentKeyID: 49387442
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Temporarily inactivate and reactivate a fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



If a fixed asset is closed down or inactive for more than three months, or if refurbishment of the asset is conducted for more than 12 months, calculation of depreciation is suspended. Depreciation calculation resumes when the fixed asset is placed back into service.

## Inactivate a fixed asset temporarily

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the fixed asset to be temporarily deactivated. The asset is shown in **Exploitation** status.

3.  In the **Status** field, select **Temporary closing-down** to open the **Temporary closing-down** form.

4.  Click **Yes** to confirm the change of status.

5.  In the **Date** field, select the deactivation date.

6.  In the **Reason code** field, select a reason code.

7.  In the **Reason comment** field, enter a description for the transaction.

8.  Click **OK**.
    

    > [!NOTE]
    > <P>The fixed asset status changes to <STRONG>Temporary closing-down</STRONG>.</P>



9.  Click **History** \> **Temporary closing-down** to view the starting date, ending date, and user code in the **Temporary closing-down** form.
    

    > [!NOTE]
    > <P>Depreciation is not accrued when the status of the fixed asset is <STRONG>Temporary closing-down</STRONG>.</P>



## Reactivate a fixed asset

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the fixed asset with the **Temporary closing-down** status.

3.  In the **Status** field, modify the status to **Exploitation** to open the **Temporary closing-down** form.

4.  Click **Yes** to confirm the change of status.

5.  In the **Date** field, select the reactivation date.

6.  In the **Reason code** field, select a reason code.

7.  In the **Reason comment** field, enter a description for the transaction.

8.  Click **OK**.
    

    > [!NOTE]
    > <P>The fixed asset status changes to <STRONG>Exploitation</STRONG>.</P>



9.  Click **History** \> **Temporary closing-down** to view the deactivation ending date in the **Temporary closing-down** form.
    

    > [!NOTE]
    > <P>Depreciation will be calculated from the period specified in the <STRONG>Date of depreciation beginning</STRONG> field in the <STRONG>Depreciation groups</STRONG> form.</P>



## See also

[(RUS) Depreciation groups (form)](https://technet.microsoft.com/library/jj678328\(v=ax.60\))

  


