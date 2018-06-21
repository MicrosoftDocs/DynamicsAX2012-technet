---
title: (DNK) Set up a method of payment to pay vendors through Nordea Bank
TOCTitle: (DNK) Set up a method of payment to pay vendors through Nordea Bank
ms:assetid: 3e236bff-8718-4cf7-9c57-59aa9beec100
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ928493(v=AX.60)
ms:contentKeyID: 52075219
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (DNK) Set up a method of payment to pay vendors through Nordea Bank [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Methods of payment - vendors** form to set up a method of payment that uses the **Nordea Unitel for PC (DK)** file format for electronic payments. You can make electronic payments to vendors using Nordea Bank if you have an account at the bank. Nordea Bank accepts electronic payments only in the **Nordea Unitel for PC (DK)** file format.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a method of payment.

3.  In the **Method of payment** field, enter a unique identification code for the Nordea Bank payment format.

4.  In the **Payment type** field, select **Electronic payment**.

5.  On the **File formats** FastTab, in the **Export format** field, select **Nordea Unitel for PC (DK)**.
    

    > [!NOTE]
    > <P>If the <STRONG>Nordea Unitel for PC (DK)</STRONG> format is not available in the <STRONG>Export format</STRONG> field, click <STRONG>Setup</STRONG> to open the <STRONG>File formats for methods of payment</STRONG> form. On the <STRONG>Export</STRONG> tab, move <STRONG>Nordea Unitel for PC (DK)</STRONG> from the <STRONG>Available</STRONG> list to the <STRONG>Selected</STRONG> list. Close the form.</P>



6.  Click **Payment specification**, and then in the **Payment specification** and **Description** fields, enter a unique identification code and a description for the payment specification.

7.  In the **Export format** field, select **Nordea intercompany payment**.

## See also

[Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\))

[Vendor payment specification (form)](https://technet.microsoft.com/en-us/library/aa554108\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

