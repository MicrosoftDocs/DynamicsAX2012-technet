---
title: Set up subcodes
TOCTitle: Set up subcodes
ms:assetid: 75cac481-bf0f-4032-a6e2-1492b46f90ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597130(v=AX.60)
ms:contentKeyID: 39519184
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up subcodes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to set up an info code so that multiple subcodes are displayed either in a list or as buttons. A subcode triggers specific actions. The actions depend on the info code that the subcode is assigned to. A subcode is commonly used to present the point of sale (POS) operator with a list of available responses. For example, you can set up a subcode to remind staff to check age requirements.

You can create and modify subcodes. The actions that are triggered by a subcode depend on the criteria that you enter for the subcode.


> [!NOTE]
> <P>In versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3, info codes in Retail were called reason codes. This topic refers to info codes, but the information also pertains to Retail reason codes in earlier versions of AX 2012, unless otherwise indicated.</P>



1.  Click **Retail** \> **Setup** \> **Info codes**.

2.  In the **Info codes** form, in the left pane, select an info code that has an input type of **Subcode buttons** or **Subcode list**, and then click **Subcodes**.

3.  In the **Information subcodes** form, click **New** to create a new subcode.

4.  In the **Subcode number** field, enter an identification number for the subcode.

5.  In the **Trigger function** field, select whether a product or a discount group triggers the action. Then, in the **Trigger code** field, enter a product number or discount group.

6.  In the **Price type** field, select whether the type of price that is charged originates from a product, a designated price, or a price that is reduced by a discount percentage.

7.  In the **Amount / percent** field, enter the amount that is charged for the product that is specified in the **Trigger code** field. Alternatively, if the price that is used at the point of sale reflects a price reduction, enter the percentage by which the price of the product is reduced.

8.  In AX 2012 R3 with Retail: Click **Translations**. In the **Text translation** form, enter the translated text for subcodes in additional languages. The translated text is displayed on the register at the point of sale.

## See also

[Set up info codes](set-up-info-codes.md)

[Information subcodes (form)](https://technet.microsoft.com/en-us/library/hh580645\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

