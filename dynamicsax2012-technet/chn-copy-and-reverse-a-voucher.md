---
title: (CHN) Copy and reverse a voucher
TOCTitle: (CHN) Copy and reverse a voucher
ms:assetid: 339adbdf-f41a-4425-a09c-11697866405a
ms:mtpsurl: https://technet.microsoft.com/library/JJ664019(v=AX.60)
ms:contentKeyID: 49384603
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- CN - 00011
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Copy and reverse a voucher 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Refer to the following information to set up and perform the following actions:

  - Copy the voucher transactions of a posted voucher to a new voucher.

  - Copy and reverse the voucher transactions of an incorrectly posted voucher to a new voucher.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Parameter setup

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Ledger**, and then select the **Chinese voucher system** check box.

3.  Select the **Copy/Reverse voucher** check box.

4.  Press CTRL+S or close the form.

## Copy a voucher

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new voucher and click **Lines** to open the **Journal voucher** form.

3.  Click **Functions** and then click **Load ledger transactions**.

4.  Select the voucher type in the **Voucher type** field.
    

    > [!NOTE]
    > <P>The copied voucher and original voucher must be of the same voucher type. The voucher type will provide the voucher number for the copied voucher.</P>



5.  Click **Select**.

6.  Enter the criteria for the voucher that will be copied.

7.  Click **OK** to open the **Voucher transactions** form.

8.  Select the voucher to copy, and then click **Select lines**.

9.  In the **Load ledger transactions** form, click **OK**. The voucher is copied to the **Journal voucher** form. The voucher will have an **Open** status.

10. Validate and post the voucher.

## Reverse a voucher

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new voucher and click **Lines** to open the **Journal voucher** form.

3.  Click **Functions** and then click **Load ledger transactions**.

4.  Select the voucher type in the **Voucher type** field. The voucher type will provide the voucher number for the reversed voucher.
    

    > [!NOTE]
    > <P>The voucher type should be of the reverse type to the original voucher. For example, if the original voucher type is <STRONG>Payment</STRONG>, the reversal voucher type must be <STRONG>Receipt</STRONG>.</P>



5.  Select the **Invert sign** check box to activate the **Reversal method** field.

6.  In the **Reversal method** field, select a reversal option.
    
      - **Debit/credit** – The original voucher is reversed by changing the debit entry to credit entry on the reversal voucher.
    
      - **+/-** – The original voucher is reversed by inverting the amount signs on the reversal voucher.

7.  Click **Select** to open the **Select** form.

8.  Enter the criteria to select the voucher to copy.

9.  Click **OK** to open the **Voucher transaction** form.

10. Select the voucher to reverse, and click **Select lines**.

11. In the **Load ledger transactions** form, click **OK** to reverse the voucher. The reversal entry of the original voucher is displayed in the **Journal voucher** form and the reversed voucher will have an **Open** status in the **Journal** form.

12. Validate and post the voucher.

## See also

[(CHN) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj664137\(v=ax.60\))

  


