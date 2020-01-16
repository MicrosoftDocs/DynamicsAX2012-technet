---
title: (RUS) Set up calculation sequences, counters, and deferred expense write-off factors
TOCTitle: (RUS) Set up calculation sequences, counters, and deferred expense write-off factors
ms:assetid: 2ac680a6-36ad-40e7-93d3-b889b8fcbecc
ms:mtpsurl: https://technet.microsoft.com/library/JJ665229(v=AX.60)
ms:contentKeyID: 49387318
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up calculation sequences, counters, and deferred expense write-off factors 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Deferrals** \> **Sequence of calculation**.

2.  Press CTRL+N to create a new line.

3.  In the **Sequence** field, enter the sequence number.

4.  In the **Description** field, enter a description of the calculation sequence.

5.  In the **Channel** field, select the **Deferral** output format for the calculation results.
    

    > [!NOTE]
    > <P>The calculation results are used to create future expense cards.</P>



6.  In the **Channel Reference** field, select the deferred expense group where you want to record the calculation results.
    

    > [!NOTE]
    > <P>If you create deferred expenses using the ledger and tax accounting models simultaneously, separate the values with commas.</P>



7.  Click **Counters** to open the **Counter setup** form to create counters for the calculation sequence.

8.  Press CTRL+N to create a new line.
    

    > [!NOTE]
    > <P>For more information.</P>



9.  In the **Output** field, select **Data output**.
    

    > [!NOTE]
    > <P>The deferred expense amount is displayed in the <STRONG>Data output</STRONG> field.</P>



10. Press CTRL+S or close the form.

11. Click **General ledger** \> **Setup** \> **Deferrals** \> **Writing off methods**.

12. Press CTRL+N to create a new line.

13. In the **Writing off method** field, enter the write-off method code.

14. In the **Name** field, enter the name of the write-off method.

15. In the **Type** field, select the write-off method type from the following options:
    
      - **Linear** – Provides an equivalent amount for deferrals write-off within a given interval over the defined period.
    
      - **Manual** – The percentage of the total to be written off in each period is entered manually in the **Manual schedules** form.
    
      - **Linear with factor** – The calculated result is multiplied by a calculated ratio.
    

    > [!NOTE]
    > <P>Set the deferred expense write-off factor between 0 and 1, defined according to the following formula: Factor = Standard Amount / Base Amount. In order to take into account the deferred write-off for the current period during factor calculation, define the value of the base amount with the line type <STRONG>Deferral write-off</STRONG>.</P>



16. In the **Writing off period** field, select the write-off period for the deferred expense.

17. Click the **General** tab. In the **Calculation period** field, select the calculation period for deferrals write-off from the following options:
    
      - **Month** – The deferrals write-off calculation is performed proportionately to the number of months in the given period.
    
      - **Day** – The deferrals write-off calculation is performed proportionately to the number of days in the selected period. This allows calculation of deferrals write-off during an incomplete reporting period, depending on the number of calendar days.
    
      - **Period** – The deferrals write-off calculation is performed proportionately to the number of periods that are defined in the **Writing off period** field.
        

        > [!NOTE]
        > <P>This field is activated only if you select <STRONG>Linear</STRONG> or <STRONG>Linear with factor</STRONG> in the <STRONG>Type</STRONG> field on the <STRONG>Overview</STRONG> tab. The calculation period defines the level of detail to be used when performing the calculation.</P>



18. In the **Round-off** field, enter the round-off for the deferrals write-off amount. For example, if the figure 0.01 is specified, then figures will be rounded off to two decimal places.

19. Click **Manual schedules** to open the **Manual schedules** form, and enter the write-off schedule for the manual write-off method.
    

    > [!NOTE]
    > <P>This button is activated only if you select <STRONG>Manual</STRONG> in the <STRONG>Type</STRONG> field.</P>



20. Press CTRL+S or close the form.

## See also

[(RUS) Standard expenses sequence (form)](https://technet.microsoft.com/library/jj853198\(v=ax.60\))

[(RUS) Writing off methods (form)](https://technet.microsoft.com/library/jj711659\(v=ax.60\))

  


