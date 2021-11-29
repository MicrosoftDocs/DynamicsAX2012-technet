---
title: (BRA) Generate the SPED fiscal export file for a month
TOCTitle: (BRA) Generate the SPED fiscal export file for a month
ms:assetid: 1430d618-43e1-46d5-8a90-f7a6716ee425
ms:mtpsurl: https://technet.microsoft.com/library/Dn305862(v=AX.60)
ms:contentKeyID: 54912960
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBBookingPeriodListPage_BR
- MsDynAx060.Forms.FBBookingPeriodListPage_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Generate the SPED fiscal export file for a month 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Sistema Publico de Escrituração Digital (SPED) fiscal text file provides information about fiscal documents that were received and issued during a specific month. This information is used by tax authorities. The SPED fiscal text file also includes information about tax assessments and payments during the month. This topic explains how to generate a SPED fiscal text file by using the **Booking period** list page.


> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3. For information that is specific to Microsoft Dynamics AX 2012 R3, see the section later in this topic.</P>



## Generate the SPED fiscal text file for a month

1.  Click **Fiscal books** \> **Common** \> **Booking period**. On the **Action Pane**, click the **Tax statements** tab.

2.  Select a booking period, and then click **SPED Fiscal**.

3.  Specify the location and name of the file. The default location is specified in the **SPED fiscal parameters** form, and the default file name is automatically generated. In most cases, you should accept the default entry.

4.  Select either **Original** or **Substitute** for the file type.

5.  Select the version. The default entry is specified in the **SPED fiscal parameters** form.

6.  Optional: Click the **Batch** tab and specify options for batch processing. You might use batch processing if the file should be generated later or on a server instead of on your computer.

7.  Click **OK**.

  


