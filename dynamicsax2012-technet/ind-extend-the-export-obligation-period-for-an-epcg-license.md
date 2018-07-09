---
title: (IND) Extend the export obligation period for an EPCG license
TOCTitle: (IND) Extend the export obligation period for an EPCG license
ms:assetid: 28b07b54-32ce-494e-8305-4a4c9654e172
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664575(v=AX.60)
ms:contentKeyID: 49385653
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- EPCG license
- EPCG license extension
- export obligation
- extension of EPCG license
---

# (IND) Extend the export obligation period for an EPCG license [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Each export obligation period for an Export Promotion Capital Goods (EPCG) incentive license is defined as one or more blocks of time. You can extend the blocks of time in the export obligation period.

## Examples

## Extend one block

When you extend a block, and the extended block overlaps a subsequent block, the starting date of the subsequent block is updated to a date that is one day after the ending date of the extended block. The total export obligation period for the selected EPCG scheme is not extended.

For example, you create an EPCG incentive scheme that has two blocks. The total period for the incentive scheme is eight years. The original period for Block 1 is five years, followed by Block 2 for three more years. When you extend Block 1 to six years, Block 2 is changed to two years, and the starting date of Block 2 is the day after the ending date for Block 1. The total period for all blocks is still eight years.

## Extend all blocks

If you extend all blocks, the ending date for all of them is extended by the selected length of time, and the total period for the incentive scheme is also extended. The starting date for the second block and each subsequent block is updated to one day after the ending date of the previous block.

For example, you create an EPCG incentive scheme that has three blocks. The original length of time for each block is 24 months and the total export obligation period is six years. When you extend all blocks by four months, all blocks are changed to 28 months. Block 2 starts on the first day of the twenty-ninth month, and Block 3 starts on the first day of the fifty-seventh month. The total export obligation period for the incentive scheme is extended by one year to seven years in total, calculated as four months per block multiplied by three blocks.

## Extend blocks of time

1.  Click **General ledger** \> **Common** \> **EXIM EPCG Schemes**. In the **EXIM EPCG Schemes** list, open an EPCG incentive scheme.

2.  In the **EXIM EPCG Schemes** form, on the **Overview** FastTab, select an EPCG scheme that has a status of **Approved**.

3.  On the **Lines** FastTab, click **Functions** \> **Extension**.
    

    > [!NOTE]
    > <P>The <STRONG>Extension</STRONG> option is available only if the status of the selected EPCG scheme is <STRONG>Approved</STRONG>.</P>



4.  In the **Block extension** form, select one or more blocks, and then click **Create**.

5.  In the **Create extension** form, in the **Certificate number** field, enter the certificate number of the EPCG license to extend.

6.  In the **Issue date/time** field, enter the date and time when the certificate was issued.

7.  In the **Extension** field, select the basis for extending the block of time:
    
      - **Selected block** – Modify the export obligation period for the selected block.
    
      - **All blocks** - Modify the export obligation period for all blocks in the EPCG scheme.

8.  In the **Period interval** field, select the unit of time to use for calculating the period.

9.  In the **Value** field, enter the number of periods for the export obligation period. For example, if you selected **Years** in the **Period interval** field, and you enter **1** in the **Value** field, you are extending the selected export obligation period by one year.

10. Click **OK** to save your changes and close the form.
    
    The updated export obligation period is displayed in the **Block extension** form.

In the **EXIM EPCG Schemes** form, on the **Lines** FastTab, the license status of the EPCG scheme is now **Extended**.

## See also

[(IND) About EPCG incentive schemes for export orders](ind-about-epcg-incentive-schemes-for-export-orders.md)

[(IND) Approve an EPCG license](ind-approve-an-epcg-license.md)

[(IND) Create an export order for an EPCG incentive scheme](ind-create-an-export-order-for-an-epcg-incentive-scheme.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

