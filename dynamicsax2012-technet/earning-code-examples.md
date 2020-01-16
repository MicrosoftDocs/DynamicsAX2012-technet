---
title: Earning code examples
TOCTitle: Earning code examples
ms:assetid: 826c594e-8d18-4264-99c4-082bdffcc180
ms:mtpsurl: https://technet.microsoft.com/library/JJ677346(v=AX.60)
ms:contentKeyID: 49384120
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- earning codes
- Earning code examples
- earning code
- overtime earning code
- overtime earning codes
- premium
- Premium earning code
- premium earning codes
- premiums
- regular rate of pay earning code
- regular rate of pay earning codes
- retroactive earning code
- retroactive earning codes
audience: Application User
ms.search.region: USA
---

# Earning code examples 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can refer to the following earning code examples when you create earning codes. You should create a unique earning code for each type of earning that your organization offers. When you generate earnings, earning lines using the appropriate earning codes are automatically added to the earnings statements so that you don’t have to enter each line manually. However, you can still make changes, if you need to.

It is common to have many more earning codes than are described in the following examples. For instance, you might also create earning codes for sick leave, vacation pay, jury duty, and bonuses. You can create as many earning codes as you need to, based on earnings types.

When earnings are generated, the fixed compensation plan that is assigned to a worker is used to determine the earning amounts unless the earning code has a flat amount rate basis. For more information about how the rate basis selection affects the earnings calculations, see [Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md).

## What do you want to do?

Learn more about...

Example: Create a base pay earning code for hourly workers

Example: Create a bonus earning code

Example: Create a gross up earning code

Example: Create a retroactive earning code

Example: Create a fringe benefit earning code

Example: Create an earning code for overtime premiums

Example: Create an earning code for premiums that are controlled by premium earning policies

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md)

[Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md)

[Generate earnings](generate-earnings.md)

## Example: Create a base pay earning code for hourly workers

Set up a base pay earning code for hourly workers. We recommend that this earning code be used for both regular and overtime hours. The earning codes for overtime premium amounts are described in “Example: Create an earning code for overtime premiums” later in this topic.

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Click **New**.

3.  Enter a name and description for the earning code.

4.  In the **Include in payment run type** field, select **Primary and additional**.
    

    > [!NOTE]
    > <P>Even though the payment run will typically be a primary run for this kind of earning code, we recommend that you select <STRONG>Primary and additional</STRONG> so that you have the flexibility to use the earning code multiple times in one payment run.</P>



5.  In the **Tax method** field, select **Regular** to indicate that the taxes will be calculated using the standard rate.

6.  Enter the information in the following fields, which work together to determine an earnings amount:
    
      - **Rate basis** – Select **Hourly**.
    
      - **Unit of measure** – Select **Hours**.
    
      - **Amount or multiplier** – Enter 1.

7.  On the **Accounting** tab, click **Add** to add a line to the table.

8.  Select a default main account. Leave the **Department**, **Job**, and **Worker** fields blank, unless you want to restrict the use of the earning code.

Back to top

## Example: Create a bonus earning code

Create a 1,000.00 bonus that is taxed on a supplemental basis and that will be generated only in **Additional** payment runs.

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Click **New**.

3.  Enter a name and description for the earning code.

4.  In the **Include in payment run type** field, select **Additional**.

5.  In the **Tax method** field, select **Supplemental** to indicate that the taxes will be calculated by using the supplemental tax rate tables.

6.  Enter information in the following fields, which work together to determine an earnings amount:
    
      - **Rate basis** – Select **Flat amount**.
    
      - **Unit of measure** – Select **Each**.
    
      - **Amount or multiplier** – Enter 1000.

7.  On the **Accounting** tab, click **Add** to add a line to the table.

8.  Select a default main account. Leave the **Department**, **Job**, and **Worker** fields blank, unless you want to restrict the use of the earning code.

Back to top

## Example: Create a gross up earning code

Gross up earning codes are used when workers receive a specific, additional amount in their paychecks after taxes. An example might be a car payment or relocation expense.

