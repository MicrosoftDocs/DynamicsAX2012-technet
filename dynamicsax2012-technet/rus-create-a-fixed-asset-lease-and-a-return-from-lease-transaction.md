---
title: (RUS) Create a fixed asset lease and a return from lease transaction
TOCTitle: (RUS) Create a fixed asset lease and a return from lease transaction
ms:assetid: 4ed19934-55ba-409c-8121-1f50dcf15ec1
ms:mtpsurl: https://technet.microsoft.com/library/JJ665372(v=AX.60)
ms:contentKeyID: 49387460
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a fixed asset lease and a return from lease transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can register the lease of an asset and the subsequent return of the leased asset to record the transactions for historical purposes.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Lease a fixed asset

1.  Click **Fixed assets (Russia)** \> **Common** \> **Fixed assets**.

2.  On the **Overview** tab, select the fixed asset to be leased, and then click **History** \> **Lease** to open the **FA leased** form.

3.  Press CTRL+N to create a new line.

4.  In the **Date of lease** field, select the date that the asset was leased out.

5.  In the **Expected return date** field, select the planned return date.

6.  In the **Leaseholder** field, enter the name of the lessee.

7.  In the **Location** field, select the location of the leased fixed asset.

8.  Close the form.

9.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

10. Press CTRL+N to create a new journal.

11. In the **Name** field, select a journal name.

12. In the **Description** field, view or modify the description of the journal.

13. Click **Lines** to open the **Journal voucher** form to create fixed asset transactions.

14. Press CTRL+N to open the **Add to journal** form.

15. In the **Transaction date** field, select the date of the transaction. You must specify a date that is the same as or later than the date specified on the **FA on loan** form.

16. In the **Transaction type** field, select **Lease**.

17. In the **FA number** field, select the leased fixed asset number.

18. In the **Value model** field, select a fixed asset value model.

19. In the **Reason code** field, select a reason code.

20. In the **Reason comment** field, view or modify the reason for the lease of the fixed asset.

21. Click **OK**. The lines for the leased asset are displayed in the journal.
    

    > [!NOTE]
    > <P>You can also click <STRONG>Group operations</STRONG> &gt; <STRONG>Lending</STRONG> to create transactions for several fixed assets.</P>



22. Click **Validate** \> **Validate** to validate the transaction.

23. Click **Post** \> **Post** to post the journal. Fixed asset and ledger transactions are created.
    

    > [!NOTE]
    > <P>The status of the fixed asset changes from <STRONG>Exploitation</STRONG> to <STRONG>Lending</STRONG> in the <STRONG>Fixed assets</STRONG> form.</P>



24. Press CTRL+S or close the form.

## Register the return of a leased fixed asset

You can register the return of a leased fixed asset in the same way that you registered the lease. Create a **Return from lease** transaction in the **FA journal** form, and then verify the return from lease dates in the **FA on loan** and **Journal transactions** forms.

1.  Click **Fixed assets (Russia)** \> **Common** \> **Fixed assets**.

2.  On the **Overview** tab, select the leased fixed asset to be returned, and then click **History** \> **Lease** to open the **FA leased** form.

3.  Press CTRL+N to create a new line.

4.  In the **Actual return date** field, view or modify the date.

5.  Repeat steps 9 through 22 in the Lease a fixed asset topic.
    

    > [!NOTE]
    > <P>You must select <STRONG>Return from lease</STRONG> in the <STRONG>Transaction type</STRONG> field to create a <STRONG>Return from lease</STRONG> transaction.</P>



6.  Click **Validate** \> **Validate** to validate the transaction.

7.  Click **Post** \> **Post** to post the journal. Fixed asset and ledger transactions are created.
    

    > [!NOTE]
    > <P>The status of the fixed asset changes from <STRONG>Lending</STRONG> to <STRONG>Exploitation</STRONG> in the <STRONG>Fixed assets</STRONG> form.</P>



8.  Press CTRL+S or close the form
    

    > [!NOTE]
    > <P>Lease and return from lease transactions are reversed in the same manner as acquisition transactions.</P>


  


