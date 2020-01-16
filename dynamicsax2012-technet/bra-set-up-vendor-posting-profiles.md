---
title: (BRA) Set up vendor posting profiles
TOCTitle: (BRA) Set up vendor posting profiles
ms:assetid: 8b3906c5-b101-4c2b-9941-073c4f8d041d
ms:mtpsurl: https://technet.microsoft.com/library/JJ710560(v=AX.60)
ms:contentKeyID: 49384450
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- posting profiles
- BRA
- Brazil
- vendor posting profiles
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up vendor posting profiles 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Vendor posting profiles** form to specify an account to credit the Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax amount to. You can apply a vendor posting profile to a single vendor, a group of vendors, or all vendors.

1.  Click **Accounts payable** \> **Setup** \> **Vendor posting profiles**.

2.  Create a vendor posting profile.

3.  In the **Posting profile** and **Description** fields, enter a name and a description for the posting profile.

4.  Click the **Setup** FastTab, and then in the **Account code** field, select an account code from the following options:
    
      - **Table** – The posting profile is for a specific vendor.
    
      - **Group** – The posting profile is for a specific vendor group.
    
      - **All** – The posting profile is for all vendors.

5.  In the **Account/Group number** field, select a vendor account or vendor group.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Account code</STRONG> field.</P>



6.  In the **Tax transfer** field, select an account to credit the ICMS tax amount to.

## See also

[Vendor posting profiles (form)](https://technet.microsoft.com/library/aa551972\(v=ax.60\))

[(BRA) Vendor posting profiles (modified form)](https://technet.microsoft.com/library/jj710579\(v=ax.60\))

  


