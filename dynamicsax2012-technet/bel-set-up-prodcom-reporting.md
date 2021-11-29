---
title: (BEL) Set up PRODCOM reporting
TOCTitle: (BEL) Set up PRODCOM reporting
ms:assetid: c2899c84-a44a-487c-844f-fb7bf1348943
ms:mtpsurl: https://technet.microsoft.com/library/Gg213635(v=AX.60)
ms:contentKeyID: 36059281
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Belgium
---

# (BEL) Set up PRODCOM reporting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Manufacturers of industrial products are required to report the quantities and values of products sold, as well as employment data, to the Nationaal Instituut voor de Statistiek (NIS) in response to the routine PRODCOM survey. Most producers submit an itemized PRODCOM report to the NIS monthly, using one of six standard report formats. The NIS stipulates the report layout, depending on the nature of the materials produced.

Use this procedure to set up the parameters for PRODCOM reporting.

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **PRODCOM** \> **PRODCOM parameters**.

2.  Click the **General** tab.

3.  In the **Primary contact ID** field, enter the primary contact identification. The identification is printed under the primary contact information section of the PRODCOM declaration.

4.  In the **External contact ID** field, enter the identification of the external contact if the company is represented by a third party. The identification is printed under the external contact information section of the PRODCOM declaration.

5.  In the **Branch number** field, select **Company** or **Warehouse**, depending on the location of your company’s production unit.
    
      - If the local branch is **Company**, the branch number of the company is transferred to the PRODCOM lines.
    
      - If the local branch is **Warehouse**, the branch number of the warehouse where the sale took place is transferred to the PRODCOM lines.
    
      - If the warehouse does not have a branch number, the branch number of the company is used.

6.  Select the **Automatic recalculation** check box to recalculate values automatically after changes.

7.  On the **Number sequences** tab, enter the number sequence code for the period.

8.  Close the form to save your changes.

## See also

[(BEL) Use PRODCOM](bel-use-prodcom.md)

[(BEL) Assign PRODCOM properties to an item](bel-assign-prodcom-properties-to-an-item.md)

[(BEL) Convert Intrastat to PRODCOM](bel-convert-intrastat-to-prodcom.md)

  


