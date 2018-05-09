---
title: Define auto charges
TOCTitle: Define auto charges
ms:assetid: a249cab0-9405-4807-85f4-7473ddde3791
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571826(v=AX.60)
ms:contentKeyID: 49684853
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- automatic
- auto charge
- auto charges
---

# Define auto charges 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to define automatic charges for vendors, customers, or items. You might apply charges automatically to a sales order or a purchase order, if, for example, a vendor or customer is located outside a specific vicinity.

Automatic charges, which are referred to as auto charges, are applied automatically when you create a sales order or purchase order. You can define auto charges for specific vendors, customers, or items or for groups of vendors, customers, or items. You can also define auto charges that apply to all vendors, customers, or items.

In Microsoft Dynamics AX 2012 R2, you can also define auto charges for modes of delivery for sales orders.

The actions that are available from the **Auto charges** form depend on where you access the form from. Some of the steps described in this topic might not apply to your specific task. For example, steps that refer to modes of delivery can be performed only when you define auto charges for sales orders.

1.  Click **Accounts receivable** \> **Setup** \> **Charges** \> **Auto charges**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Setup** \> **Charges** \> **Automatic charges**.
    
    –or–
    
    Click **Retail** \> **Setup** \> **Charges** \> **Auto charges**.
    

    > [!NOTE]
    > <P>You can open the <STRONG>Auto charges</STRONG> form from Retail only if Microsoft Dynamics AX 2012 R2 is installed.</P>



2.  Click **New** to define a new auto charge.

3.  In the **Level** field, select the level to apply the auto charge to from the following values:
    
      - **Main** – Apply charges to the order header.
    
      - **Line** – Apply charges to the order lines.

4.  Select an account in the **Account code** field from the following values:
    
      - **Table** – Assign charges to a specific customer or vendor.
    
      - **Group** – Assign charges to a miscellaneous charges group.
    
      - **All** – Assign charges to all customers or vendors.

5.  In the **Customer relation** or **Vendor relation** field, select a specific customer or vendor if you selected **Table**, or select a customer or vendor charges group if you selected **Group**.

6.  In the **Item code** field, select an item code. You can select an item code only when you define auto charges at the lines level.
    
      - **Table** – Assign charges to a specific item.
    
      - **Group** – Assign charges to an item charges group.
    
      - **All** – Assign charges to all items.

7.  In the **Item relation** field, select a specific item if you selected **Table**, or select an item charges group if you selected **Group**.

8.  In the **Mode of delivery code** field, select a mode of delivery code.
    
      - **Table** – Assign charges to a specific mode of delivery.
    
      - **Group** – Assign charges to a mode of delivery group.
    
      - **All** – Assign charges to all modes of delivery.
    

    > [!NOTE]
    > <P>This field is available only if Microsoft Dynamics AX 2012 R2 is installed.</P>



9.  In the **Mode of delivery relation** field, select a specific mode of delivery if you selected **Table**, or select a mode of delivery charges group if you selected **Group**.
    

    > [!NOTE]
    > <P>This field is available only if Microsoft Dynamics AX 2012 R2 is installed.</P>



10. Expand the **Lines** FastTab to define the charges and the charges rates to use when the current auto charge is applied.

11. In the **Currency** field, select the currency to use to calculate the charge.

12. In the **Charges code** field, select the code for the charge.

13. Specify how to calculate the charge in the **Category** field and enter a value in the **Charges value** field.
    
      - **Fixed** – The charge is entered as a fixed amount on the line. Fixed charges can be used on charges in the order header and on the order lines.
    
      - **Pcs.** – The charge is based on the unit. These charges can be used only on order lines.
    
      - **Percent** – The charge is entered as a percentage on the line. Percentage charges can be used on charges in the order header and on the order lines.
    
      - **Intercompany percent** – The charge is entered as a percentage on the line for intercompany orders. Intercompany percentage charges can be used only on order lines.
    
      - **External** – The charge is calculated by a third-party service that is associated with one or more shipping carriers.
    
    If you are validating charges for Accounts payable, and if the charges are calculated as a fixed amount instead of a percentage, this value must be less than the maximum amount that is specified in the **Charges code** form.

14. In the **Charges currency code** field, specify a currency for the charge to use a different currency than is specified in the **Currency** field. This is possible if the **Debit** or **Credit** type is either **Ledger account** or **Item** for the selected charges code.

15. Specify a starting amount to apply the auto charge to in the **From amount** field. In the **To amount** field, specify the ending amount to apply the auto charge to. Amount in this context refers to the order total. To define tiered charges, you can specify a from amount and a to amount only if you define auto charges at the main level and if the category is **Fixed** or **Percent**.
    

    > [!NOTE]
    > <P>The <STRONG>From amount</STRONG> and <STRONG>To amount</STRONG> fields are available only if Microsoft Dynamics AX 2012 R2 is installed, and only when you define auto charges for sales orders. For more information, see <A href="about-tiered-charges-on-sales-orders.md">About tiered charges on sales orders</A>.</P>



16. Optional: In the **Sales tax group** field, specify a sales tax group.

17. Select the **Keep** check box to keep the charges transactions after invoicing, so that the charge is applied every time that you create a new invoice for the selected customer account.

## Examples

**Example 1**

To assign a freight charge automatically to customers or vendors who are located outside a specific vicinity:

1.  Create a customer or vendor charges group by using the **Charges groups** form, for example Freight.

2.  Create an auto charge at the main level with an **Account code** of **Group** and the **Customer relation** or **Vendor relation** of Freight.

3.  On the **Lines** tab, specify the charges code and the freight charge.

**Example 2**

To assign a packing fee automatically to all customers or vendors that buy or sell items that require special packing:

1.  Create an item charges group, for example Fragile, in the **Item charges groups** form.

2.  Create an auto charge at the line level. First, select **Line** in the **Level** field. Then, in the **Account code** field, select **All**. In the **Item code** field, select **Group** and then select Fragile in the **Item relation** field.

3.  On the **Lines** tab, specify the charges code and the charges value.

**Example 3**

To assign a delivery fee to orders delivered by air using tiered charges:

1.  Create an auto charge at the main level. In the **Account code** field, select **Table** and then select a customer in the **Customer relation** field.

2.  In the **Mode of delivery code** field, select **Table**, and then select **Air** in the **Mode of delivery relation** field.

3.  On the **Lines** tab, select a currency of **USD**, and specify the charges code. Select a category of either **Fixed** or **Percent** and enter a charges value.

4.  To apply the auto charge whenever the order total is over USD 100, in the **From amount** field, enter 100.


> [!NOTE]
> <P>You can define auto charges for modes of delivery using tiered charges only if Microsoft Dynamics AX 2012 R2 is installed, and only when you define charges for sales orders.</P>



## See also

[Auto charges (form)](https://technet.microsoft.com/en-us/library/aa582856\(v=ax.60\))

[Charges groups (form)](https://technet.microsoft.com/en-us/library/aa617452\(v=ax.60\))

[Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\))

[About tiered charges on sales orders](about-tiered-charges-on-sales-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

