---
title: Set up and assign functionality profiles
TOCTitle: Set up and assign functionality profiles
ms:assetid: f49978f8-42da-4298-aeba-3ee8cb522840
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597281(v=AX.60)
ms:contentKeyID: 39519365
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- functionality profile
- functionality profiles
---

# Set up and assign functionality profiles 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use a functionality profile to configure the point of sale (POS) functionality for all registers in a store. The settings in a functionality profile put limits on staff logons, specify information about secondary currencies, control the aggregation of products and payments, specify reason codes, enable X and Z reports, and so on.

After the functionality profile is set up, you can assign it to one or more stores.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## Set up functionality profiles

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Functionality profiles**.

2.  In the **POS functionality profile** form, click **New** to create a new profile. To modify an existing profile, select the profile.

3.  In the **Profile** field, enter an identifier for the profile, and then enter a description.

4.  On the **General** FastTab, in the **ISO** field, select the locale for the store. Be sure to select the correct locale. An incorrect locale can adversely affect posting and tax calculation.

5.  On the **Functions** FastTab, select how the workers use the POS system, how the registers function, and how POS transactions are saved. You also select the level of event logging that is written to the POSIsLog table in the database for the store or register.

6.  Depending on your version of the product, on the **Amount** FastTab, do one of the following:
    
      - In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: Select the **Apply discounts to unit price** check box to apply item discounts to each unit of an item when multiple units are included in a single transaction line.
    
      - Otherwise: Enter the maximum amounts for transaction prices and quantities.

7.  On the **Info codes** FastTab, select the info codes that cashiers see during specific tasks.
    
    In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: You can select an info code to prompt the cashier to either enter a value or select a subcode when they open the register till by using the open drawer operation.

8.  On the **Receipt numbering** FastTab, enter the formats for receipt numbers in the store.
    

    > [!TIP]
    > <P><STRONG>SSSS</STRONG> is the store number and <STRONG>TTTT</STRONG> is the register number.</P>



## Assign a functionality profile to a store

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  On the **Retail stores** list page, double-click a store in the list.

3.  In the **Stores** form, on the **General** FastTab, in the **POS terminal** group, in the **Functionality profile** field, select a functionality profile.

## See also

[POS functionality profile (form)](https://technet.microsoft.com/en-us/library/hh597181\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

