---
title: (CHN) Run a batch job to check the continuity of voucher numbers
TOCTitle: (CHN) Run a batch job to check the continuity of voucher numbers
ms:assetid: 965d45f1-b80b-4cd5-9681-3dd5cd8ff013
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664081(v=AX.60)
ms:contentKeyID: 49384665
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Run a batch job to check the continuity of voucher numbers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Chinese voucher continuity check** form to run a batch job that determines whether Chinese voucher numbers are sequential. This process renumbers the vouchers to make sure that there is no gap in the continuity of Chinese vouchers for the selected fiscal period. Vouchers that have already been printed are also renumbered if they are in the selected fiscal period. These vouchers must be reprinted to make them consistent with the vouchers that are generated.


> [!NOTE]
> <P>To run the <STRONG>Chinese voucher continuity check</STRONG> batch process, you must select the <STRONG>Chinese voucher system</STRONG> check box in the <STRONG>General ledger parameters</STRONG> form.</P>



1.  Click **General ledger** \> **Periodic** \> **China** \> **Chinese voucher continuity check**.

2.  In the **Period start** field, select the starting date for the period from which the Chinese voucher number continuity is verified.

3.  Select the **Print out the result of renumbering** check box to print the renumbering report at the end of the batch process.

4.  On the **Batch** tab, select the **Batch processing** check box to renumber Chinese vouchers in a batch.

5.  Click **OK** to renumber the Chinese vouchers for continuity.

  


