---
title: (HUN) Create a customer payment transfer
TOCTitle: (HUN) Create a customer payment transfer
ms:assetid: 7169d037-c9f0-4be1-8d0a-1a593dbbb515
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664307(v=AX.60)
ms:contentKeyID: 49385396
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HUN) Create a customer payment transfer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can define an export file format when you set up a payment method. When you transfer payments from customers, the export file is generated for all payment lines that use HUF (Hungarian Forint) currency in the correct format.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new line.
    

    > [!NOTE]
    > <P>For more information, see "Journal header (form)" in the Application and Business Processes Help.</P>



3.  Click **Lines** to open the **Journal voucher** form.

4.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

5.  In the **Export format** field, select **MCash (HU).**

6.  In the **Bank account** field, select the bank account for payment.

7.  Click **Dialog** to open the **MCash (HU)** form, and then select the domestic currency in the **Currency** field.

8.  In the **Processing date** field, select the processing date for payment.

9.  In the **File name** field, select the file name for the payment file.

10. Click **OK** to close the dialog window.

11. Click **OK** to generate the payment file.
    

    > [!NOTE]
    > <P>The export file will be created with a "ung" file name extension. The export file will contain only the payment vouchers with a positive credit amount in domestic (HUF) currency.</P>



## See also

[(EEUR) Invoice register journal lines (modified form)](https://technet.microsoft.com/en-us/library/jj730992\(v=ax.60\))

[(HUN) Create a single vendor payment transfer](hun-create-a-single-vendor-payment-transfer.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

