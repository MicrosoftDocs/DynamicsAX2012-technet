---
title: (IND) Set up asset group depreciation for value models
TOCTitle: (IND) Set up asset group depreciation for value models
ms:assetid: 001579f0-1b41-4c21-b4bf-315924b493ec
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664421(v=AX.60)
ms:contentKeyID: 49385511
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Set up asset group depreciation for value models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can use asset group depreciation for assets that are similar in nature and for those assets that have the same number of years of life. Asset group depreciation method is opposite to other methods of depreciation where assets are depreciated individually or where dissimilar assets are grouped together. You can use value models for accounting depreciation, tax depreciation, revaluation, and disposal as opposed to depreciation books which is used for reporting asset information for tax and other non-financial reporting.

You can also define the asset group depreciation for value models by using the **Fixed asset group/value model** form.


> [!NOTE]
> <P>The asset group depreciation check box can be selected only for a value model with the posting layer set as <STRONG>Tax</STRONG>.</P>



1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  Create or select a value model.
    

    > [!NOTE]
    > <P>For more information about value models, see <A href="ind-set-up-parameters-to-define-a-depreciation-threshold.md">(IND) Set up parameters to define a depreciation threshold</A>.</P>



3.  Select **Tax** in the **Posting layer** field.

4.  Click the **General** tab.

5.  Select the **Allow net book value higher than the acquisition cost** check box and the **Allow negative net book value** check box, if required.
    

    > [!NOTE]
    > <P>The term net book value here refers to the net book value of the whole fixed asset group.</P>



6.  Click **Fixed asset groups** to open the **Fixed asset group/value model** form.

7.  Select the fixed asset group to attach to the value model.

8.  Select the **Asset group depreciation** check box to apply asset group depreciation for the fixed asset group that is attached to the value model.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Asset group depreciation</STRONG> check box for a fixed asset group that is attached to a value model, it is selected automatically in the other forms for that value model.</P>



9.  Click **Bonus depreciation** and enter the bonus depreciation details for fixed assets that are purchased and put to use during the year.

10. Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>You can enter bonus depreciation details only for the value model that is attached to the fixed asset group with Tax as the posting layer.</P>



## See also

[(IND) Attach fixed asset numbers to fixed asset groups and value models](ind-attach-fixed-asset-numbers-to-fixed-asset-groups-and-value-models.md)

[(IND) Fixed asset group/ Value model (modified form)](https://technet.microsoft.com/en-us/library/jj664616\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

