---
title: (BRA) Set up a check or Bordero method of payment for a vendor
TOCTitle: (BRA) Set up a check or Bordero method of payment for a vendor
ms:assetid: 4730fee7-3d4d-46c7-8814-5c3097a5bb00
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ910985(v=AX.60)
ms:contentKeyID: 53382663
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) Set up a check or Bordero method of payment for a vendor [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a check or Bordero method of payment to make payments to vendors. You can create a method of payment for checks that generates one check for a combination of a specific payment date, a vendor, and a bank, or that generates one check for a specific payment date for each bank. For a Bordero method of payment, one Bordero payment is generated for a specific payment date for each bank.

## Set up a method of payment for checks

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a method of payment for checks.

3.  In the **Method of payment** field, enter an identification code for the method of payment.

4.  In the **Period** field, select **Total**.

5.  In the **Description** field, enter a description for the method of payment.

6.  In the **Payment type** field, select **Check**.

7.  On the **File formats** FastTab, in the **Export format** field, select **Check** as the export format for the method of payment.
    

    > [!NOTE]
    > <P>If the <STRONG>Check</STRONG> format is not available in the <STRONG>Export format</STRONG> field, click <STRONG>Setup</STRONG> to open the <STRONG>File formats for methods of payment</STRONG> form. On the <STRONG>Export</STRONG> tab, move <STRONG>Check</STRONG> from the <STRONG>Available</STRONG> list to the <STRONG>Selected</STRONG> list. Close the form.</P>



8.  On the **Payment control** FastTab, select the **Enabled** check box for **Check number is mandatory** and **Offset account has the type bank**.

9.  On the **General** FastTab, in the **Account type** field, select **Bank**.

10. In the **Posting level** field, select one of the following options to indicate the level of posting for the check or Bordero payment:
    
      - **Vendor** – One check is created for a combination of a specific payment date, a vendor, and a bank.
    
      - **Bank** – One check or Bordero is created for a specific payment date for each bank.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Total</STRONG> in the <STRONG>Period</STRONG> field.</P>



## Set up a method of payment for Bordero

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a method of payment for a Bordero.

3.  In the **Method of payment** field, enter an identification code for the method of payment.

4.  In the **Period** field, select **Total**.

5.  In the **Description** field, enter a description for the method of payment.

6.  On the **File formats** FastTab, in the **Export format** field, select **Borderô (BR)** as the export format for the method of payment.
    

    > [!NOTE]
    > <P>If the <STRONG>Borderô (BR)</STRONG> format is not available in the <STRONG>Export format</STRONG> field, click <STRONG>Setup</STRONG> to open the <STRONG>File formats for methods of payment</STRONG> form. On the <STRONG>Export</STRONG> tab, move <STRONG>Borderô (BR)</STRONG> from the <STRONG>Available</STRONG> list to the <STRONG>Selected</STRONG> list. Close the form.</P>



7.  On the **General** FastTab, in the **Account type** field, select **Bank**.

8.  In the **Posting level** field, select **Bank** to generate one Bordero for a specific payment date for each bank.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Total</STRONG> in the <STRONG>Period</STRONG> field.</P>



## See also

[(BRA) Methods of payment - vendors (modified form)](https://technet.microsoft.com/en-us/library/jj923217\(v=ax.60\))

[(BRA) Post a payment with the Bordero method of payment and generate the Bordero report](bra-post-a-payment-with-the-bordero-method-of-payment-and-generate-the-bordero-report.md)

[(BRA) Post a payment with the check method of payment](bra-post-a-payment-with-the-check-method-of-payment.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

