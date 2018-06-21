---
title: (IND) Set up withholding tax components for TCS tax types
TOCTitle: (IND) Set up withholding tax components for TCS tax types
ms:assetid: e4f9829d-34f3-4093-a11c-36e85d269d78
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710886(v=AX.60)
ms:contentKeyID: 49386299
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Set up withholding tax components for TCS tax types [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The different TCS components are TCS, surcharge, E-cess, and SHE- cess. You can also define the threshold limit and exception threshold limit to calculate TCS for the TCS component.


> [!NOTE]
> <P>Threshold limit and exception threshold limit are not applicable for TCS. However, you can define the threshold limit and exception threshold limit for TCS components.</P>



1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **India** \> **Withholding tax components**.

2.  Select **TCS** in the **Tax type** field.

3.  Press CTRL+N to create a new line.

4.  Enter the TCS component name in the **Withholding tax component** field and a description in the **Description** field.

5.  In the **Withholding tax component group** field, select the TCS withholding tax component group to attach the TCS component to.

## Define the threshold limit

1.  Click **Threshold** on the **Withholding tax components** form to open the **Threshold** form.

2.  Select the period range that the threshold limit is applied for in the date fields.

3.  Enter the threshold amount limit to calculate TCS for the TCS component in the **Threshold** field. The tax is collected at the source only when the cumulative invoice amount has crossed the threshold limit.
    
    For example, if the threshold limit is 10000, the TCS is calculated after the cumulative invoice amount is 10001 or more.

4.  Enter the exception threshold amount limit in the **Exception threshold** field. The tax is collected at the source on an invoice line if the amount has crossed the exception threshold limit.
    
    For example, if the exception threshold limit is 5000, the TCS is calculated on a specific invoice line if the invoice line amount is 5001 or more.
    

    > [!NOTE]
    > <P>The exception threshold amount must be less than or equal to the threshold amount. The TCS is calculated for a transaction if the transaction amount crosses the exception threshold limit, even if the cumulative invoice amount does not cross the threshold limit specified in the <STRONG>Threshold</STRONG> field.</P>



5.  Close the **Threshold** form to return to the **Withholding tax components** form.

## Copy TCS components to another TCS component group

1.  Click **Copy** on the **Withholding tax components** form to open the **Copy withholding tax components** form, where you can copy the TCS components that are set up for a TCS component group to another TCS component group.

2.  Select the TCS component group to copy the TCS components from in the **From** field. Select the withholding tax component group to copy the TCS components to in the **To** field.
    

    > [!NOTE]
    > <P>The common TCS components that are attached to both the TCS component groups are not copied.</P>



3.  Click **OK** to copy and create TCS components for the other TCS component group in the **Withholding tax components** form.

4.  Press CTRL+S or close the form.

## See also

[(IND) Threshold (form)](https://technet.microsoft.com/en-us/library/jj677862\(v=ax.60\))

[(IND) Withholding tax components (form)](https://technet.microsoft.com/en-us/library/jj664790\(v=ax.60\))

[(IND) Copy withholding tax components (form)](https://technet.microsoft.com/en-us/library/jj678010\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

