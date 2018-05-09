---
title: (POL) Calculate depreciation
TOCTitle: (POL) Calculate depreciation
ms:assetid: 96d8ce8c-9d33-42ca-b19a-7e523e55577f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ730409(v=AX.60)
ms:contentKeyID: 49636328
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Calculate depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can calculate depreciation for fixed assets with an **Open** status for periods in which depreciation has not yet been posted.

**Example**

Available depreciation methods for Poland are:

  - **Reducing balance (Poland)** - This depreciation method considers special local legal requirements about Fixed asset value change during fiscal year and cost part recognition.

  - **Straight line (Poland)** – Depreciation is calculated for the first period for the number days that the asset was used. For example, if a fixed asset was purchased January 15 and the depreciation period starts January 1, depreciation will be calculated for half of the period.

  - **Straight line percentage (Poland)** – The service life is calculated by entering a percentage and dividing 100% by the percentage entered. For example, if you entered 20%, 100% divided by 20% is 5 service years.

Depreciation for all fixed assets can be calculated and posted in one single operation.

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Click **Proposals** \> **Depreciation proposal** to open the **Depreciation proposal** form.

3.  In the **To date** field, enter the date through which depreciation is calculated.

4.  Select the **Summarize depreciation** check box to summarize all monthly depreciation into one journal line for a single fixed asset or value model.
    

    > [!NOTE]
    > <P>For more information, see "Depreciation proposal (form)" in the Application user Help.</P>



## See also

[(POL) Set up depreciation of fixed assets](pol-set-up-depreciation-of-fixed-assets.md)

[(POL) Fixed asset value models (modified form)](https://technet.microsoft.com/en-us/library/jj730408\(v=ax.60\))

[(POL) Set up depreciation of fixed assets](pol-set-up-depreciation-of-fixed-assets.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

