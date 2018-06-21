---
title: (IND) Create a primary EPCG license
TOCTitle: (IND) Create a primary EPCG license
ms:assetid: 538a841e-a3e3-4511-9e24-36bf38c31061
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677815(v=AX.60)
ms:contentKeyID: 49385779
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- EXIM
- EPCG license
- EXIM EPCG scheme
- create EXIM EPCG scheme
- primary EPCG license
---

# (IND) Create a primary EPCG license [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **EXIM EPCG Schemes** form to create a primary Export Promotion Capital Goods (EPCG) license. After the details are updated, you can submit the data to the customs authority. The customs authority verifies the data and provides an EPCG license number.


> [!NOTE]
> <P>This procedure can be completed only if the <STRONG>Export Promotion Capital Goods</STRONG> check box is selected in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



1.  Click **General ledger** \> **Common** \> **EXIM EPCG Schemes**. On the **Action Pane**, in the **New** group, click **EXIM EPCG Schemes**.

2.  In the **EXIM EPCG Schemes** form, click **New**.
    
    The **ID** field is filled in automatically, based on the number sequence that is selected in **Number sequences** area in the **Incentive scheme parameters** form. The **Date/time** field displays the current date and time, and the **Status** field displays **Created**.

3.  In the **Port ID** field, select an EXIM port.

4.  In the **Authorization basis** field, select **Primary**.

5.  Press CTRL+S to save the line, and then click **Importable Items**.

6.  In the **Importable Items** form, in the **Item number** field, select the identification number of the importable item. The description of the selected item is displayed in the **Product name** field.

7.  In the **Unit** field, select the unit of measure of the importable item.

8.  In the **Installation certificate number** field, enter the installation certificate number for the importable item.

9.  In the **Certificate date/time** field, specify the date and time on which the installation certificate becomes valid.

10. On the **General** FastTab, in the **Text** field, enter information about the import.

11. Press CTRL+S, and then close the **Importable Items** form.

## See also

[(IND) Approve an EPCG license](ind-approve-an-epcg-license.md)

[(IND) Create an EXIM EPCG scheme for a technology upgrade EPCG license](ind-create-an-exim-epcg-scheme-for-a-technology-upgrade-epcg-license.md)

[(IND) Extend the export obligation period for an EPCG license](ind-extend-the-export-obligation-period-for-an-epcg-license.md)

[(IND) Revalidate an EPCG license for domestic purchasing](ind-revalidate-an-epcg-license-for-domestic-purchasing.md)

[(IND) Redeem an EPCG license](ind-redeem-an-epcg-license.md)

[(IND) Merge EPCG licenses](ind-merge-epcg-licenses.md)

[(IND) EXIM EPCG schemes (form)](https://technet.microsoft.com/en-us/library/jj677817\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

