---
title: (RUS) Post a reverse transaction manually using inventory journals
TOCTitle: (RUS) Post a reverse transaction manually using inventory journals
ms:assetid: 1c42cec4-eed4-4993-8139-5c02a4b29bf8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711449(v=AX.60)
ms:contentKeyID: 49387268
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Post a reverse transaction manually using inventory journals [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Movement**.
    
    –or–
    
    Click **Inventory management** \> **Journals** \> **Item transactions** \> **Transfer**.
    
    –or–
    
    Click **Inventory management** \> **Common** \> **Bills of materials**.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa558607(v=ax.60)">Inventory journal (form)</A>.</P>



2.  In the **Inventory journal** form, select the journal line to be reversed.

3.  On the **General** tab, select the **Storno** check box to activate the reversing entry parameter for inventory journal lines when creating a new line.

4.  Click **Lines** to open the **Journal lines, inventory** form, and then enter the required details.
    

    > [!NOTE]
    > <P>If the reversing entry parameter is already activated, the reversing entry parameter is applied to journal lines automatically.</P>



5.  On the **General** tab, in the **Return lot ID** field, select the return lot.
    

    > [!NOTE]
    > <P>The return lot is entered in the receipt transaction and allows the receipt cost price of the lot to be determined by the issue cost price of that lot.</P>



6.  Click **Validate** to validate the journal.

7.  Click **Post** to post the journal.
    

    > [!NOTE]
    > <P>You can view the reverse transactions of Inventory transaction in the <STRONG>Posting</STRONG> form. If the Extended Validation parameter in the <STRONG>Inventory Parameters</STRONG> form is activated, during validation using the same financial and inventory dimensions, the reverse transaction is posted in the journal as reversed transactions.</P>
    > <P>If, during validation, the inventory dimensions do not match and therefore the journal posting cannot be performed, an Infolog message will appear. This tool is very convenient when you need to display the original and reversed transactions.</P>



## See also

[(RUS) Set up reverse transactions](rus-set-up-reverse-transactions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

