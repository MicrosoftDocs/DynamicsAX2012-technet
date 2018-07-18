---
title: (RUS) Set up folders to save exported electronic documents to and store the statuses of reports
TOCTitle: (RUS) Set up folders to save exported electronic documents to and store the statuses of reports
ms:assetid: 2c1afc6c-083c-42ca-a569-4e88cd683248
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ735278(v=AX.60)
ms:contentKeyID: 49693279
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up folders to save exported electronic documents to and store the statuses of reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you export electronic documents, you must set up company information in the **Legal entities** form. For more information, see [(RUS) Legal entities (modified form)](https://technet.microsoft.com/en-us/library/jj711352\(v=ax.60\)).

After you set up company information, you can set up a folder in which to save electronic documents that must be exported to the reporting authorities. The documents that you save in this folder are validated and then sent to the reporting authorities for approval.

You can also set up a folder in which to save documents that contain information about status updates for the electronic documents that are exported. The status of the documents is updated based on the approval of the reporting authorities.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Configurations**.

2.  In the **Configuration of electronic document sending service** form, click the **General** tab.

3.  In the **Outbound folder** field, specify a path to use to save and export electronic documents.
    

    > [!NOTE]
    > <P>The documents must be saved in an XML format. For more information, see <A href="rus-about-the-transfer-and-maintenance-of-electronic-documents.md">(RUS) About the transfer and maintenance of electronic documents</A>.</P>



4.  In the **Inbound folder** field, specify a path to use to save documents that contain status update information about the electronic documents that are exported.

## See also

[(RUS) Configuration of electronic document sending (form)](https://technet.microsoft.com/en-us/library/jj852144\(v=ax.60\))

  


