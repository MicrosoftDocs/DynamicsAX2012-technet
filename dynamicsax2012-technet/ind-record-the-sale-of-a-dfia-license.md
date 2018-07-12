---
title: (IND) Record the sale of a DFIA license
TOCTitle: (IND) Record the sale of a DFIA license
ms:assetid: b2f861bf-b296-426f-b517-72be9164acda
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664789(v=AX.60)
ms:contentKeyID: 49386119
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- authorization
- (IND)
- India
- DFIA
- Sell
audience: Application User
ms.search.region: India
---

# (IND) Record the sale of a DFIA license 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to record a Duty Free Import Authorization (DFIA) that was sold on the open market.


> [!NOTE]
> <P>You can sell a license only if its status is set to <STRONG>Approved</STRONG> in the <STRONG>EXIM Authorization schemes</STRONG> form.</P>



1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. On the **EXIM Authorization schemes** list page, on the **Action Pane**, in the **New** group, click **EXIM Authorization schemes**.

2.  In the **EXIM Authorization schemes** form, select the authorization that was sold.

3.  Click **Functions**, and then click **Sale** to open the **Authorization sale details** form.
    

    > [!NOTE]
    > <P>The <STRONG>Sale</STRONG> menu item is available only if following criteria are met:</P>
    > <UL>
    > <LI>
    > <P>The <STRONG>Allow sale</STRONG> check box is selected in the <STRONG>DFIA</STRONG> area of the <STRONG>Incentive scheme parameters</STRONG> form.</P>
    > <LI>
    > <P>The <STRONG>Transferable</STRONG> check box is selected for the authorization in the <STRONG>EXIM Authorization schemes</STRONG> form.</P>
    > <LI>
    > <P>The value in the <STRONG>Achieved</STRONG> field is greater than or equal to the value in the <STRONG>Obligation</STRONG> field in the <STRONG>Export obligation</STRONG> form.</P></LI></UL>



4.  In the **Import assessable value** field, enter the cost, insurance, and freight (CIF) amount that remains for the authorization, out of the amount that is allowed.

5.  In the **Expiration date** field, enter the expiration date of the authorization.

6.  In the **Sale value** field, enter the value of the sale of the authorization.

7.  To view the details of the items that can be sold, click **Sale items** to open the **Sale items details** form. After you view the details of the items that can be sold, close the **Sale items details** form.

8.  In the **Authorization sale details** form, on the **Tax information** FastTab, in the **Tax ledger posting group** field, select the relevant ledger posting group. The tax ledger posting group must display **Customs** in the **Tax type** column.

9.  In the **IEC number** field, select the importer-exporter code (IEC) number for the company.

10. In the **Transaction date** field, select the posting date for the invoice for the license.

11. On the **Tax** tab, press CTRL+N to create a new line.

12. In the **Tax component** field, select the tax component that is relevant to the incentive scheme.
    
    The **Ledger account** field displays the ledger account that the exempt duty amount is posted to.
    

    > [!NOTE]
    > <P>The association between the tax component and the ledger account is maintained in the <STRONG>Tax ledger posting groups</STRONG> form.</P>



13. In the **Amount** field, enter the exempt duty amount in the default currency. The amount that you enter is posted to the account that is specified for the DFIA receivable account in the selected incentive scheme.

14. In the **Offset account** field, select the offset ledger account that the exempt duty amount is posted to. The default account is the account that is selected in the **Benefit account** field for the DFIA incentive scheme in the **Incentive scheme parameters** form. However, you can change the default account.

15. In the **Tax code** field, select the tax code for the exempt duty amount, and then click **OK**. You receive the following message:
    
    **You are about to approve the sale of an authorization. Do you want to continue?**
    
    Click **Yes**. A new line appears on the **Lines** FastTab in the **EXIM Authorization schemes** form. The new line displays **Sold** in the **License status** column.
    

    > [!NOTE]
    > <P>The voucher transactions for the sale are posted by using the number sequence that is specified for DFIA vouchers in the <STRONG>Number sequences</STRONG> area in the <STRONG>Incentive scheme parameters</STRONG> form. The voucher is posted on the date that is specified in the <STRONG>Transaction date</STRONG> field.</P>



To view the tax information that is posted, follow these steps:

1.  In the **EXIM Authorization schemes** form, on the **Lines** FastTab, click **Tax information**.

2.  In the **Posted tax information** form, click **Voucher** to open the **Voucher transactions** form.

To view information about the license that was sold, follow these steps:

  - In the **EXIM Authorization schemes** form, on the **Overview** FastTab, click **Inquiry**, and then click **Import details**.
    
    In the **Import details** form, information about the license that was sold is displayed in the **Sold quantity** and **Sold value** fields.

## See also

[(IND) EXIM Authorization schemes (form)](https://technet.microsoft.com/en-us/library/jj664625\(v=ax.60\))

[(IND) Authorization sale details (form)](https://technet.microsoft.com/en-us/library/jj677924\(v=ax.60\))

[(IND) Sale items details (form)](https://technet.microsoft.com/en-us/library/jj710923\(v=ax.60\))

[(IND) Posted tax information (form)](https://technet.microsoft.com/en-us/library/jj664909\(v=ax.60\))

[(IND) Import details - AA/DFIA (form)](https://technet.microsoft.com/en-us/library/jj664632\(v=ax.60\))

  


