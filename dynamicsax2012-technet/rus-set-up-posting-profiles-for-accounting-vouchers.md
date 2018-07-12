---
title: (RUS) Set up posting profiles for accounting vouchers
TOCTitle: (RUS) Set up posting profiles for accounting vouchers
ms:assetid: fb18ed81-c0a3-4178-a760-b0209e0c957d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678654(v=AX.60)
ms:contentKeyID: 49388136
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up posting profiles for accounting vouchers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the following posting profiles for an account of operations:


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



  - One ledger account for all advance holders.

  - A separate ledger account for each group of advance holders.

  - A separate ledger account for each advance holder.

<!-- end list -->

1.  Click **Accounts payable** \> **Setup** \> **Advance holders** \> **Employee posting profiles**.

2.  Click the **Overview** tab, and press CTRL+N.

3.  In the **Posting profile** field, enter the profile ID of the profile being processed.

4.  In the **Description** field, enter the description of the posting profile.

5.  Click the **Ledger accounts** tab.

6.  In the **Valid for** field, select the level of grouping for setting up the posting profile from the following options:
    
      - **Table** – This option is set for only one advance holder.
    
      - **Group** – This option is set for a group of advance holders.
    
      - **All** – This option is set for all advance holders.

7.  In the **Reference** field, select the corresponding reference.
    

    > [!NOTE]
    > <P>You can select this field only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Valid for</STRONG> field.</P>



8.  In the **Summary account** field, select the account to reflect transactions for the advance holders.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Advance holders (form)](https://technet.microsoft.com/en-us/library/jj665294\(v=ax.60\))

  


