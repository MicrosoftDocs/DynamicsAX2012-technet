---
title: (CHN) Set up a Chinese voucher system
TOCTitle: (CHN) Set up a Chinese voucher system
ms:assetid: ef5dec31-b525-4155-83b3-c684265d8659
ms:mtpsurl: https://technet.microsoft.com/library/JJ664138(v=AX.60)
ms:contentKeyID: 49384720
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- CN - 00009
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Set up a Chinese voucher system 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a voucher document for every posted journal, and then print a paper voucher and/or a posted journal. You can use booking vouchers to enter Receipt, Payment, and Transfer types of transactions.

According to some accounting rules, the voucher types must be validated in a journal, and a continuous number sequence beginning from the first of every period (monthly) should be assigned to each voucher type.

You can enter transactions using the **Simple** or **Advanced** method in the **Journal** form, using the **Daily journal** type. Voucher numbers can be duplicated from one accounting period to another.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Parameter setup

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Select **Accept duplicates** in the **Check for voucher used** field to accept the duplication of voucher numbers.

3.  Select the **Chinese voucher system** check box.

4.  Press CTRL+S or close the form.

## Number sequence setup

1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**. On the Action Pane, in the **Additions** group, click **Additions**.

2.  On the **Additions** form, on the **Setup** tab, select the **Restart numbering for each period** check box to start the numbering of vouchers from the first of each accounting period. Duplication of voucher numbers from one period to another is allowed when this check box is selected.
    
    For example, the number sequence for voucher type **Rec** starts the numbering with 001 for March 2009. If voucher type **Rec** is used to create vouchers in April 2009, the numbering will again start with 001.

3.  Press CTRL+S or close the form.

## See also

[(CHN) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj664137\(v=ax.60\))

[(CHN) Number sequences (modified form)](https://technet.microsoft.com/library/jj664047\(v=ax.60\))

[(CHN) Run a batch job to check the continuity of voucher numbers](chn-run-a-batch-job-to-check-the-continuity-of-voucher-numbers.md)

[(CHN) Generate and print a Chinese voucher](chn-generate-and-print-a-chinese-voucher.md)

  


