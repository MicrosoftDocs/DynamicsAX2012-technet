---
title: 'Scenario: Perform in-place upgrade to AX 2012 R3 + CU10'
TOCTitle: 'Scenario: Perform in-place upgrade to AX 2012 R3 + CU10'
ms:assetid: 32c1b95e-5b84-4520-a4d9-68850716b61a
ms:mtpsurl: https://technet.microsoft.com/library/Mt674913(v=AX.60)
ms:contentKeyID: 72156812
author: Khairunj
ms.date: 01/20/2016
mtps_version: v=AX.60
---

# Scenario: Perform in-place upgrade to AX 2012 R3 + CU10 


This topic provides instructions for repairing incorrect model element IDs when upgrading to Microsoft Dynamics AX 2012 R3 + CU10 or later from any previous version of Dynamics AX 2012 R2.

It requires the Model Store Upgrader tool that is available for download in KB 3118784.

1.  Stop the AOS.

2.  Back up your current model store database. (This database will be modified, and if any issues occur, you will need to restore the backup.)

3.  Download the ModelStoreUpgrader tool.

4.  Run the UpdateModelElementOriginIds command:
    
        ModelStoreUpgrader.exe UpdateModelElementOriginIds --InputFilePath=DynamicsAX2012R3OriginIDs.txt --ModelStoreServer=localhost --ModelStoreDatabaseName=MicrosoftDynamicsAX_model

5.  If you have a “DMF Labels” model in the SYP layer, remove it:
    
        AxUtil.exe delete "/model:DMF Labels"

6.  Copy the slipstream version of Dynamics AX 2012 R3 Cumulative Update 10 (CU10) or later into the Dynamics AX 2012 R3 installation media. For more information about slipstreaming, see [Include cumulative updates and hotfixes in a new installation (slipstreaming)](include-cumulative-updates-and-hotfixes-in-a-new-installation-slipstreaming.md).

7.  Run setup.exe and complete the Microsoft Dynamics AX 2012 R3 installation steps.

8.  Run the FixElementIds command:
    
        ModelStoreUpgrader.exe FixElementIds --ModelStoreServer=localhost --BaselineModelStoreDatabaseName=MicrosoftDynamicsAX_UpgradeR3Baseline --ModelStoreDatabaseName=MicrosoftDynamicsAX_model

9.  Compile the application:
    
        AxBuild.exe xppcompileall

10. Proceed with the upgrade process as described in [Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3](scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md), beginning at the section “Back up the test system model store”.

  


