---
title: Perform an export or import consolidation
TOCTitle: Perform an export or import consolidation
ms:assetid: 20fa98c9-4c38-4352-b25b-3afde679d7bb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496786(v=AX.60)
ms:contentKeyID: 37822140
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Perform an export or import consolidation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In an export or import consolidation, the subsidiary legal entities are in different databases than the consolidated legal entity. The subsidiary data is exported to files that are created automatically. Those files are then imported into the database of the consolidated legal entity.

## Export subsidiary data to a file

Use the **Consolidate** \[**Export to**\] form to prepare the export of subsidiary data to files that can be imported into the consolidated legal entity.

1.  Prepare the subsidiary accounts for consolidation. For more information, see [Set up a subsidiary legal entity for consolidation](set-up-a-subsidiary-legal-entity-for-consolidation.md).

2.  Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Export to\]**.

3.  On the **Criteria** tab, specify the details of the consolidation.
    

    > [!NOTE]
    > <P>If the same criteria apply to several subsidiaries that are in the same database, you can transfer data from those subsidiaries to separate export files by using a single operation.</P>



4.  On the **Financial dimensions** tab, specify the financial dimension information that is transferred from the transactions in the subsidiary accounts to the transactions in the consolidated legal entity.

5.  On the **Legal entities** tab, create a line for each subsidiary legal entity whose accounts will be exported to files. These files will be imported into the consolidated legal entity later.

6.  For each subsidiary, enter the subsidiary name and the name of the export file that will be created during the export job.

7.  Click **Batch** to set up the consolidation to run as a batch job at a specific time, or click **OK** to run the consolidation immediately.

8.  When the export is completed, a message displays the number of records that were saved in each file. You can then import the files into the consolidated legal entity.

## Import subsidiary data from files

Use the **Consolidate** \[**Import**\] form to prepare the transfer of subsidiary data from the export files to the consolidated legal entity.

1.  Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Import from\]**.

2.  On the **Criteria** tab, specify the details of the data import.
    

    > [!NOTE]
    > <P>If the same criteria apply to several subsidiaries, you can transfer data from those subsidiaries to the consolidated legal entity by using a single operation.</P>



3.  On the **Legal entities** tab, create a line for each subsidiary legal entity whose data will be imported into the consolidated legal entity. Specify the following information for each subsidiary:
    
      - If the consolidated legal entity owns part of a subsidiary, specify the share of the subsidiary accounts that is imported.
    
      - In the **Account type of conversion differences** field, specify whether exchange differences that are the result of the consolidation process are posted to a balance account or a profit and loss account in the consolidated legal entity.

4.  Click **Batch** to set up the consolidation to run as a batch job at a specific time, or click **OK** to run the consolidation immediately.
    
    The transactions and balances that were specified for consolidation in the subsidiaries are added to the appropriate accounts in the consolidated legal entity.

  


