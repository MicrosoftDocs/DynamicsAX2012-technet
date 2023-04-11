---
title: Import demo data for AX 2012 R3 by using the Test Data Transfer Tool
TOCTitle: Import demo data for AX 2012 R3 by using the Test Data Transfer Tool
ms:assetid: 
ms:mtpsurl: 
ms:contentKeyID: 
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---


# Import demo data for AX 2012 R3 by using the Test Data Transfer Tool


[!INCLUDE[archive-banner](includes/archive-banner.md)]

In this walkthrough, you will use the Test Data Transfer Tool (beta) to import the demo data for Microsoft Dynamics AX 2012 R3.

We strongly recommend that you work locally on the database server where the business database for AX 2012 R3 is stored. This is both faster, and avoids any network communication issues during import.

## Prerequisites
**Caution:** The Test Data Transfer Tool (beta) is only supported for use in a development, test, or demo environment. Do not perform this procedure in a production environment.

## Download the demo data and Test Data Transfer Tool (beta)
1.  Download the AX 2012 R3 demo data.
2.  Extract the demo data from the package to the database server that hosts the AX 2012 R3 business database for your environment.
3.  Download the Test Data Transfer Tool (beta) tool installer from the Downloadable tools section of [Microsoft Dynamics Lifecycle Services](https://lcs.dynamics.com), and install it on the database server that hosts the AX 2012 R3 business database for your environment.
4.  Verify that you have appropriate permissions to import data. You must have read access to the location where the demo data is stored, and in SQL Server Management Studio, permission to execute **SELECT** statements and **BULK INSERT** statements. For more information, see [Install the Test Data Transfer Tool (beta)](install-test-data-transfer-tool-beta.md).

## Run the Test Data Transfer Tool (beta)
1.  Go to **Control Panel** &gt; **Services**, and stop the AOS instance associated with your environment.
2.  Using Windows Explorer, browse to the **Test Data Transfer Tool (beta)**.
3.  On the **File** menu in Windows Explorer, click **Open command prompt as administrator**.
4.  At the command prompt, enter the following command to import the demo data: **dp.exe import** \location\_of\_demo\_data \Name\_of\_AX\_business\_database \ServernameInstanceName. 

    We assume that you are running the Test Data Transfer Tool (beta) on the local computer. If you have a named instance on the local computer, you can use the syntax localhostInstanceName or **.** InstanceName. In the following example, the data is on the E drive, in the demodata folder, and the business database is named MicrosoftDynamicsAX: **dp.exe import e:demodata MicrosoftDynamicsAX** 

    > [!NOTE]
    > It may take over 30 minutes to import the demo data. If you encounter any issues during the import, you can open the log file **DPLog.xml**, which will be created in the folder where you ran the Test Data Transfer Tool (beta).
5.  Go to **Control Panel** &gt; **Services**, and restart the AOS instance associated with your environment.


