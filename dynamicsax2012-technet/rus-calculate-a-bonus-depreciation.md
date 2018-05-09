---
title: (RUS) Calculate a bonus depreciation
TOCTitle: (RUS) Calculate a bonus depreciation
ms:assetid: cda89f12-01d8-46d2-9463-6a672cc6327a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923591(v=AX.60)
ms:contentKeyID: 52075436
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Calculate a bonus depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The depreciation bonus is an additional depreciation amount that is assessed during the first year for some asset types that are operational. The depreciation bonus is calculated only for the tax value model for fixed assets. You must set up a posting profile before you can calculate the depreciation bonus for fixed assets.

1.  Click **Fixed assets (Russia)** \> **Periodic** \> **Depreciation bonus initialization**.

2.  In the **Value model** field, select a model for the depreciation bonus.

3.  In the **Depreciation bonus** field, select the bonus ID that you create in the **Depreciation bonus** form.

4.  Click **Select** to open the **Inquiry** form. Then enter the selection criteria for the fixed asset or fixed asset group to create the transaction for.

5.  Click **OK**. The depreciation bonus percentage is updated in the **Depreciation bonus** field in the **FA transactions** form.
    

    > [!NOTE]
    > <P>When you post a depreciation transaction, two transactions are created in the fixed asset (FA) journal to register the depreciation and the depreciation bonus.</P>



## See also

[(RUS) Value models (modified form)](https://technet.microsoft.com/en-us/library/jj923586\(v=ax.60\))

[(RUS) FA value models (form)](https://technet.microsoft.com/en-us/library/jj856113\(v=ax.60\))

[(RUS) FA transactions (form)](https://technet.microsoft.com/en-us/library/jj911230\(v=ax.60\))

[(RUS) Fixed assets (modified form)](https://technet.microsoft.com/en-us/library/jj923580\(v=ax.60\))

[(RUS) Calculate or reverse fixed asset depreciation](rus-calculate-or-reverse-fixed-asset-depreciation.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

