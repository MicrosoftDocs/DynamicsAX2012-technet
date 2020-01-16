---
title: (RUS) Set up parameters for incoming VAT processing
TOCTitle: (RUS) Set up parameters for incoming VAT processing
ms:assetid: af6d2760-d487-478d-ab2d-5411cf6f01e9
ms:mtpsurl: https://technet.microsoft.com/library/JJ711515(v=AX.60)
ms:contentKeyID: 49387840
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up parameters for incoming VAT processing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Parameters of VAT process** form to set up parameters for incoming value-added tax (VAT) processing and for restored VAT transactions.

1.  Click **Accounts payable** \> **Periodic** \> **Purchase book** \> **Parameters of VAT process**.

2.  Click **New** to create a parameter for the VAT process.

3.  In the **VAT operation code** field, enter the operation code for incoming VAT processing.

4.  In the **Operation type** field, select the operation type for incoming VAT processing. Select one of the following options:
    
      - **Standard** – Process the incoming VAT. This operation type is used if the VAT restoration journal is not approved during the reporting period.
    
      - **VAT 0% confirmation** – Process the incoming VAT after export confirmation. This operation type is used if there is an approved VAT restoration journal in the reporting period.

5.  In the **Description** field, enter a description of the new parameter for VAT process.

6.  Select the **By default** check box to determine the default operation code for the selected operation type.

7.  Select the **Include in book** check box to include the specified operation in the sales book.

8.  Select the **Default dimension** check box to use the dimensions values from the transaction and overwrite the dimensions value that is set in the **Financial dimensions** form.

9.  Click the **Setup** FastTab, and then in the **Account code** field, select from the following options:
    
      - **Table** – The sales tax code that is attached to the incoming VAT transaction.
    
      - **Group** – The sales tax group that is attached to a group of incoming VAT transactions.
    
      - **All** – The sales tax code that is attached to all incoming VAT transactions.

10. In the **Account/Group number** field, select the sales tax code or group for the incoming VAT transaction.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Account code</STRONG> field.</P>



11. In the **Main account** field, select the ledger account number to post incoming VAT processing transactions.

12. In the **Offset account** field, select the ledger account number to post incoming VAT processing transactions.

## See also

[(RUS) Perform an outgoing VAT processing transaction](rus-perform-an-outgoing-vat-processing-transaction.md)

  


