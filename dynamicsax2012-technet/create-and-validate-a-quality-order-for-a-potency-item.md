---
title: Create and validate a quality order for a potency item
TOCTitle: Create and validate a quality order for a potency item
ms:assetid: 7ea865cc-afdb-4894-a656-db9e67115502
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838740(v=AX.60)
ms:contentKeyID: 50120623
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create and validate a quality order for a potency item [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to report results of a quality order and update the inventory base batch attribute for the specified potency item and to validate the quality order after the test results are entered and the batch attribute values are updated.


> [!NOTE]
> <P>A quality order is created for each batch number that is created when the potency item is received.</P>



1.  Click **Inventory management** \> **Periodic** \> **Quality management** \> **Quality orders**.

2.  Create a quality order. For more information, see [(PM) Quality orders (form)](https://technet.microsoft.com/en-us/library/hh328650\(v=ax.60\)).

3.  In the **Reference type** field, select the type of reference for the quality order.

4.  In the **Item number** field, select the number of the potency item for the quality order.

5.  In the **Test group** field, select the test group to associate with the quality order.

6.  In the **Quantity** field, enter the quantity of the potency item.

7.  Enter inventory dimensions for the potency item, and then click **OK**.

8.  On the **General** tab, select the **Update batch disposition** check box to update the batch disposition of the inventory batch, based on the passed or failed status of the quality order batch disposition.

9.  In the **Failed quality order batch disposition** field, select a batch disposition code to indicate whether the quality order disposition failed.

10. In the **Passed quality order batch disposition** field, select a batch disposition code to indicate whether the quality order disposition passed.

11. Select the **Update inventory batch attribute** check box to update the related inventory batches with the value in the **Batch attribute** field for the quality order lines.

12. Click **Validate**, and then in the **Validated by** field, select or enter the employee ID of the employee who must approve the validation process of the selected quality order.

13. Select the **Quarantine about validation failure** check box to quarantine the quality order if the quality order validation fails.
    

    > [!NOTE]
    > <P>This check box is available only if you first clear the <STRONG>Accept error</STRONG> check box.</P>



14. Click **OK** to validate the quality order.

## See also

[Set up prerequisites to report quality order results for a potency item](set-up-prerequisites-to-report-quality-order-results-for-a-potency-item.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

