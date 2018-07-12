---
title: (IND) Define type of shift and industry for value models and attach to fixed asset
TOCTitle: (IND) Define type of shift and industry for value models and attach to fixed asset
ms:assetid: 5a76c5f3-1a6a-4811-8667-d03341338723
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677842(v=AX.60)
ms:contentKeyID: 49385808
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed assets
- value models
- (IND)
- India
- type of industry
- type of shift
audience: Application User
ms.search.region: India
---

# (IND) Define type of shift and industry for value models and attach to fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The calculation of depreciation for a fixed asset is for a specific period is based on the selected type of shift and industry. You can define rates for a single shift, double shift, and triple shift to calculate depreciation using the **Straight line service life** method or the **Reducing balance** method.

The calculation of depreciation is also based on the actual number of days in the calendar month when **DayBased** is selected in the **Calendar** field on the **Value models** form for the **Straight line service life** depreciation method or the **Reducing balance** depreciation method.

1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  Press CTRL+N to create a new value model.

3.  Enter an identification and brief description of the value model.

4.  Select the **Current** option in the **Posting layer** field.
    

    > [!NOTE]
    > <P>You must select the <STRONG>Current</STRONG> option in the <STRONG>Posting layer</STRONG> field to calculate depreciation for assets as per the Companies Act, 1956 with the depreciation profile set at the <STRONG>Straight line service life</STRONG> method or the <STRONG>Reducing balance</STRONG> method.</P>



5.  Select the fixed asset calendar for the value model.

6.  Click the **General** FastTab.

7.  Select the depreciation profile for the value model in the **Depreciation profile** field.
    
      - You cannot define an alternative depreciation profile in the **Alternative depreciation profile** field for a depreciation profile that follows the **Straight line service life** method or the **Reducing balance** method.
        

        > [!NOTE]
        > <P>The shift depreciation is not calculated if you attach an alternative depreciation profile that follows the <STRONG>Straight line service life</STRONG> method or the <STRONG>Reducing balance</STRONG> method to a depreciation profile.</P>

    
      - You cannot define an extraordinary depreciation profile in the **Extraordinary depreciation profile** field for a depreciation profile that follows the **Straight line service life** method.

8.  Select the calendar year from the **Calendar** field.

9.  Select the **Override fixed asset calendar days?** check box to override the number of days that are defined for a fixed asset calendar with the number of days that the asset is used during the calendar year.

10. Enter the total number of days that the asset is used during the calendar year in the **Asset working days** field.

11. Click **Shift depreciation**.
    

    > [!NOTE]
    > <P>The <STRONG>Shift depreciation</STRONG> button is activated only for a value model with a <STRONG>Current</STRONG> posting layer.</P>



12. Select the **From date** and **To date**.

13. Select the type of shift for the value model in the **Type of shift** field from the following options:
    
      - **None** – Shift depreciation does not apply for the value model.
    
      - **Single shift** – Apply single-shift depreciation for the value model.
    
      - **Double shift** – Apply double-shift depreciation for the value model.
    
      - **Triple shift** – Apply triple-shift depreciation for the value model.

14. Select the type of industry to apply a specific type of shift depreciation to in the **Type of industry** field from the following options:
    
      - **Non seasonal industry**
    
      - **Seasonal industry**

15. Press CTRL+S or close the form.

16. Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**. Double-click a fixed asset or, on the **Action Pane**, click **Fixed asset** or **Edit**.
    
    .
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa620341(v=ax.60)">Fixed assets (form)</A>in the Applications and Business Processes Help.</P>



17. Click **Value models** to attach a value model to a fixed asset.

18. Click **Shift depreciation** in the **Value models** form to view or modify the shift depreciation setup for a value model.
    

    > [!NOTE]
    > <P>The <STRONG>Shift depreciation</STRONG> button is activated when you select a value model <STRONG>Current</STRONG> select in the <STRONG>Posting layer</STRONG> field.</P>



## See also

[(IND) Fixed asset value model/shift depreciation (form)](https://technet.microsoft.com/en-us/library/jj678007\(v=ax.60\))

  


