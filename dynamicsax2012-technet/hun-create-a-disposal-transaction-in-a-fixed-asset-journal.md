---
title: (HUN) Create a disposal transaction in a fixed asset journal
TOCTitle: (HUN) Create a disposal transaction in a fixed asset journal
ms:assetid: 1567703f-f921-4a51-bc7c-b6e0a1521385
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664231(v=AX.60)
ms:contentKeyID: 49385320
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Create a disposal transaction in a fixed asset journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create a disposal transaction in a fixed asset journal, the transaction is posted in the selected account. If the disposal transaction is based on the standard configuration, the balance sheet amount for the asset is decreased by twice the net book value. You can specify the number of an offset account in the posting profile.


> [!NOTE]
> <P>When you post the disposal sale or disposal scrap of an asset, the asset and ledger transactions are not created to register the disposal of the net book values.</P>




> [!NOTE]
> <P>For more information, see "Set up posting profile for disposal" in the Applications and Business Processes Help.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Press CTRL+N to create a new line.

3.  Click **Lines** to open the **Journal voucher** form.

4.  Press CTRL+N to create a new line.

5.  In the **Date** field, select the date of disposal.

6.  In the **Transaction type** field, select **Disposal-sale** or **Disposal-scrap**.
    

    > [!NOTE]
    > <P>For more information, see "Fixed assets Journal lines (form)" and "Disposal" in the Application and Business Processes Help.</P>



7.  Click **Post** \> **Post** to post the journal.

## See also

[(HUN) Set up a posting profile for a disposal sale](hun-set-up-a-posting-profile-for-a-disposal-sale.md)

  


