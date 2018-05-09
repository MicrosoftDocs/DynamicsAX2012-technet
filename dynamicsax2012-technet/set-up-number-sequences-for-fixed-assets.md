---
title: Set up number sequences for Fixed assets
TOCTitle: Set up number sequences for Fixed assets
ms:assetid: fd319d2b-901e-4d82-b12d-5aa23546d146
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa500112(v=AX.60)
ms:contentKeyID: 36060102
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- fixed asset number sequence
- number sequence
- asset number sequence
- FA number sequence
---

# Set up number sequences for Fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up number sequences for fixed assets based on a default number sequence, or based on fixed asset groups. You also can set up number sequences to use for fixed assets with bar codes and for journals that you use to post fixed asset transactions.

## Number sequences for fixed asset numbering

There are two methods to assign number sequences to fixed assets.

## Method 1: Automatic numbering of all fixed assets from one default number sequence

1.  Before you create any fixed asset transactions, create at least one number sequence for fixed asset numbering. (Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**. Click **Number sequence** and then enter information for the number sequence.)

2.  Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**. Click **Number sequences**, and then select a number sequence code for the **Fixed asset number** reference.
    
    When a fixed asset is created, a number from this number sequence is automatically entered in the **Fixed asset number** field.
    

    > [!NOTE]
    > <P>If you assign special numbering sequences to some fixed asset groups (see the second method), the general default sequence continues to be used for the automatic numbering of fixed assets that are assigned to fixed asset groups that do not have group-specific number sequences.</P>



## Method 2: Automatic numbering based on fixed asset group

1.  Create a number sequence for fixed asset groups. (Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**. Click **Number sequence** and then enter information for the number sequence.)

2.  Click **Fixed assets** \> **Setup** \> **Fixed asset groups**.

3.  Select a fixed asset group. On the **General** tab, select the **Autonumber fixed assets** check box, and select the appropriate number sequence in the **Number sequence code** field. This number sequence is used for all fixed assets that are assigned to the fixed asset group.
    
    If there is a default number sequence for all fixed assets (see the first method), the default sequence is used for the automatic numbering of fixed assets that are assigned to fixed asset groups without group-specific number sequences.
    

    > [!NOTE]
    > <P>To type the number of each fixed asset in the <STRONG>Fixed asset number</STRONG> field, you do not have to set up number sequences for fixed assets or fixed asset groups.</P>



## Number sequences for bar codes

You can set up separate number sequences for bar codes for fixed assets. For more information, see [Assign fixed asset numbers to bar codes](assign-fixed-asset-numbers-to-bar-codes.md).

## Number sequences for journals

You must create number sequences for the journals that you will use to post fixed asset transactions and also enter a number sequence in the journal before you create fixed asset transactions. The journals that are usually used for fixed asset transactions are **Fixed assets**, **Inventory to fixed assets**, **General journal**, and **Fixed asset budget**. Depreciation book journals use the same number sequence that is defined for the **Journal batch number** reference in the **General ledger parameters** form.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

