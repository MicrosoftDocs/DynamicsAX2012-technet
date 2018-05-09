---
title: (IND) Set up withholding tax codes for TCS tax types
TOCTitle: (IND) Set up withholding tax codes for TCS tax types
ms:assetid: a90e64ed-ed62-491a-817a-53b7354cbb3f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664778(v=AX.60)
ms:contentKeyID: 49386113
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Set up withholding tax codes for TCS tax types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

2.  Press CTRL+N to create a withholding tax code for Tax Collected at Source (TCS) and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa585361(v=ax.60)">Withholding tax codes (form)</A>.</P>



3.  On the **General** FastTab, select **TCS** in the **Tax type** field to categorize the tax code as the TCS tax code.

4.  Select the payable ledger account to post the TCS amount to in the **Main account** field.

5.  Select the TCS settlement period for the TCS tax code in the **Settlement period** field.

6.  Select the receivable account to post the TCS amount collected in purchase transactions in the **Receivable account** field.

7.  **Percentage of gross amount** is displayed in the **Origin** field and cannot be changed.
    

    > [!NOTE]
    > <P>You cannot set the origin to <STRONG>Percentage of net amount</STRONG> for the TCS tax type.</P>



8.  Select the TCS tax component for the TCS tax code in the **Withholding tax component** field.

9.  Click **Values** to open the **Withholding tax values** form. Enter the starting date and the ending date for the TCS value in the **From date** and the **To date** fields.
    

    > [!NOTE]
    > <P>The <STRONG>Minimum limit</STRONG> field, the <STRONG>Upper limit</STRONG> field, and the <STRONG>Exclude %</STRONG> field are not available for tax codes with the TCS tax type. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa615586(v=ax.60)">Withholding tax values (form)</A>.</P>



10. Enter the percentage of TCS for the TCS tax code in the **Value** field.

11. Press CTRL+S or close the **Withholding tax values** form and return to the **Withholding tax codes** form.
    

    > [!NOTE]
    > <P>The <STRONG>Limits</STRONG> button is not available for the TCS tax type. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa615586(v=ax.60)">Withholding tax values (form)</A>.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## See also

[(IND) Withholding tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj664629\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

