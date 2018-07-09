---
title: (BRA) Generate the Sintegra tax statement
TOCTitle: (BRA) Generate the Sintegra tax statement
ms:assetid: 5c0d1297-5624-4523-83e8-ef9f6f24e939
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn600274(v=AX.60)
ms:contentKeyID: 62200236
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- forms.FBBookingPeriodListPage_BR
---

# (BRA) Generate the Sintegra tax statement [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to generate a Sintegra tax statement in a text file by using the **Booking period** list page. The Sintegra text file provides information about fiscal documents that have been received and issued each month. This information is used by tax authorities. The Sintegra text file also includes information about tax payments during the month.


> [!NOTE]
> <P>Before you can generate the Sintegra tax file, you must select the check box next to <STRONG>Sintegra</STRONG> in the <STRONG>Tax statements</STRONG> form.</P>



## Generate the Sintegra tax statement in a text file

To generate the Sintegra tax statement in a text file, follow these steps:

1.  Click **Fiscal books** \> **Common** \> **Booking period**. On the **Action pane**, click the **Tax statements** tab.

2.  Select a booking period, and then click **Sintegra**.

3.  Specify the location and name of the file. The default location is specified in the **Sintegra parameters** form, and the default file name is automatically generated. In most cases, you should accept the default entry.

4.  Select the version of the Sintegra text file to generate. For Microsoft Dynamics AX 2012 R3, only **Version 3 – ICMS 73/03** is supported.

5.  Select either **Normal** or **Substitute** for the file type.

6.  Select the operation from the following options:
    
      - **All** – Generate one Sintegra text file for all states.
    
      - **Interstate** – Generate one Sintegra text file for a specific state.
    
      - **Interstate – all states** – Generate one Sintegra text file for each state.

7.  In the **State** field, select the state that the Sintegra text file is for. This field is available if **Interstate** is selected in the **Operations** field.

8.  Enter the location where the Sintegra text file will be generated. This field is available if **Interstate – all states** is selected in the **Operations** field.

9.  Select the **Inventory records** check box to generate records 74 and 75 to include the inventory position.

10. Select the reference month and the reference year of the inventory position.

11. Optional: Click the **Batch** tab and specify options for batch processing. You might use batch processing if the file should be generated later or on a server instead of on your computer.

12. Click **OK** to generate the Sintegra text file.

## See also

[(BRA) Set up parameters for Sintegra tax statements](bra-set-up-parameters-for-sintegra-tax-statements.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

