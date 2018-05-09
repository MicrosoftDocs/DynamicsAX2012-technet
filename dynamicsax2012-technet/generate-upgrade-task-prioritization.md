---
title: Generate upgrade task prioritization
TOCTitle: Generate upgrade task prioritization
ms:assetid: 5e9bb5bd-cb79-4891-a6d2-e2a308b679b9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731812(v=AX.60)
ms:contentKeyID: 35132659
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- top
- priority
- weight
---

# Generate upgrade task prioritization 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Data upgrade checklist** item **Generate upgrade task prioritization** to plan the sequence of bulk copy and post-synchronization script operations during data upgrade. Data upgrade takes place while both the source system and the target system are in single-user mode. Consequently, business operations on Microsoft Dynamics AX are suspended during this time. Bulk copy and script operations, which run concurrently to minimize system downtime, must be prioritized to make the most efficient use of available processing capacity. Microsoft Dynamics AX uses a weighting algorithm to create a default prioritization, though you can use the **Prioritized upgrade scripts** form to override default priorities as needed to increase efficiency.

## Determining task priorities

To preserve data integrity, upgrade tasks must be run in a certain sequence. Upgrade scripts cannot be run until their associated tables have been copied to the Microsoft Dynamics AX target system, and large tables with millions of records take longer than other tables to copy and process. Additionally, dependencies among scripts can result in delays as one script waits for another to finish. The **Prioritized upgrade scripts** form analyzes all of the upgrade tasks and calculates a prioritization resulting in the least downtime. The prioritization algorithm achieves this by assigning a weight to each task. The weight of a table is based on its physical size and on the number of records. The weight of a script derives from the weight of the tables it updates and on the cumulative weights of all its dependent scripts. In either case, the highest weight results in the highest priority, since heavily weighted jobs are likely to block other jobs until they finish running.

Weight-ranked results are displayed in grids on the **Top tables and scripts** tab. The **Top tables and scripts** field contains an integer value that specifies the number of tables and scripts that will be processed concurrently during data upgrade. For example, a value of 20 means that a block of 20 tables and a block of 20 scripts will be run concurrently before proceeding to the next block of 20 and 20. You may achieve efficiency gains by overriding the default value of the **Top tables and scripts** field. This field also determines the number of top tables and top scripts displayed in their respective grids.

In most cases, the ranking algorithm will produce the best prioritization. However, you can override the algorithm by manually assigning higher or lower weights to tables or scripts and then regenerating the prioritization. Custom priorities are useful when you have knowledge of the actual loads that your system will encounter while upgrading certain tables.


> [!IMPORTANT]
> <P>When you are regenerating the prioritization after assigning custom weights, select “No” if a dialog asks to overwrite your customization.</P>



## Adding new tasks

The **Prioritized upgrade scripts** form allows to you to add tables or scripts to the grids manually. To insert an additional table or script, press Ctrl+F3 to create a new row, and then fill in the table or script information. This method can also be used to override the calculated weight of an existing table or script that is not displayed in its grid:

1.  Press Ctrl+F3 to create a new row.

2.  Enter the name of the table or script whose weight you wish to change.

3.  Enter a custom weight.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

