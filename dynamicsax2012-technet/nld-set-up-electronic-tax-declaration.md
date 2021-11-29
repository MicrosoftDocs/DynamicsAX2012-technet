---
title: (NLD) Set up electronic tax declaration
TOCTitle: (NLD) Set up electronic tax declaration
ms:assetid: 2f44db86-7c87-4257-964e-29621a33d647
ms:mtpsurl: https://technet.microsoft.com/library/Gg231023(v=AX.60)
ms:contentKeyID: 36056296
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Netherlands
---

# (NLD) Set up electronic tax declaration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Companies in the Netherlands must submit a turnover statement that shows Value Added Taxes (VAT), sales tax and turnover tax-Omzet Belasting (OB), and their Intracommunautaire Prestaties (ICP) tax declaration to the Dutch tax authorities electronically.

Use the **Electronic tax declaration parameters** form to set up electronic tax declaration information.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Netherlands** \> **Electronic tax declaration parameters**.

2.  Select the VAT contact-person type in the **VAT contact type** field and ICP contact-person type in the **ICP contact type** field, and enter additional contact information.

3.  In the **SEB ID**, **SEB name**, and **SEB telephone** fields, enter the service bureau ID, name, and telephone number.

4.  On the **BAPI** (Business Application Programming Interface) link, enter the time-out limit in minutes, and select the work folder and log-file folder.

5.  In the **Process ID sender** field, enter the process identification of the person who is sending the file.

6.  On the **E-mail** link, enter the appropriate e-mail addresses and the incoming and outgoing server names.

7.  On the **Certificates** link, enter the Lightweight Directory Assistance Protocol (LDAP) server name and the certificate information.

8.  On the **Number sequences** link, you can assign a number sequence to each reference.

9.  Close the form to save your changes.

## See also

[(NLD) Set up electronic tax error messages](nld-set-up-electronic-tax-error-messages.md)

[(NLD) Create, send, and import the OB tax declaration electronically](nld-create-send-and-import-the-ob-tax-declaration-electronically.md)

[(NLD) Create, send, and import the ICP tax declaration electronically](nld-create-send-and-import-the-icp-tax-declaration-electronically.md)

[(NLD) Electronic tax declaration parameters (form)](https://technet.microsoft.com/library/aa582881\(v=ax.60\))

  


