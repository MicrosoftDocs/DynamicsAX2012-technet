---
title: (JPN) Configure for bill of exchange upgrade
TOCTitle: (JPN) Configure for bill of exchange upgrade
ms:assetid: 4cb380d8-be1e-4c21-8838-da0d6feaf934
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ714191(v=AX.60)
ms:contentKeyID: 49651300
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (JPN) Configure for bill of exchange upgrade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2012 R2 simplifies how bills of exchange are endorsed. The **Preprocessing upgrade checklist** task **Configure for bill of exchange upgrade** opens a form with the same name that allows you to configure certain financial transactions affected by upgrade.

## Changes to bill of exchange (BOE) support

A bill of exchange is endorsed by a company to a vendor with which it has a business relationship. During data upgrade preprocessing, in the **Accounts receivable parameters** form, on the **Settlement** tab, the **Allow endorsement of BOE** check box will appear selected. During data upgrade on the target system, the upgrade framework makes the following changes to a bill of exchange:

  - It generates the bill of exchange transaction for the credit side.

  - It generates the payment journal transaction for the debit side.

  - It updates the bill of exchange with a status of **Endorsed**.

For each company on the source system, you must specify the following information.

  - The number sequence to use for bills of exchange.

  - A bridge account for the transactions that are created on the target system.


> [!NOTE]
> <P>The configuration for the bill of exchange upgrade for each partition. In Microsoft Dynamics AX 2012 R2, each company is contained in a partition. Each system has at least one default partition, which is named <STRONG>Initial</STRONG>. If you create additional partitions during the <STRONG>Configure partitions</STRONG> step of the <STRONG>Preprocessing upgrade checklist</STRONG>, you must configure the companies in each partition.</P>



## Configure bill of exchange upgrade

Click the **Configure for bill of exchange upgrade** task to open the **Configure for bill of exchange upgrade** form. On the form, specify the number sequence and bridge account for bills of exchange for each company as follows.

1.  In the **Configure for bill of exchange upgrade** form, in the **Partition** field, select a partition.

2.  For each company in the partition, in the **Endorsed bill of exchange voucher** field, select the number sequence for bills of exchange.

3.  For each company in the partition, in the **Endorse account** field, select the bridge account for transactions.

4.  Repeat steps 1 to 3 for each partition.

5.  When you have finished, click **Set to ready for upgrade**.

## See also

[(JPN) Configure for bill of exchange upgrade (form)](https://technet.microsoft.com/en-us/library/jj713625\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

