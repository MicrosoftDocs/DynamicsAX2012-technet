---
title: (RUS) Set up an object information register for fixed assets
TOCTitle: (RUS) Set up an object information register for fixed assets
ms:assetid: 2acd9f2d-1c50-4626-992f-05eaafaf950b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665228(v=AX.60)
ms:contentKeyID: 49387317
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up an object information register for fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **FA - information about object**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Click the **Parameters** to set up additional parameters for the register.

10. In the **Parameter name** field, select the parameter.

11. In the **Value** field, select the fixed asset group by the tax account type and asset type that are to be used to create the register. If you specify more than one value, separate the values with commas.
    

    > [!NOTE]
    > <P>If you do not specify parameter values, the register will contain all fixed assets.</P>



12. Click **Specific** to open the **Expense code setup** form, and then set up expense and revenue codes for the register.

13. Click the **General tab**, and, in the **Fixed assets type** field, select the asset type from the following options:
    
      - **Use for production**
    
      - **Don't use for production**

14. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Expense code setup (form)](https://technet.microsoft.com/en-us/library/jj839690\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

