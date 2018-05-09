---
title: (RUS) Set up customer posting profiles for dimensions control for settlements
TOCTitle: (RUS) Set up customer posting profiles for dimensions control for settlements
ms:assetid: eb446466-ca2b-49ce-abca-b7d2ba4e0385
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711731(v=AX.60)
ms:contentKeyID: 49388054
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Set up
- customer posting profiles
- (RUS)
- dimensions control for settlements
---

# (RUS) Set up customer posting profiles for dimensions control for settlements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up customer posting profiles for dimension control for settlements by using the **Customer posting profiles** form. For required groups or for a customer, you must specify a dimension set for dimension control. You must also include empty values at settlement control for the posting profile.

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Press CTRL+N to create a new customer posting profile, and then enter the required details. For more information, see [Customer posting profiles (form)](https://technet.microsoft.com/en-us/library/aa600572\(v=ax.60\)).

3.  Click the **Table restrictions** FastTab.

4.  In the **Allow empty dimension value** field, select the condition under which customer transaction settlements can be processed if dimension values are not specified. The following options are available:
    
      - **No** – Transactions are not settled, whether the dimension values are specified or not.
    
      - **Auto** - Automatic transactions are settled, whether the dimension values are specified or not.
    
      - **Manual** – Manual transactions are settled, whether the dimension values are specified or not.
    
      - **Always** – All transactions are settled, whether the dimension values are specified or not.
    

    > [!NOTE]
    > <P>This parameter lets you ignore the setting of dimensions when individual transactions are created.</P>



5.  Click the **Setup** FastTab.

6.  In the **Set** field, select the dimension set for settlement control.
    

    > [!NOTE]
    > <P>The specified dimension set indicates that dimension control is activated.</P>



## See also

[(RUS) Set up vendor posting profiles for dimensions control for settlements](rus-set-up-vendor-posting-profiles-for-dimensions-control-for-settlements.md)

[(RUS) Customer posting profiles (modified form)](https://technet.microsoft.com/en-us/library/jj678641\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

