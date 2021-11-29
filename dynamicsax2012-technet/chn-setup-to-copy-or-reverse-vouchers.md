---
title: (CHN) Setup to copy or reverse vouchers
TOCTitle: (CHN) Setup to copy or reverse vouchers
ms:assetid: 1a83fc37-e2ad-4efa-87c4-b98e490ee84a
ms:mtpsurl: https://technet.microsoft.com/library/JJ664003(v=AX.60)
ms:contentKeyID: 49384587
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Setup to copy or reverse vouchers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can copy transactions for an existing voucher and reverse the voucher transactions of a voucher that is posted incorrectly.

You can complete the following two actions:

  - Copy the voucher transactions of a posted voucher to a new voucher.

  - Copy and reverse the voucher transactions of an incorrectly posted voucher to a new voucher.

## Configuration key setup

1.  Click **System administration** \> **Setup** \> **Licensing** \> **License configuration**.

2.  Expand the **Country/Regional specific features** node and select the **China** check box.

3.  Click **OK**.

## Parameter setup

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Select the **Copy/Reverse voucher** check box.
    

    > [!NOTE]
    > <P>This check box is available only when the <STRONG>Chinese voucher system</STRONG> check box is selected.</P>



3.  Press CTRL+S or close the form.

## See also

[(CHN) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj664137\(v=ax.60\))

[(CHN) Copy and reverse a voucher](chn-copy-and-reverse-a-voucher.md)

  


