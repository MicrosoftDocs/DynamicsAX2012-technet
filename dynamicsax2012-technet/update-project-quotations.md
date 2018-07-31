---
title: Update project quotations
TOCTitle: Update project quotations
ms:assetid: 7d4f3880-05eb-4ad5-bc75-0e72cbff1513
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Bb176039(v=AX.60)
ms:contentKeyID: 36058300
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project quotation
- update quotation
- confirm quotation
- send quotation
audience: Application User
ms.search.region: Global
---

# Update project quotations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the following procedures to update a project quotation.

## Modify a quotation

You can modify an existing quotation by editing the information that is registered on the selected quotation.

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select or open the project quotation that you want to modify.

3.  On the **Action Pane**, on the **Quotation** tab, in the **Maintain** group, click **Edit**.

4.  In the **Project quotation** form, add or change information as appropriate.

## Send a quotation

Any quotation with the status of **Created** can be sent to the prospect for confirmation, either by using e-mail or by mailing a printed copy.

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select or open the quotation that you want to send to the prospect.

3.  On the **Action Pane**, on the **Quote** tab, in the **Generate** group, click **Quotation**.

4.  In the **Send quotation** form, click **Options**, and then in the **Print destination settings** form, select whether you want the quotation sent to **Screen**, **E-mail**, **File**, **Print archive** or **Printer**, and then make any adjustments that you want in the **Specification** area in order to properly route the quotation.

5.  Click **OK** in the **Print destination settings** form.

6.  In the **Send quotation** form, click **OK** to accept the update and to change the quotation status to **Sent**.

## Confirm a quotation

You can confirm any quotation with the status of **Created**. You can confirm the status before the quotation is sent.

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select or open the quotation that has been accepted and confirmed by the prospect.

3.  On the **Action Pane**, on the **Follow up** tab, in the **Generate** group, click **Confirm**.

4.  In the **Confirm quotation** form, select the **Print confirmation** check box if you want to print the quotation.

5.  Click **OK** to accept the update and to change the quotation status to **Confirmed**.

The quotation is converted to a project. Use the **Projects** form for additional processing.

## Record a quotation as lost

When a quotation does not lead to a sale, you can update the status to **Lost**.

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select or open the quotation that you want to register as lost.

3.  On the **Action Pane**, on the **Follow up** tab, in the **Generate** group, click **Lost quotation**.

4.  In the **Lose quotation** form, in the **Reason lost or canceled** field, select the reason that the quotation did not lead to a sale.

5.  Click **OK** to accept the update and to change the quotation status to **Lost**.

## Cancel a quotation

Any quotation with the status **Sent** can be canceled.

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select or open the quotation that you want to cancel.

3.  On the **Action Pane**, on the **Follow up** tab, in the **Generate** group, click **Cancel**.

4.  In the **Cancel quotation** form, in the **Reason lost or canceled** field, select the reason that the quotation was canceled.

5.  Click **OK** to accept the update and to change the quotation status to **Canceled**.

## Update multiple quotations

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select the quotations that you want to update.

3.  On the **Action Pane**, on the **Follow up** tab, in the **Generate** group, click the relevant update option.
    

    > [!NOTE]
    > <P>If you select quotations that have different statuses, only the update options that are available for all the selected quotations are available on the <STRONG>Action Pane</STRONG>. For example, if you select a quotation that has the status <STRONG>Sent</STRONG> and a quotation that has the status <STRONG>Created</STRONG>, only the <STRONG>Confirm</STRONG> button is available on the <STRONG>Action Pane</STRONG>.</P>



4.  Enter your changes in the update form.

You can also use update multiple quotations at the same time by using a periodic job. Click **Project management and accounting** \> **Periodic** \> **Quotations**, and then click the type of update that you want to perform.

## See also

[Project quotation (form)](https://technet.microsoft.com/en-us/library/aa557295\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

[Send quotation (class form)](https://technet.microsoft.com/en-us/library/aa589556\(v=ax.60\))

[Confirm quotation (class form)](https://technet.microsoft.com/en-us/library/aa571332\(v=ax.60\))

[Lose quotation (class form)](https://technet.microsoft.com/en-us/library/aa583731\(v=ax.60\))

[Cancel quotation (class form)](https://technet.microsoft.com/en-us/library/aa634363\(v=ax.60\))

  


