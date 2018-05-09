---
title: (RUS) Set up tax correspondence with budget revenue codes
TOCTitle: (RUS) Set up tax correspondence with budget revenue codes
ms:assetid: fc9e3db0-a467-42b1-a593-8c633aad9ccb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678661(v=AX.60)
ms:contentKeyID: 49388143
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up tax correspondence with budget revenue codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets (Russia)** \> **Setup** \> **Tax reporting** \> **Sales tax relations**.

2.  Press CTRL+N to create a new line.

3.  In the **Type of tax** field, select the type of tax for the fixed asset for which the correspondence must be set up.

4.  In the **Code** field, select the sales tax code for the fixed asset for which the correspondence must be set up.

5.  In the **Budget revenue code** field, select the budget revenue code that corresponds to the selected tax code. Verify that the budget revenue code belongs to the Single System of Gas Supply (SSGS).
    

    > [!NOTE]
    > <P>For more information, see <A href="rus-set-up-budget-revenue-codes-for-fixed-asset-taxes.md">(RUS) Set up budget revenue codes for fixed asset taxes</A>.</P>



6.  Click the **General** tab, and, in the **Benefit by reduction of rate** field, select the tax rate reduction benefit code. The **Privilege value** field displays the benefit amount specified in the **Assessed tax** form.
    

    > [!NOTE]
    > <P>For more information, see <A href="rus-set-up-tax-benefit-codes.md">(RUS) Set up tax benefit codes</A>.</P>



7.  In the **Benefit by reduction of tax** field, select the tax amount reduction benefit code, if necessary. The **Privilege value** field displays the benefit amount specified in the **Assessed tax** form.
    

    > [!NOTE]
    > <P>Although you can map only one tax code with one budget revenue code, a budget revenue code can correspond to several tax codes.</P>



8.  Press CTRL+S or close the form.

## See also

[(RUS) Sales tax relations (form)](https://technet.microsoft.com/en-us/library/jj856164\(v=ax.60\))

[(RUS) Assessed tax (form)](https://technet.microsoft.com/en-us/library/jj856180\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

