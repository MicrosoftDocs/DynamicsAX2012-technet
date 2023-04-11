---
title: (RUS) Generate a reverse transaction journal using the Copy Journal function
TOCTitle: (RUS) Generate a reverse transaction journal using the Copy Journal function
ms:assetid: 19a91fc2-3fc5-4cf4-a252-ba10f2746c71
ms:mtpsurl: https://technet.microsoft.com/library/JJ711438(v=AX.60)
ms:contentKeyID: 49387256
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a reverse transaction journal using the Copy Journal function 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Copy** function simplifies generation of reverse transaction journals by letting you copy lines from an existing journal into a new journal. If reverse transactions are canceled by using the journal copy function, the resulting transactions are reflected as direct transactions. They are not marked as reverse.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Movement**.
    
    –or–
    
    Click **Inventory management** \> **Journals** \> **Item transactions** \> **Inventory adjustment**.
    
    –or–
    
    Click **Inventory management** \> **Journals** \> **Item transactions** \> **Transfer**.
    
    –or–
    
    Click **Inventory management** \> **Journals** \> **Item transactions** \> **Bills of materials**.
    

    > [!NOTE]
    > <P>For more information, see "Inventory journal (form)" in the Applications and Business Processes Help.</P>



2.  In the **Inventory journal** form, select the inventory journal line to be reversed.

3.  Click **Functions** \> **Copy** to open the **Copy lines to a new journal** form.

4.  In the **Journal** field, select the journal to be copied.

5.  In the **Description** field, enter a brief description of the journal.

6.  In the **Transaction date** field, enter the date for the new journal lines.
    

    > [!NOTE]
    > <P>If this field is left blank, the lines will be created with the same dates as the lines in the original journal.</P>



7.  In the **Detail level** field, select the level of detail to be copied. The options are:
    
      - **Journal Lines** – New journal lines will be copied from the original journal.
    
      - **Inventory Transactions** – New journal lines will be copied from the lines for inventory transactions in the original journal.

8.  Select the **Invert sign** check box so that quantities in the new journal lines appear with the opposite sign.

9.  Select the **Storno** check box so that the new journal lines are the reverse of the original lines.
    

    > [!NOTE]
    > <P>You can select this check box only if the <STRONG>Invert sign</STRONG> check box is selected.</P>



10. Select the **Automarking** check box to link created issue transactions with original transactions, or to determine return lots from original transactions.
    

    > [!NOTE]
    > <P>This check box is selected by default. To set up marking and return functions, you must clear this check box.</P>



11. Click **ОK** to copy the journal lines.
    

    > [!NOTE]
    > <P>When you copy journals with the reversing entry parameter activated, links to the inventory transactions that were used to create the journal line are automatically created and saved. If the <STRONG>Inventory Transactions</STRONG> parameter is activated, any inventory transactions with the receipt status <STRONG>Registered</STRONG> and inventory issue transactions with the status <STRONG>Reserved</STRONG> are created in the new journal. This prevents dimension changes due to inventory transactions prior to journal posting (for example, as a result of an automatic reservation).</P>



## See also

[(RUS) Post a reverse transaction manually using inventory journals](rus-post-a-reverse-transaction-manually-using-inventory-journals.md)

  


