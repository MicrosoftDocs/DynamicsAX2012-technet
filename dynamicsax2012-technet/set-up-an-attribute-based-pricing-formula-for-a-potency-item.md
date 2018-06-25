---
title: Set up an attribute-based pricing formula for a potency item
TOCTitle: Set up an attribute-based pricing formula for a potency item
ms:assetid: b409f4ff-b29e-45a3-be5f-0b7345e8a63f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838747(v=AX.60)
ms:contentKeyID: 50120630
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up an attribute-based pricing formula for a potency item [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up a batch attribute-based pricing formula for a potency item. You can create an identifier (ID) for advanced pricing with calculation equations that change the purchase price paid for the potency item.

1.  Click **Procurement and sourcing** \> **Setup** \> **Price/discount** \> **Attribute-based pricing details**.

2.  Click **New** to create a pricing formula line.

3.  In the **Attribute-based pricing ID** field, enter an identification code for the attribute-based pricing formula.

4.  On the **Equation** FastTab, in the **Equation** field, enter the equation for the advanced pricing formula. This equation calculates the purchase price of a potency item.

5.  Click **Validate equation** to validate the equation.

6.  On the **Elements** FastTab, click **Add variable** to add an equation variable.

7.  In the **Equation element** field, enter the equation element that identifies a set of values that are used in the equation. Use only alphabetical characters for the equation element.

8.  In the **Equation element type** field, select the type of equation element from the following options:
    
      - **Purchase receipt quantity** ─ The received quantity of the potency item.
    
      - **Purchase price** ─ The purchase price of the potency item.
    
      - **Batch attribute – Actual** ─ The actual percentage of potency for an inventory batch.
    
      - **Constant** ─ The standard percentage of potency for an inventory batch.
    
      - **Select the element type** ─ The default value for the type of equation element.
    
      - **Batch attribute – Target** ─ The target percentage of potency for an inventory batch.

9.  In the **Attribute** field, select the value of the batch attribute for the calculation.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Batch attribute – Actual</STRONG> or <STRONG>Batch attribute – Target</STRONG> in the <STRONG>Equation element type</STRONG> field.</P>



10. In the **Constant** field, enter the constant value or quantity value that is used for the calculation.

## See also

[Attribute-based pricing data (form)](https://technet.microsoft.com/en-us/library/jj838766\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

