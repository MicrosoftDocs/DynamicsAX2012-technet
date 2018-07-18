---
title: (CZE) Apply half-yearly depreciation for tax purposes
TOCTitle: (CZE) Apply half-yearly depreciation for tax purposes
ms:assetid: a6ac7511-d1e5-457a-86c5-0126c179b624
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ683244(v=AX.60)
ms:contentKeyID: 49685125
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Apply half-yearly depreciation for tax purposes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When a fixed asset is sold or otherwise disposed of, you can apply half the yearly depreciation for the asset for tax purposes. This half-yearly depreciation can be applied regardless of the disposal date.

## Set up depreciation methods for the depreciation profile

Use the **Regular CZ** and **Accelerated CZ** depreciation methods to apply half-yearly depreciation for a fixed asset.

1.  Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation profiles**.

2.  Click **New** to create a depreciation profile.

3.  In the **Method** field, select **Regular CZ** or **Accelerated CZ**.

4.  In the **Depreciation year** field, select **Calendar** as the basis for the calculation of depreciation.

5.  In the **Period frequency** field, select **Yearly**.

## Apply the half-yearly depreciation method

After you set up the depreciation methods, you can apply half the yearly depreciation for assets that were disposed of.

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  On the **Overview** tab, click **New** to create a journal, and then enter the required details.

3.  Click **Lines** to open the **Journal voucher** form.

4.  Create a journal line for the fixed asset that was disposed of or sold.

5.  Click **Proposals** \> **Depreciation proposal** to open the **Depreciation proposal** form.

6.  In the **To date** field, enter the journal date.

7.  Select the **Calculate half-year depreciation amount** check box to calculate half-yearly depreciation. When this check box is selected, the yearly depreciation amount is divided by two and rounded according to the round-off setup for the depreciation book.

8.  Optional: Select the **Summarize depreciation** check box to summarize the calculated depreciation for each fixed asset or for each value model.

9.  Click **OK** to close the **Depreciation proposal** form.

10. Post the journal.

## See also

[(CZE) Depreciation proposal (modified form)](https://technet.microsoft.com/en-us/library/jj677565\(v=ax.60\))

  


