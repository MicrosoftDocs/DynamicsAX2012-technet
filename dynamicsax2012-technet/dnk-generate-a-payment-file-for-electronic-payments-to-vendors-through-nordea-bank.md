---
title: (DNK) Generate a payment file for electronic payments to vendors through Nordea Bank
TOCTitle: (DNK) Generate a payment file for electronic payments to vendors through Nordea Bank
ms:assetid: 48207cb8-f2fa-4bfa-a082-e165921d6af1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ913180(v=AX.60)
ms:contentKeyID: 52075220
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (DNK) Generate a payment file for electronic payments to vendors through Nordea Bank 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Generate payments** form to generate a payment file in the **Nordea Unitel for PC (DK)** file format. You can export vendor payment details to this file. One payment file can have a maximum of 1,200 payments. If there are more than 1,200 payments, an additional file is generated for the remaining payments. The name of the additional file is the same as the initial file, but it is suffixed with “\_n” where “n” is the number of the iteration. An empty file is generated when there are no payments.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a payment journal, and then in the **Name** field, select a journal name. Click **Lines**.
    
    –or–
    
    Select an existing journal, and then click **Lines**.

3.  Select a journal line, and then in the **Method of payment** field, select the method of payment that is set up for electronic payments through Nordea Bank. The **Payment specification** field is updated with the payment specification code that is set up for the selected method of payment.

4.  Click the **Bank** tab, and then in the **Account identification** field, select the vendor bank account to which the payment is made through Nordea Bank.

5.  Click **Functions** \> **Generate payments**.

6.  In the **Method of payment** field, select the method of payment that is set up for electronic payments through Nordea Bank.
    
    –or–
    
    In the **Export format** field, select **Nordea Unitel for PC (DK)**.

7.  In the **Bank account** field, select a Danish bank account.

8.  Select the **Show format dialog** check box, and then click **OK**.

9.  In the **Batch entry number** and **Transfer type** fields, enter the three-digit batch entry number that is specified in the account statement and the three-digit transfer type code that is specified by Nordea Bank.

10. In the **File name** field, enter the path and name of the payment file.

11. Select the **Control report** check box to print a control report.
    

    > [!NOTE]
    > <P>Click <STRONG>Control report</STRONG> to set up the printer to print the payment file.</P>



12. Click **OK** to generate the payment file in the **Nordea Unitel for PC (DK)** file format.

## See also

[Generate payments - vendor (class form)](https://technet.microsoft.com/en-us/library/aa586980\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

