---
title: (SGP) Set up tax groups for GST reporting
TOCTitle: (SGP) Set up tax groups for GST reporting
ms:assetid: a13bbcb0-d21c-44a7-bca7-8b6466ca1cc3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213387(v=AX.60)
ms:contentKeyID: 36058781
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (SGP) Set up tax groups for GST reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Sales tax groups** form to set up sales tax groups. The sales tax groups are assigned to companies, and taxes are calculated based on the tax codes that are in effect when transactions occur. For Singapore, set up at least the following three tax groups:

  - **GST** – Use this group for companies that are subject to standard tax.

  - **Exempt** – Use this group for companies that provide certain financial services or the sale and lease of residential properties. Sales tax is not charged for these types of supplies.

  - **Zero-rated** – Use this group for companies that have special trade agreements. The export of goods and the provision of international services are zero-rated supplies.

<!-- end list -->

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Press CTRL+N to create a new sales tax group.

3.  In the **Sales tax group** field, enter a name, such as GST, and then enter general information about the sales tax group.

4.  Click the **Setup** tab. Press CTRL+N.

5.  In the **Sales tax code** field, select a sales tax code to add to the sales tax group.

6.  Repeat steps 2 through 5 to set up additional sales tax groups.

7.  Close the form to save your changes.

## See also

[(SGP) Set up tax codes for GST reporting](sgp-set-up-tax-codes-for-gst-reporting.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

