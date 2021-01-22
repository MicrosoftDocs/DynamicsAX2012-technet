---
title: Create mail merge files
TOCTitle: Create mail merge files
ms:assetid: d35a02c6-6a25-4dee-a6d7-018fcec89c1b
ms:mtpsurl: https://technet.microsoft.com/library/Aa551065(v=AX.60)
ms:contentKeyID: 36059509
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create mail merge files 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a mail merge file in two ways. You can base the mail merge file on an existing mailing list, or you can base it on prospects and contacts.

## Create a mail merge file based on an existing mailing list

When you create a mail merge file based on an existing mailing list, all records that have a status of **Not sent** in the **Mailings** form are sent to the mail merge file. Therefore, you cannot use the **Mailings** form for long-term storage of mailing lists that have a status of **Not sent**.

1.  Click **Sales and marketing** \> **Periodic** \> **Mailings** \> **Mailings**.

2.  Click **Create mailing file**.

3.  Enter the full location of the mail merge file as the file name.

4.  Select the **Update status** check box to update the status, date, and history of the mailing. The status is changed from **Not sent** to **Sent**.

5.  Select the date on which you want to send the mailing.


> [!NOTE]
> <P>Only mailing lists that have a status of <STRONG>Not sent</STRONG> are updated to a status of <STRONG>Sent</STRONG> when the check box is selected.</P>



## Create a mail merge file based on prospects and contacts

You can create a mail merge file by filtering the **Prospects** and **Contacts** tables.

1.  Click **Sales and marketing** \> **Periodic** \> **Mailings** \> **Create mailing file**.

2.  Specify the full location of the mail merge file.

3.  Select the **Update status** check box to update the status of the mailing list in the **Prospects** form.

4.  Select the date on which you want to send the mailing.
    
    If you select the **Update status** check box, the **Date sent** value is registered in both the **Prospects** and the **Contacts** forms.

5.  Click **Select**. Then, in the **Mailing file query** form, change, add, or remove filter fields as necessary.

6.  Click **OK** to accept the query and the values in the filter fields.

7.  Click **OK** to generate the mail merge file in the location that you specified.

  


