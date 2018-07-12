---
title: (RUS) Generate a deferral using a periodic voucher
TOCTitle: (RUS) Generate a deferral using a periodic voucher
ms:assetid: 90ee0677-f96f-4ca8-ab0e-c13ba8998ab6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678477(v=AX.60)
ms:contentKeyID: 49387705
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.Dialog
- Forms.RTax25StdSeq
- Forms.RTax25StdExpressionTable
- MsDynAx060.Forms.Dialog
- MsDynAx060.Forms.RTax25StdSeq
- MsDynAx060.Forms.RTax25StdExpressionTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a deferral using a periodic voucher 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



After you set up the calculation sequences and counters for a deferrals group, you can create a deferral voucher.

## Set up calculation sequences

1.  Click **General ledger** \> **Setup** \> **Deferrals** \> **Sequence of calculation**. Click **Sequence of calculation** to open the **Standard expenses sequence** form.

2.  Press CTRL+N to create a new line.

3.  In the **Sequence** field, enter the sequence number.

4.  In the **Description** field, enter a description of the sequence of calculation.

5.  In the **Channel** field, select the **Ratio** output format for the sequence calculation results.
    

    > [!NOTE]
    > <P>Deferrals are created from the calculation results.</P>



6.  In the **Channel Reference** field, select the deferred expense group where you want to record the calculation results.
    

    > [!NOTE]
    > <P>If you create deferred expenses using the ledger and tax accounting models simultaneously, specify all of them, separated with commas.</P>



7.  Press CTRL+S or close the form.

## Set up counters

1.  Click **General ledger** \> **Setup** \> **Deferrals** \> **Sequence of calculation**. Click **Counters** to open the **Counter setup** form.

2.  Press CTRL+N to create a new line.
    

    > [!NOTE]
    > <P>&nbsp;&nbsp;&nbsp;For more information, see <A href="rus-set-up-counters.md">(RUS) Set up counters</A>.</P>



3.  In the **Table field** field, specify the field to be sent to the channel.

4.  Press CTRL+S or close the form.

## Generate deferrals

1.  Click **General ledger** \> **Periodic** \> **Deferrals** \> **Deferrals creating**. Click **Calculate marked**
    
    –or–
    
    Click **General ledger** \> **Periodic** \> **Deferrals** \> **Deferrals creating**. Click **Calculate all** to open the **Deferrals creating** form.

2.  In the **Start date** and **End date** fields, enter the starting and ending dates for the deferral calculation.

3.  Select the **Overwrite** check box to overwrite all existing deferrals for the specified period that do not contain write-off or disposal vouchers.

4.  Select the **Preview** check box to view or modify the deferrals before creation.
    

    > [!NOTE]
    > <P>If the <STRONG>Preview</STRONG> check box is not activated, the deferrals are automatically generated based on the parameters that were entered in the <STRONG>Deferrals creating</STRONG> form.</P>



5.  Select the **Only from ledger vouchers** check box to create deferrals from the ledger documents only. Any deferrals that are generated based on purchases will not be accounted for.

6.  Click **OK** to open the **Deferrals creating** form, where you can change parameters for the deferrals that are being created.
    

    > [!NOTE]
    > <P>You can open this form only if the <STRONG>Preview</STRONG> check box is activated.</P>



7.  Click **Create deferrals** to create the deferral voucher.


> [!NOTE]
> <P>Click <STRONG>General ledger</STRONG> &gt; <STRONG>Common Forms</STRONG> &gt; <STRONG>Deferrals</STRONG> to view the generated deferrals source details on the <STRONG>General</STRONG> tab.</P>



## See also

[(RUS) Deferrals creating (form)](https://technet.microsoft.com/en-us/library/jj839648\(v=ax.60\))

[(RUS) Standard expenses sequence (form)](https://technet.microsoft.com/en-us/library/jj853198\(v=ax.60\))

[(RUS) Counter setup (form)](https://technet.microsoft.com/en-us/library/jj856173\(v=ax.60\))

  


