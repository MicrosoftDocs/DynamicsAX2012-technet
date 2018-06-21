---
title: (BEL) Generate and upload payments by using Generic ISO20022 credit transfers
TOCTitle: (BEL) Generate and upload payments by using Generic ISO20022 credit transfers
ms:assetid: c01357bc-32c3-436e-97c7-367a88e8ed56
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500669(v=AX.60)
ms:contentKeyID: 37822158
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BEL) Generate and upload payments by using Generic ISO20022 credit transfers [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Single Euro Payment Area (SEPA) is an initiative that provides a common electronic banking process for transferring payments within the SEPA region, which is comprised of 32 countries. In Belgium, SEPA credit transfers have been extended and standardized to also support non-SEPA credit transfers called Generic ISO20022 credit transfers. This format is applied to payments if they are made in a currency other than euros and to payments that are made to companies outside the SEPA region. The generated payment files can be uploaded by using Client Isabel Synchronizer (CIS).

## Set up a method of payment for Generic ISO20022 credit transfers

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a new method of payment for Generic ISO20022 credit transfers.

3.  In the **Method of payment** field, enter an appropriate identifier, such as **Generic ISO 20022 CredTrans BE**, to make payments by using Generic ISO20022 credit transfers.

4.  Enter other information for the method of payment, as needed.

5.  Click the **File formats** FastTab, and then in the **Export format** field, select **Generic ISO 20022 CredTrans BE** to make payments by using Generic ISO20022 credit transfers.
    

    > [!NOTE]
    > <P>If the <STRONG>Export format</STRONG> field list is empty, click <STRONG>Setup</STRONG>, and then select one of the available formats.</P>



6.  Close the form.

## Create a payment journal for Generic ISO20022 credit transfers

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new journal, and then click **Lines** to open the **Journal voucher** form.

3.  Enter the required details for the journal line. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

4.  In the **Offset account** field, select the offset bank account.

5.  Click the **Bank** tab, and then in the **Account identification** field, select the third-party bank account.

6.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

7.  In the **Method of payment** field, select the required method of payment.

8.  In the **Bank account** field, select the offset bank account to filter the vendor transaction lines of payment.

9.  Select the **Show format dialog** check box, and then click **OK** to display the **Microsoft Dynamics AX** payment format dialog box.

10. In the **Processing date** field, enter the date when the bank should initiate the payments.

11. In the **Remittance Information** field, select one of the following options:
    
      - **Structured** – Generate structured remittance information for each payment.
    
      - **Unstructured** – Generate unstructured remittance information for each payment.
        

        > [!NOTE]
        > <P>To make sure that a new line is inserted into the IBS log in the <STRONG>IBS transactions</STRONG> form for each payment file, set the <STRONG>Upload mode</STRONG> field to <STRONG>Attended mode</STRONG> in the <STRONG>IBS parameters</STRONG> form. You must also select the <STRONG>IBS integration</STRONG> check box in the <STRONG>Microsoft Dynamics AX</STRONG> payment format dialog box.</P>



12. In the **Amount limit** field, enter the maximum transaction amount allowed per line.

13. In the **File name** field, enter the file path and name of the payment file.

14. Click **OK** to generate the payment file. The payment files are saved in the path specified in the **Upload folder** field of the **IBS parameters** form.

## Upload a Generic ISO20022 credit transfer initiation file

1.  Click **Cash and bank management** \> **Common** \> **IBS transactions**.

2.  In the **IBS transactions** form, select the vendor payment transaction line to upload.

3.  Click **Upload** to electronically send the Generic ISO20022 initiation file to the bank.

4.  Close the form.

## See also

[(BEL) About CIS](bel-about-cis.md)

[(BEL) Generate customer payment files and upload them using CIS](bel-generate-customer-payment-files-and-upload-them-using-cis.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

