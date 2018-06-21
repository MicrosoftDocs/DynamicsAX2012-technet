---
title: Example of a count unit for time and attendance
TOCTitle: Example of a count unit for time and attendance
ms:assetid: 3a3991d1-19b4-4813-82df-74a44999ae9f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242213(v=AX.60)
ms:contentKeyID: 36056639
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Example of a count unit for time and attendance [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an example of how you can use count units in a pay agreement for time and attendance.

## Count unit setup on a production operation

In the production department of a company, a special operation is performed, which is very strenuous on the workers. Consequently, the production manager decides that a worker must not work on that particular operation for more than maximum 10 hours per week.

The workers who work on the special operation receive a bonus. The bonus is paid per hour and can be paid for minimum one hour and maximum 10 hours per week.

## Set up a pay type

The company creates a special pay type that functions as a bonus for work on the operation. The bonus is added as a **Premiums** wage type on a pay agreement line for the pay agreement.

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Pay types**.

2.  Create a pay type named Operation bonus 05.

3.  Click **Rates** to open the **Rates** form. Use this form to set up the amount to pay for the bonus.

4.  Optional: You can set up the rate to be valid for a limited period of time.

## Set up a count unit on a pay agreement

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Pay agreements**.

2.  Select the pay agreement, and click **Count unit**.
    
      - In the **Description** field, insert a description of the count unit.
        

        > [!NOTE]
        > <P>The <STRONG>Count unit</STRONG> field is automatically filled out with sequential numbers.</P>

    
      - In the **Minimum**, insert the number 0 (zero).
    
      - In the **Maximum**, insert the number 10.
    
      - In the **Wage type** field, select **Premiums**.
    
      - In the **Pay type out** field, select **Premiums**, or another pay type to be displayed on the payroll records.
        

        > [!NOTE]
        > <P>This may be relevant if you want to display a different <STRONG>Wage type</STRONG> in the payroll records that are created.</P>

    
      - In the **Period code** field, select the weekly pay period that the count unit relates to.

3.  In the **Pay agreements** form, click **Pay agreement lines**.

4.  Create a new pay agreement line for the relevant week days for the **Premiums** pay type.

5.  Select the pay type that you created earlier.

6.  On the **General** tab, in the **Count unit** field, select the count unit that you created in step 2.

7.  In the **Operation** field, select the operation that the count unit relates to.


> [!NOTE]
> <P>If this count unit should be available for a specific work time profile only, select the profile in the <STRONG>Profile type</STRONG> field on the pay agreement line. This means that only workers connected to that profile can receive the operation bonus.</P>



## See also

[About pay adjustments and count units](about-pay-adjustments-and-count-units.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