These two earning codes are required for each gross up earning:

  - **Main earning code** – An earning code that is manually added to a worker’s earnings statement when the worker has earnings that are to be grossed up. Each main earning code has **Gross up** selected in the **Include in payment run type** field, and specifies a secondary earning code in the **Gross up earning code** field. When the main earning code is included in a gross up payment run, additional earnings are generated to make sure that the worker receives the specified amount after all taxes are withheld.

  - **Secondary earning code** – The earning code that is used for the additional earnings that cover the amount of taxes related to the main earning code. Each secondary earning code has **Automatic** selected in the **Include in payment run type** field. The additional earnings are calculated and a line using the secondary earning code is added to the worker’s pay statement automatically in a gross up payment run. Because this code is referenced by the main earning code, it must be created first.
    
    To assign a secondary earning code to a main earning code, there are several values that must be the same for both earning codes. These are discussed in the sections later in this topic.

In the following example, the gross up earning uses the supplemental tax tables and is not included when the base salary is determined.

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Click **New** to create the secondary earning code.

3.  Enter a name and description for the earning code, such as Gross up and Gross up earning.

4.  In the **Include in payment run type** field, select **Automatic**.
    
    When you select this option, the **Base earnings component**, **Unit of measure**, **Tax method**, and **Gross up earning code** fields display the default values, which can’t be changed.

5.  On the **Accounting** tab, click **Add** to add a line to the table.

6.  Select a default main account. Leave the **Department**, **Job**, and **Worker** fields blank, unless you want to restrict the use of the earning code.

7.  Click **New** to create the main earning code.

8.  Enter a name and description for the earning code, such as CarAllow and Gross up earning.

9.  In the **Include in payment run type** field, select **Gross up**.
    
    When you select this option, the **Base earnings component**, **Rate basis**, **Unit of measure**, and **Tax method** fields display the default values, which can’t be changed.

10. In the **Gross up earning code** list, select the secondary earning code that you created. This list displays only the earning codes that meet the guidelines that you set up, and that have the same fringe benefit type as the earning code you are creating.

11. On the **Accounting** tab, click **Add** to add a line to the table.

12. Select the default main account. Leave the **Department**, **Job**, and **Worker** fields blank.

Back to top

## Example: Create a retroactive earning code

Retroactive earning codes are used when a worker receives earnings for past services at a new negotiated rate. An example might be an increase in compensation that was agreed upon after the worker was already paid.

After you create a retroactive earning code, you must assign it to an existing earning code so that it is processed correctly.

Retroactive earning codes are available only if you installed Microsoft Dynamics AX 2012 R3 or the Human resources/Payroll regulatory feature pack July 2014 for Microsoft Dynamics AX 2012 R2.

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Click **New** to create the retroactive earning code.

3.  Enter a name and description for the earning code, such as Retroactive holiday and Retroactive holiday pay.

4.  In the **Include in payment run type** field, select **Primary and additional**.

5.  Select the **Base earnings component** check box.

6.  Select the **Retroactive earning** check box, and then click **OK** when you are prompted to confirm the selection.

7.  Complete the fields on the **Accounting** tab.

8.  Open the earning code to apply the retroactive pay to.

9.  In the **Retroactive earning code** field, select the retroactive earning code that you created..

Back to top

## Example: Create a fringe benefit earning code

Fringe benefits are earnings that workers are taxed on, even though the workers don’t receive any additional increase in actual pay. Examples might be a life insurance policy or fitness allowance.

This example describes how to create a group term life earning code that uses the supplemental tax tables.

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Click **New**.

3.  Enter a name and description for the earning code.

4.  In the **Include in payment run type** field, select **Primary and additional**.

5.  Enter information in the following fields, which work together to determine an earnings amount:
    
      - **Rate basis** – Select **Flat amount** to indicate that this earning can’t be used in time-based or piece-based earnings.
    
      - **Unit of measure** – Select **Each**.
    
      - **Amount or multiplier** – Enter 1.

6.  In the **Tax method** field, select **Supplemental** to indicate that the taxes will be calculated using the supplemental tax rate tables.

7.  In the **Fringe benefit type** field, select **Group term life**.

8.  On the **Accounting** tab, click **Add** to add a line to the table.

9.  Select a default main account. Leave the **Department**, **Job**, and **Worker** fields blank, unless you want to restrict the use of the earning code.

