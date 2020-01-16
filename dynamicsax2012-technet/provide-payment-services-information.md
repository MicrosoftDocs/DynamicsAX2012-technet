---
title: Provide payment services information
TOCTitle: Provide payment services information
ms:assetid: 1bb6cdb7-76f9-484c-8fe8-bafca56fd12d
ms:mtpsurl: https://technet.microsoft.com/library/JJ720351(v=AX.60)
ms:contentKeyID: 49721146
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Provide payment services information 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Provide information about the Payment Services for Microsoft Dynamics ERP account that you use to process credit cards and debit cards in Microsoft Dynamics AX 2009.


> [!IMPORTANT]
> <P>This task appears in the <STRONG>Preprocessing upgrade checklist</STRONG> if you have installed the upgradeAX50.xpo file and enabled the credit card configuration key. However, the information requested by the <STRONG>Enter payment services information</STRONG> form is needed only if you are using Payment Services for Microsoft Dynamics ERP on Microsoft Dynamics AX 2009. If you are not using Payment Services for Microsoft Dynamics ERP, you can immediately click <STRONG>Set to ready for upgrade</STRONG> on the form to mark the task complete.</P>
> <P>If you are using Payment Services for Microsoft Dynamics ERP, the information you need to complete the form must be obtained from the Payment Services for Microsoft Dynamics ERP section of your Dynamics Online account.</P>



If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

1.  In the **Partition key** field, select a partition for preprocessing.

2.  In the **Enter payment services information** form, select a company account in the list. If no companies are displayed in the form, click **Set to ready for upgrade** to complete this task.

3.  In the **Service account ID** field, enter the service account ID that you obtained as described above.

4.  In the **Public key** field, enter your public key.

5.  In the **Private key** field, enter your private key.

6.  In the **Password** field, enter your password.

7.  Repeat steps 1 through 5 for each company account in the list.

8.  After you finish entering the information for each company account, click **Set to ready for upgrade** to complete this step and close the form.

  


