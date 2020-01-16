---
title: (JPN) Generate payments with JBA export format
TOCTitle: (JPN) Generate payments with JBA export format
ms:assetid: 8a654e80-4304-4ca7-a84c-88675a84a335
ms:mtpsurl: https://technet.microsoft.com/library/JJ711088(v=AX.60)
ms:contentKeyID: 49386497
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- JP - 00009
audience: Application User
ms.search.region: Japan
---

# (JPN) Generate payments with JBA export format 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **Lines** to open the **Journal voucher** form.

3.  Press CTRL+N to create a new line and enter the required details.

4.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

5.  Select **Export format**. Select the **JBA(JP)** export format in the **Export format** field.

6.  Select the **Show format dialog** check box.

7.  Click **OK** to create the export file. You must specify the path when you use the payment format for the first time.
    
    The exported file name takes the following format: FilenameYYYYMMDD\_1 when the file is exported with a date. The file that is exported without a specified date takes the following format: Filename\_1.
    
    The file with the next date is exported in the following format: FilenameYYYYMMDD\_2.
    
    A file that is exported using the same date and name overwrites the file that was exported earlier.

## See also

[(JPN) Define the JBA export format for a method of payment](jpn-define-the-jba-export-format-for-a-method-of-payment.md)

  


