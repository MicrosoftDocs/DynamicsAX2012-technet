---
title: Propose depreciation for fixed assets
TOCTitle: Propose depreciation for fixed assets
ms:assetid: a05a6286-41e5-41b6-b42b-19631ac5f938
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn479034(v=AX.60)
ms:contentKeyID: 59632402
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation
- propose
- propose depreciation
---

# Propose depreciation for fixed assets [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how depreciation batch proposals work and explains how to propose depreciation for fixed assets.

When you propose depreciation, depreciation is calculated for the fixed assets, and then depreciation transactions (journal lines) are created. However, the transactions are not yet posted, so you can review them and before you post them.

You can propose depreciation for fixed assets in two ways: from the **Journal voucher** form or from the **Create acquisition or depreciation proposals for fixed assets** form.

When you use the **Create acquisition or depreciation proposals for fixed assets** form, you can propose depreciation in batches. This is what we recommend for larger proposals that use up more system resources. If you select the batch option, you can still use Microsoft Dynamics AX to complete other tasks during that time. When you propose depreciation in this way, depreciation is calculated for value models for fixed assets. For more information, see [Set up value models](set-up-value-models.md).

When you use the **Journal voucher** form, depreciation is calculated by using depreciation books.

After the depreciation proposal process is complete, you can review the proposed depreciation transactions in the **Journal voucher** form.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## Propose depreciation transactions for fixed assets

To propose and later post transactions for the periodic depreciation of eligible fixed assets, follow these steps:

1.  Click **Fixed assets** \> **Periodic** \> **Create fixed assets proposals**.

2.  In the **Create acquisition or depreciation proposals for fixed assets** form, select the posting layer that the proposal is based on.

3.  In the **Name of journal** field, select the journal where the depreciation transactions will be created.

4.  Click **Proposals** and select **Depreciation proposal**.

5.  Click **Select** to create a query to limit and sort the data to include in the proposal.

6.  In the **To date** field, enter the ending date of the period to create depreciation transactions for.

7.  Select the **Summarize depreciation** check box to summarize monthly depreciations into one journal line.
    
    For example, if the **To date** value is March 31, 2014, the following description is generated: “Depreciation since January 31, 2014.” The **Date** field on the proposed journal lines is then set to March 31, 2014.

8.  To propose depreciation by using a batch process, click **Batch** and select the **Batch processing** check box. For more information, see [Create a batch job](create-a-batch-job.md).
    

    > [!WARNING]
    > <P>If you click the <STRONG>Recurrence</STRONG> button, new proposals are not created. Depreciation proposals can’t be set up as recurring batches.</P>



9.  Click **OK** to create the unposted depreciation transactions.

10. Review the asset book entries that were created. Click **Fixed assets** \> **Journals** \> **Fixed assets**. Select the journal that was created in the previous step, and then click **Lines**.
    

    > [!NOTE]
    > <P>Each journal can contain up to 2,000 transactions. If the depreciation proposal process creates more than 2,000 transactions, these transactions will be split across multiple journals. The summarized depreciation proposal process creates all the asset book entries in one journal.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

