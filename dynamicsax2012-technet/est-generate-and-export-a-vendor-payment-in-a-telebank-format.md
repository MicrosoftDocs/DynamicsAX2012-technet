---
title: (EST) Generate and export a vendor payment in a telebank format
TOCTitle: (EST) Generate and export a vendor payment in a telebank format
ms:assetid: b5ba5bcc-614a-4f65-a993-c66f40dbbe28
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664187(v=AX.60)
ms:contentKeyID: 49385277
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Estonia
---

# (EST) Generate and export a vendor payment in a telebank format 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you set up the export of telebank payments to vendors, you can generate and export a payment to a vendor by using the telebank format.

For more information, see [(EST) Set up the export of telebank payments to vendors](est-set-up-the-export-of-telebank-payments-to-vendors.md).

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **New** to create a payment journal, and then enter the required details.

3.  Click **Lines** to open the **Journal voucher** form.

4.  Click **Functions** \> **Generate payments**.

5.  In the **Generate payments** form, select the **Export format** field, and then select an export format. The following file formats are available for telebanking:
    
      - **Teleteenus (EE) v. 2.3**
    
      - **Telehansa (EE) v. 5.116**
    
      - **Telehansa (INT) v. 5.116**

6.  Select a bank account.

7.  To view the payment format before you generate payments, select the **Show format dialog** check box.

8.  Click **Dialog** to open a form where you can select the file to export. The name of this form depends on the selection in the **Export format** field.
    

    > [!TIP]
    > <P>You can also click the browse button, select the file path, and then enter the name.</P>



9.  Depending on the form that opens, enter information in the following fields:
    
      - **Payment priority**
    
      - **Transfer costs**
    
      - **File name**

10. Click **OK** to export payments.

## See also

[(EST) Set up the export of telebank payments to vendors](est-set-up-the-export-of-telebank-payments-to-vendors.md)

  


