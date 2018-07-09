---
title: (IND) Post a shipping bill for an export sales order
TOCTitle: (IND) Post a shipping bill for an export sales order
ms:assetid: 0b64888e-f6f6-4afa-ad7a-97dc4c70eac8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664470(v=AX.60)
ms:contentKeyID: 49385549
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- DBK scheme
- DFIA scheme
- EPCG scheme
- export order
- shipping bill
---

# (IND) Post a shipping bill for an export sales order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can export goods, you must generate a shipping bill for the goods. Before you can generate a shipping bill, you must create an export sales order and generate and post the invoice for it. You must generate a shipping bill before you can run the incentive scheme processes, such as the duty drawback process, to calculate and apply for incentives for a selected time period.

1.  Click **Accounts receivable** \> **Common** \> **Customs export order**.

2.  On the **Customs export order** list page, on the **Action pane**, in the **New** group, click **Export order**.

3.  In the **Export order** form, click **New** to create a new line.

4.  In the **Sales order** field, select a sales order number in the list. Only export sales orders that have been invoiced appear in the list.

5.  In the **Invoice** field, select the invoice number of a posted sales order. All other fields in this form are updated automatically.

6.  Click **Shipping bill** to set up the parameters to generate a shipping bill for the export order.

7.  In the **Posting shipping bill** form, on the **Parameters** tab, in the **Parameter** group, select the **Shipping bill** check box.

8.  In the **Number** field, select the posted shipping bill that the export transactions apply to.

9.  In the lower pane, click the **Line incentive scheme** tab to view the customs tariff code, duty drawback details, port ID, and product group information that was specified on the selected sales invoice.
    

    > [!NOTE]
    > <P>This tab is available only when you select the <STRONG>Activate incentive schemes</STRONG> check box in the <STRONG>Sales tax</STRONG> area in the <STRONG>General ledger parameters</STRONG> form.</P>



10. Click **OK** to post the shipping bill for the export order and generate the shipping bill journal entries.

## See also

[(IND) Posting shipping bill (form)](https://technet.microsoft.com/en-us/library/jj664918\(v=ax.60\))

[(IND) Create an export order for DBK scheme](ind-create-an-export-order-for-dbk-scheme.md)

[(IND) Apply for duty drawback (DBK) for an export order](ind-apply-for-duty-drawback-dbk-for-an-export-order.md)

[(IND) Create an export order for an EPCG incentive scheme](ind-create-an-export-order-for-an-epcg-incentive-scheme.md)

[(IND) Create an export order for the DFIA incentive scheme](ind-create-an-export-order-for-the-dfia-incentive-scheme.md)

[(IND) Create an export order and apply the AA incentive scheme to the export order](ind-create-an-export-order-and-apply-the-aa-incentive-scheme-to-the-export-order.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

