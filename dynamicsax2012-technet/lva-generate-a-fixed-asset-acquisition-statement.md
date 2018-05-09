---
title: (LVA) Generate a fixed asset acquisition statement
TOCTitle: (LVA) Generate a fixed asset acquisition statement
ms:assetid: ab3eaf3b-675d-4a01-8ee4-fc223df9e549
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853413(v=AX.60)
ms:contentKeyID: 50396782
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LVA) Generate a fixed asset acquisition statement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The fixed asset acquisition statement is a list of all fixed assets acquired during a specified period.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Press CTRL+N to create a new line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see the section "Journal header (form)" in the Applications and Business Processes Help.</P>



3.  Click **Lines** to open the **Journal voucher** form.

4.  Press CTRL+N to create a new line, and enter the required details to acquire a fixed asset.
    

    > [!NOTE]
    > <P>For more information, see the section "Fixed assets journal lines (form)" in the Applications and Business Processes Help.</P>



5.  In the **Transaction type** field, select **Acquisition**.

6.  In the **Document** field, enter the number of the document that the voucher was generated from.

7.  Click **Post** \> **Post** to post the journal.

8.  Press CTRL+S or close the form.

9.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

10. Select the value model and click **Value models** \> **Transactions** to open the **Fixed asset transactions** form.

11. Select the transaction and click **Print** \> **Fixed asset Acquisition Statement** option to open the **Fixed asset Acquisition Statement** report.

12. In the **Document number** field, enter the document number to be printed in the report.

13. In the **Document date** field, select the date of the document.

14. Click **OK** to generate the **Fixed asset Acquisition Statement** report.

## See also

[Value models (form)](https://technet.microsoft.com/en-us/library/aa590830\(v=ax.60\))

[Journal voucher - Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620564\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

