---
title: (RUS) Update the system register for electronic reporting
TOCTitle: (RUS) Update the system register for electronic reporting
ms:assetid: 398e591d-6bf4-438b-8ab2-a877abe15182
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ894654(v=AX.60)
ms:contentKeyID: 52075366
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- electronic reporting
- dynamic section
- excel sheet
audience: Application User
ms.search.region: Russia
---

# (RUS) Update the system register for electronic reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

By default, in the **Requisites setup** form, the Microsoft Excel template opens in a new window. To set up requisites, the Excel template must be opened in the lower pane of the **Requisites setup** form. You must update the system register to open the Excel template in the lower pane of the form.

Use the following procedure to update the system register on a computer that is running Windows Server 2008.

1.  Click **Start** \> **Run**.

2.  Enter regedit, and then click **OK**.

3.  Expand the **HKEY\_CLASSES\_ROOT** folder, and then select the **Excel.Sheet.12** folder.

4.  In the right pane, right-click **BrowserFlags**, and then click **Modify**.

5.  In the **Value data** field, enter 0.

6.  Click **OK**.

7.  In the left pane, select the **Excel.Sheet.8**, **Excel.SheetBinaryMacroEnabled.12**, **Excel.SheetMacroEnabled.12**, **Excel.Template**, and **Excel.Template.8** folders, and then repeat steps 4 through 6 for each folder.

## See also

[(RUS) Requisites setup (form)](https://technet.microsoft.com/en-us/library/jj710719\(v=ax.60\))

  