Back to top

## Example: Create an earning code for overtime premiums

The earning code in this example would be used pay the overtime premium for second-shift time-and-a-half. For more information about premium earnings, see [Premium earning setup tasks](premium-earning-setup-tasks.md).

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Click **New**.

3.  Enter a name and description for the earning code. For example, you might enter FLSA 2nd OT as the earning code name and FLSA second shift time and a half as the description.

4.  Enter the following information on the **General** tab.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Include in payment run type</strong></p></td>
    <td><p><strong>Primary and additional</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Base earnings component</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retroactive earning</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rate basis</strong></p></td>
    <td><p><strong>Regular rate of pay</strong></p>
    <p>This field is used together with the <strong>Amount or multiplier</strong> field to determine the premium amount.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Unit of measure</strong></p></td>
    <td><p>This field is automatically set to <strong>Each</strong>. It can’t be changed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Productive</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Reduce remaining FMLA time</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax method</strong></p></td>
    <td><p><strong>Regular</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fringe benefit type</strong></p></td>
    <td><p><strong>Not applicable</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount or multiplier</strong></p></td>
    <td><p>1.50</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Gross up earning code</strong></p></td>
    <td><p>This field is not used.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Base definition</strong></p></td>
    <td><p><strong>Not applicable</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Basis earning code group</strong></p></td>
    <td><p>Select the earning code group that contains the earning codes that are used to calculate this premium. For example, select All nondiscretionary earnings.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **Accounting** tab, click **Add** to add a line to the table, and then select a default main account. Leave the **Department**, **Job**, and **Worker** fields blank, unless you want to restrict the use of the earning code.
    
    If necessary, select a different legal entity and repeat this step.

6.  Optional: On the **Earning code groups** tab, click **Add** to select an earning code group to add this earning code to. For example, you might have created an earning code group for all earning codes that are used by hourly workers.

Regular rate of pay lines are added to earnings statements manually. They are not generated by the premium earnings generation process. Therefore, when you set up premium earnings, you will not add earning codes that have a rate basis of **Regular rate of pay** to premium codes.

Back to top

## Example: Create an earning code for premiums that are controlled by premium earning policies

Premiums that are based on other earnings or on characteristics of the worker or position are controlled by premium earning policies. Additional setup steps are required before you can use these premiums. For more information, see [Premium earning setup tasks](premium-earning-setup-tasks.md).

The earning code in this example would be used pay a 20 percent shift differential for work on the second shift.

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Click **New**.

3.  Enter a name and description for the earning code. For example, you might enter 2nd shift 20% as the earning code name, and 20% differential for 2nd shift as the description.

4.  Enter the following information on the **General** tab.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Include in payment run type</strong></p></td>
    <td><p><strong>Primary and additional</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Base earnings component</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retroactive earning</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rate basis</strong></p></td>
    <td><p><strong>Percent of earnings</strong></p>
    <p>This field is used together with the <strong>Amount or multiplier</strong> field to determine the premium amount.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Unit of measure</strong></p></td>
    <td><p>This field is automatically set to <strong>Each</strong>. It can’t be changed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Productive</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Reduce remaining FMLA time</strong></p></td>
    <td><p>Cleared</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax method</strong></p></td>
    <td><p><strong>Regular</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fringe benefit type</strong></p></td>
    <td><p><strong>Not applicable</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount or multiplier</strong></p></td>
    <td><p>.20</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Gross up earning code</strong></p></td>
    <td><p>This field is not used.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Base definition</strong></p></td>
    <td><p><strong>Not applicable</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Basis earning code group</strong></p></td>
    <td><p>Select the earning code group that contains the earning codes that are eligible for this premium, such as 2nd shift earnings.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **Accounting** tab, click **Add** to add a line to the table, and then select a default main account. Leave the **Department**, **Job**, and **Worker** fields blank, unless you want to restrict the use of the earning code.
    
    If necessary, select a different legal entity and repeat this step.

6.  Optional: On the **Earning code groups** tab, click **Add** to select an earning code group to add this earning code to. For example, you might have created an earning code group for all earning codes that are used by hourly workers.

Back to top

## Find related tasks

[Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md)

  


