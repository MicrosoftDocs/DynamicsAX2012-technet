---
title: (LTU) Set up additional validation and compression for Intrastat lines
TOCTitle: (LTU) Set up additional validation and compression for Intrastat lines
ms:assetid: 4c8f2305-4185-47eb-93eb-87ddbb4ceaab
ms:mtpsurl: https://technet.microsoft.com/library/JJ665072(v=AX.60)
ms:contentKeyID: 49386655
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Set up additional validation and compression for Intrastat lines 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Under Lithuanian tax law, companies must declare Intrastat transactions with other members of the European Union to the tax authorities. The Intrastat report must include the details concerning the Intrastat agent and the statistical value for the Intrastat transaction. When reporting triangular transactions between an EU and a non-EU country/region in which the consignment is loaded in another EU country/region, you must specify the loading country, the region, and the state in the report.

You can export Intrastat reports in XML format. You can also validate and compress Intrastat order lines by loading countries, regions, states, and other specific items into the Intrastat table.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  In the **Credit note** field, select the transaction code for the credit note lines in a sales and purchase order.

3.  In the **Check setup** field group, select the required check boxes.

4.  Click **Compress** to open the **Compression of Intrastat** form.

5.  In the **Available** field, select the options for **Commodity**, **Transaction code**, **Country/region of origin**, **Direction**, **Transport**, and **Delivery terms**. Click **\<** to add each option to the **Selected** field. The Intrastat order lines with similar data are compressed into one line.

6.  Click the **Number sequences** tab.

7.  In the **Number sequence code** field, select the number sequence code for the **Reference** type **Intrastat**.

8.  Press CTRL+S or close the form.

## See also

[(LTU) Foreign trade parameters (modified form)](https://technet.microsoft.com/library/jj678085\(v=ax.60\))

  


