---
title: Run report as finished for a batch order
TOCTitle: Run report as finished for a batch order
ms:assetid: f3425a99-9517-41c0-85f7-5ce94d0cb0ff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh328613(v=AX.60)
ms:contentKeyID: 36688045
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- report batch order as finished
- run report as finished for batch order
---

# Run report as finished for a batch order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Report as finished is a production stage. At this stage, some or all of the quantity for a formula item, co-product, or by-product in a batch order is produced. The inventory is physically received in stock. When you perform the report as finished process, the finished products of the batch order are posted in a Report as finished journal. You can also automatically post the Route card and Picking list journals.

## Report production as finished

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Double-click the batch order that you want to report as finished. The **Batch order** form is displayed.

3.  On the **Action Pane** in the **Production order** tab, in the **Process** group, click **Report as finished**. The **Report as finished** form is displayed.

4.  On the **General** tab, in the **Good quantity** field, enter the number of items that comply with quality standards that you want to report as finished. If you are reporting a catch weight item as finished, enter the actual weight in the **CW good qty** field.
    

    > [!NOTE]
    > <P>When you open the <STRONG>Report as finished</STRONG> form, the quantity that remains to be finished is displayed as the default. However, you can change this quantity if it is appropriate.</P>



5.  In the **Error quantity** field, enter the number of defective items to report as finished.

6.  In the **Error cause** field, select the cause of the error.

7.  If you do not expect additional items to be produced for the batch order, select **End job**. The batch order status is changed to **Reported as finished**. However, you can still report additional items as finished.

8.  If you want to bypass all validations that occur before posting the Report as finished journal, select **Accept error**. If you select this check box, you can report production quantities that differ from order quantities. Otherwise, leave the check box blank.

9.  Click **OK**. The Report as finished journal is posted, and the quantity of finished items that complies with quality standards is physically received in stock.

You can also report a batch order as finished from the Report as finished production journal by using the path **Production control \> Journals \> Report as finished**.

## Post production journals

You can post route card and picking list journals when you report batch order production as finished.

## Post the Route card journal

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Double-click the batch order that you want to report as finished. The **Batch order** form is displayed.

3.  On the **General** tab in the **Automatic route consumption** field, select how to post the Route card journal.
    

    > [!NOTE]
    > <P>If you select <STRONG>Never</STRONG>, nothing is posted. If you also select <STRONG>End-mark route</STRONG>, the journal is posted, but each line has zero consumption. The <STRONG>Operation completed</STRONG> field in the posted route card is also marked. This indicates that you do not expect additional consumption to be posted for the operation.</P>



4.  If you want to post the Route card journal for specific operations, enter the number range of the operations in the **From Oper. No.** and **To Oper. No** fields. If you leave these fields blank, all operations are included in the Route card journal.

5.  To report the batch order as finished, select **Report production as finished**. This option is available only when you specify an operation or operation range.

## Post the Picking list journal

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Double-click the batch order that you want to report as finished. The **Batch order** form is displayed.

3.  On the **General** tab in the **Automatic BOM consumption** field, select how to post the Picking list journal.
    

    > [!NOTE]
    > <P>If you select <STRONG>Never</STRONG>, nothing is posted. If you also select <STRONG>End-mark picking list</STRONG>, the journal is posted, but each journal line has zero consumption. The <STRONG>End job</STRONG> field in the Picking list journal is also marked. This indicates that you do not expect additional consumption to be posted for the material, and the remaining quantity for the material is reset.</P>



## See also

[Batch order (form)](https://technet.microsoft.com/en-us/library/hh352323\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

