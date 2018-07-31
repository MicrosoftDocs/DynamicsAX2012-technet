---
title: Set up functionality profiles (Retail essentials)
TOCTitle: Set up functionality profiles (Retail essentials)
ms:assetid: 6dc377d8-a0f6-40fe-a884-dac0d2497de2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736887(v=AX.60)
ms:contentKeyID: 62200365
ms.date: 08/15/2014
mtps_version: v=AX.60
f1_keywords:
- 54dcb5e1-c519-4446-a883-faff1493436f
---

# Set up functionality profiles (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up functionality profiles. You can use the settings in these profiles to specify how registers work at the point of sale. For example, you can specify how cashiers log on and off the register, specify information about secondary currencies, control the aggregation of products and payments, specify info codes, and enable X and Z reports.

After the functionality profile is set up, you can assign it to one or more stores.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Set up functionality profiles

Use this procedure to set up the functionality profiles for a register.

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Functionality profiles**.

2.  In the **POS functionality profile** form, click **New** to create a new profile. To modify an existing profile, select the profile.

3.  In the **Profile** field, enter an identifier for the profile, and then enter a description.

4.  On the **General** FastTab, in the **ISO** field, select the locale for the store. Be sure to select the correct locale. An incorrect locale can adversely affect posting and tax calculation.

5.  On the **Functions** FastTab, select how the workers use the POS system, how the registers function, and how POS transactions are saved. You also select the level of event logging that is written to the POSIsLog table in the database for the store or register.

6.  On the **Amount** FastTab, select the **Apply discounts to unit price** check box to apply item discounts to each unit of an item when multiple units are included in a single transaction line.

7.  On the **Info codes** FastTab, select the info codes that cashiers see during specific tasks.
    
    You can select an info code to prompt the cashier to either enter a value or select a subcode when they open the register till by using the open drawer operation.

8.  On the **Receipt numbering** FastTab, enter the formats for receipt numbers in the store.
    

    > [!TIP]
    > <P><STRONG>SSSS</STRONG> is the store number and <STRONG>TTTT</STRONG> is the register number.</P>



## Assign a functionality profile to a store

Use this procedure to assign a functionality profile to a store.

1.  Click **Retail essentials** \> **Channels** \> **Retail stores**.

2.  On the **Retail stores** list page, double-click a store in the list.

3.  In the **Stores** form, on the **General** FastTab, in the **POS terminal** group, in the **Functionality profile** field, select a functionality profile.

## See also

[Setting up profiles (Retail essentials)](setting-up-profiles-retail-essentials.md)

[Setting up Retail POS (Retail essentials)](setting-up-retail-pos-retail-essentials.md)

  


