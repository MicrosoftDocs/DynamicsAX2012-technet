---
title: (BRA) Set up an electronic method of payment
TOCTitle: (BRA) Set up an electronic method of payment
ms:assetid: ec40f383-4e19-4288-8896-c9eb0c9e5152
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ730980(v=AX.60)
ms:contentKeyID: 49675211
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Configurable layout file
- Export layout group
- Return layout group
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up an electronic method of payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up electronic methods of payment that are used to make vendor payments or receive customer payments.

Before you set up the electronic methods of payment for vendors or customers, you must set up a configurator layout group for the file layout that is used for the electronic method of payment. For more information, see [(BRA) Set up the configurator layout group](bra-set-up-the-configurator-layout-group.md)

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.
    
    –or–
    
    Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create an electronic method of payment for vendors or customers.

3.  In the **Method of payment** and **Description** fields, enter an identification code and a description for the method of payment.

4.  In the **Period** field, select **Invoice** to set up a payment transfer for customer or vendor invoices. Each invoice is settled with only one payment.

5.  In the **Payment type** field, select **Electronic payment**.

6.  On the **File formats** FastTab, in the **Export format** field, select **Configurable layout file** as the format for the export files.
    

    > [!NOTE]
    > <P>If the <STRONG>Configurable layout file</STRONG> format is not available in the <STRONG>Export format</STRONG> field, click <STRONG>Setup</STRONG> to open the <STRONG>File formats for methods of payment</STRONG> form. On the <STRONG>Export</STRONG> tab, move the <STRONG>Configurable layout file</STRONG> format from the <STRONG>Available</STRONG> list to the <STRONG>Selected</STRONG> list. Close the form.</P>



7.  In the **Export layout group** field, select a layout group for the export files.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Configurable layout file</STRONG> in the <STRONG>Export format</STRONG> field.</P>



8.  In the **Return format** field, select **Configurable layout file** as the format for the return files.
    

    > [!NOTE]
    > <P>If the <STRONG>Configurable layout file</STRONG> format is not available in the <STRONG>Return format</STRONG> field, click <STRONG>Setup</STRONG> to open the <STRONG>File formats for methods of payment</STRONG> form. On the <STRONG>Return</STRONG> tab, move the <STRONG>Configurable layout file</STRONG> format from the <STRONG>Available</STRONG> list to the <STRONG>Selected</STRONG> list. Close the form.</P>



9.  In the **Return layout group** field, select a layout group for the return files.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Configurable layout file</STRONG> in the <STRONG>Return format</STRONG> field.</P>



10. On the **General** FastTab, in the **Account type** field, select **Bank**.

11. In the **Payment account** field, select the bank account number.

12. Click **Payment specification** to open the **Payment specification** form, where you can create a payment specification for the method of payment. For more information, see [(BRA) Vendor payment specification (modified form)](https://technet.microsoft.com/en-us/library/jj730978\(v=ax.60\)) and [(BRA) Customer payment specification (modified form)](https://technet.microsoft.com/en-us/library/jj730984\(v=ax.60\)).
    

    > [!NOTE]
    > <P>If the electronic method of payment uses complex file layouts, specify the payment type, payment way, and segments in the <STRONG>Payment type</STRONG>, <STRONG>Payment way</STRONG>, <STRONG>Segment</STRONG>, <STRONG>Remittance segment</STRONG>, and <STRONG>Return segment</STRONG> fields.</P>



## See also

[(BRA) Set up the configurator definition group](bra-set-up-the-configurator-definition-group.md)

[(BRA) Methods of payment - customers (modified form)](https://technet.microsoft.com/en-us/library/jj730974\(v=ax.60\))

  


