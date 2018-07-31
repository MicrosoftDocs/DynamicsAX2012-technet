---
title: (IND) Set up parameters to calculate depreciation
TOCTitle: (IND) Set up parameters to calculate depreciation
ms:assetid: 61465f58-f096-4145-852b-258fb8725418
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677857(v=AX.60)
ms:contentKeyID: 49385819
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up parameters to calculate depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the **Companies Act depreciation** check box to calculate depreciation based on the Companies Act of India and to generate the Depreciation schedule report.

3.  Under the **India Depreciation** field group, enter information in the following fields:
    
      - **Min. working days for seasonal industries** – Enter the minimum number of working days to calculate depreciation on fixed assets for seasonal industries.
    
      - **Min. working days for non-seasonal industries** – Enter the minimum number of working days to calculate depreciation on fixed assets for non-seasonal industries.
    
      - **Max. acquisition value to avail full depreciation** – Enter the maximum acquisition value for a fixed asset to avail full depreciation. You can avail full depreciation on a fixed asset in a specific year that the fixed asset is used if the acquisition value of the fixed asset is equal to or less than the value specified in this field.
    

    > [!NOTE]
    > <P>Full depreciation is calculated based on the parameter setup, only if the depreciation profile that is attached to the value model uses the Straight line percentage method or the Reducing balance method.</P>



4.  Press CTRL+S or close the form.

## See also

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj677901\(v=ax.60\))

  


