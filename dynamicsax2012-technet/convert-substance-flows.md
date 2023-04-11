---
title: Convert substance flows
TOCTitle: Convert substance flows
ms:assetid: 48164c81-a67c-4c59-bdcc-c55c62de1f82
ms:mtpsurl: https://technet.microsoft.com/library/Hh433537(v=AX.60)
ms:contentKeyID: 36941327
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Convert substance flows 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you define the settings for tracking transactions that affect the environment, use the **Calculate conversions** form to convert incoming substance flows to outgoing substances. Incoming flows can result from information entered on invoices that were created in the **Invoice register** form or the **Purchase order** form, from meter readings, or from manual entries. After you select the criteria for the flows, you can schedule the conversion calculation to run regularly as a batch job.

1.  Click **Compliance and internal controls** \> **Periodic** \> **Environmental sustainability** \> **Calculate conversions**.

2.  To limit the conversion calculation to a selected period, on the **General** tab, enter dates in the **Start date** field and **End date** field. The default date range allows for conversion of all unconverted substances.

3.  On the **General** tab, select the check boxes for the types of transactions that you want to include in the conversion.

4.  Click **Select** to constrain the number of substance flows to calculate.

5.  On the **Batch** tab, make the appropriate selections, select the **Batch processing** check box, and then click **OK**.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Batch processing</STRONG> check box and click <STRONG>OK</STRONG> before setting up the batch job, the conversion task runs immediately.</P>



## See also

[Calculate conversions (form)](https://technet.microsoft.com/library/hh227467\(v=ax.60\))

[Set up substance conversions](set-up-substance-conversions.md)

  


