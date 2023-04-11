---
title: (EEUR) Post the pre-acquisition and acquisition of a fixed asset
TOCTitle: (EEUR) Post the pre-acquisition and acquisition of a fixed asset
ms:assetid: ee60e228-4ff3-493c-869e-77e627def734
ms:mtpsurl: https://technet.microsoft.com/library/JJ714484(v=AX.60)
ms:contentKeyID: 49651581
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Post the pre-acquisition and acquisition of a fixed asset 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedures to create and post pre-acquisitions and acquisitions.

A pre-acquisition of a fixed asset is not depreciable, and it does not affect the acquisition costs and the net book value of the fixed asset. When you post a pre-acquisition, the status of the fixed asset changes to **Acquired**. A fixed asset that has the **Acquired** status is not depreciable. When you post an acquisition, the status changes to **Open**, and the fixed asset is depreciable.

To post pre-acquisitions, verify the following prerequisites:

  - Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**. In the **Fixed assets** area, verify that the **Allow pre-acquisitions** check box is selected.

  - Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**. Verify that a posting profile is set up for the **Pre-Acquisition** posting type.

### Post a pre-acquisition of a fixed asset

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Click **New** to create a journal, and then enter the required information. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).

3.  Click **Lines** to open the **Journal voucher** form.

4.  Click **New** to create a line. In the **Transaction type** field, select a transaction that has the **Pre-Acquisition** transaction type.

5.  Specify values for the remaining fields. For more information, see [Journal voucher - Fixed assets (form)](https://technet.microsoft.com/library/aa620564\(v=ax.60\)).

6.  Click **Validate** to validate the journal lines.

7.  Click **Proposals** \> **Pre-acquisition proposal**.

8.  Click **Select** to set up the selection criteria, and then click **OK**.

9.  Click **OK** to close the **Pre-acquisition proposal** form. Click **Post** \> **Post** to post the pre-acquisition transaction. In the **Value models** form, the status of the fixed asset changes to **Acquired**.

### Post an acquisition of a fixed asset

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Click **New** to create a journal, and then enter the required information. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).

3.  Click **Lines** to open the **Journal voucher** form.

4.  Click **New** to create a line. In the **Transaction type** field, select a transaction that has the **Acquisition** transaction type.

5.  Specify values for the remaining fields. For more information, see [Journal voucher - Fixed assets (form)](https://technet.microsoft.com/library/aa620564\(v=ax.60\)).

6.  Click **Validate** to validate the journal.

7.  Click **Proposals** \> **Acquisition proposal**.

8.  Click **Select** to set up the selection criteria, and then click **OK**.

9.  Click **OK** to close the **Acquisition proposal** form. Click **Post** \> **Post** to post the acquisition transaction. In the **Value models** form, the status of the fixed asset changes to **Open**.

  


