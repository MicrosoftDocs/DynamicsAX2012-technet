---
title: (HUN) Create a single vendor payment transfer
TOCTitle: (HUN) Create a single vendor payment transfer
ms:assetid: 9fe36acb-6575-4f98-a3bb-cb46275ceb1c
ms:mtpsurl: https://technet.microsoft.com/library/JJ664341(v=AX.60)
ms:contentKeyID: 49385430
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Create a single vendor payment transfer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The MultiCash system includes a bank-Giro format to transfer domestic payments in domestic (HUF) currency and another format to payments in foreign currencies. Generating payments is similar to the standard functionality in Microsoft Dynamics AX. When you create payments, the payment file in the required format is generated, according to the selected currency code.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines**.

2.  In the **Company accounts** field, select the company account.

3.  In the **Account** field, select the account.

4.  In the **Description** field, select the transaction text.

5.  In the **Debit** or **Credit** field, enter the amount.

6.  In the **Offset account type** field, select the offset account.

7.  In the **Offset account** field, select the bank account.

8.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

9.  In the **Export format** field, select **MCash (HU)**.

10. In the **Bank account** field, select the bank account for payment.

11. Click **Dialog** to open the **MCash (HU)** form, and select the domestic currency in the currency field.

12. Select the **Export in domestic currency** check box.
    

    > [!NOTE]
    > <P>When this check box is selected, the export file has an ".ung" file name extension and contains only the payment vouchers in HUF currency. Otherwise, the file name extension is ".hua" and the export file contains only payment vouchers in EUR or DEM currency.</P>



13. In the **Processing date** field, select the payment processing date.

14. In the **File name** field, select the file name for the payment file.

15. Click **OK** to close the form.

16. Click **OK** to generate the payment file.
    

    > [!NOTE]
    > <P>The export file has an ".ung" file name extension, and contains only those payment vouchers with a positive credit amount in HUF currency.</P>



17. Press CTRL+S or close the form.

## See also

[(HUN) Set up an export format](hun-set-up-an-export-format.md)

[(EEUR) Invoice register journal lines (modified form)](https://technet.microsoft.com/library/jj730992\(v=ax.60\))

  


