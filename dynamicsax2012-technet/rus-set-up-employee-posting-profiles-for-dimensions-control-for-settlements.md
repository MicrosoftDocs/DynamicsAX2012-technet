---
title: (RUS) Set up employee posting profiles for dimensions control for settlements
TOCTitle: (RUS) Set up employee posting profiles for dimensions control for settlements
ms:assetid: a1416fea-1f0a-4290-b97d-cdd569d9b5db
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678545(v=AX.60)
ms:contentKeyID: 49387774
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Set up
- (RUS)
- dimensions control for settlements
- employee posting profiles
---

# (RUS) Set up employee posting profiles for dimensions control for settlements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up employee posting profiles for dimension control for settlements by using the **Employee posting profiles** form. Set up advance holder posting profiles for accruals and closing payment operations. These posting profiles can be adjusted for advance holder operation of payments and debts by using a dimension set for control for settlements.

1.  Click **Accounts payable** \> **Setup** \> **Advance holders** \> **Employee posting profiles**.

2.  Create a new employee posting profile. For more information, see [(RUS) Set up posting profiles for accounting vouchers](rus-set-up-posting-profiles-for-accounting-vouchers.md).

3.  Click the **Table restrictions** FastTab.

4.  In the **Allow empty dimension value** field, select the condition under which settlements that are related to accruals and closing payment operations can be processed if dimension values are not specified. The following options are available:
    
      - **No** – Transactions are not settled, whether the dimension values are specified or not.
    
      - **Auto** - Automatic transactions are settled, whether the dimension values are specified or not.
    
      - **Manual** – Manual transactions are settled, whether the dimension values are specified or not.
    
      - **Always** – All transactions are settled, whether the dimension values are specified or not.
    

    > [!NOTE]
    > <P>This parameter lets you ignore the setting of dimensions when individual transactions are created.</P>



5.  Click the **Setup** FastTab.

6.  In the **Set** field, select the dimension focus for settlement control.
    

    > [!NOTE]
    > <P>The specified dimension set indicates that dimension control is activated.</P>



## See also

[(RUS) Set up customer posting profiles for dimensions control for settlements](rus-set-up-customer-posting-profiles-for-dimensions-control-for-settlements.md)

[(RUS) Employee posting profiles (form)](https://technet.microsoft.com/en-us/library/jj733181\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

