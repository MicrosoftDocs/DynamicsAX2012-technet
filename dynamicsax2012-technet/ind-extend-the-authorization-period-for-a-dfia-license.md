---
title: (IND) Extend the authorization period for a DFIA license
TOCTitle: (IND) Extend the authorization period for a DFIA license
ms:assetid: 6e368379-a1e3-4714-a388-bba4000da113
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677902(v=AX.60)
ms:contentKeyID: 49385881
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- India
- DFIA
- authorization period
---

# (IND) Extend the authorization period for a DFIA license [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to extend the authorization period for a Duty Free Import Authorization (DFIA) license.

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. Select the authorization to extend, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

2.  In the **EXIM Authorization schemes** form, in the **Authorization type** field, select **DFIA**.

3.  On the **Overview** FastTab, select the authorization to extend, and then, on the **Lines** FastTab, click **Extension**.

4.  In the **Create extension** form, click the **Authorization extension** FastTab. Then, in the **Identification** field group, in the **Extension letter number** field, enter the number that appears in the extension letter that the customs authority issued to grant the extension.

5.  In the **Issue date** field, select the date on which the extension letter was issued.

6.  In the **Import** field group, in the **Import assessable value** field, enter the extended cost, insurance, and freight (CIF) value for the authorization.

7.  In the **Extension** and **Value** fields, define the extension period. For example, to extend the authorization by 18 months, select **Months** in the **Extension** field, and then enter **18** in the **Value** field.

8.  On the **Tax information** FastTab, in the **Tax ledger posting group** field, select the ledger posting group for the saved tax amount.

9.  In the **IEC number** field, select the Importer-Exporter Code number for the company.

10. In the **Transaction date** field, select the posting date.

11. On the **Tax** tab, press CTRL+N, and then, in the **Tax component** field, select the tax component that applies to the incentive scheme.
    

    > [!NOTE]
    > <P>A receivable account for the incentive scheme must be defined for the tax component in the <STRONG>Tax ledger posting groups</STRONG> form. The receivable account appears in the <STRONG>Ledger account</STRONG> field.</P>



12. In the **Amount** field, enter the amount that is exempt from customs duty.

13. By default, the **Offset account** field displays the ledger account that is associated with the incentive scheme in the **Benefit account** field in the **Incentive scheme parameters** form. To override the default, select a different account.

14. In the **Tax code** field, select the tax code that is updated by the amount that is exempt from customs duty.

15. Click **OK**. When a message prompts you to confirm that you want to approve the authorization, click **Yes**.

The validity period for the authorization is extended, and in the **EXIM Authorization schemes** form, on the **Lines** FastTab, the **License status** field displays **Extended**.

## See also

[(IND) Create extension (form)](https://technet.microsoft.com/en-us/library/jj664454\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

