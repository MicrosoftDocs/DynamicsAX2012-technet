---
title: Register, update, and delete alternative project quotations
TOCTitle: Register, update, and delete alternative project quotations
ms:assetid: 7d874dbb-a9ef-4436-8580-e59e77ea4c8a
ms:mtpsurl: https://technet.microsoft.com/library/Bb176092(v=AX.60)
ms:contentKeyID: 36058307
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- alternative quotations
- linked quotation
audience: Application User
ms.search.region: Global
---

# Register, update, and delete alternative project quotations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To register alternative quotations, you select a quotation as the main quotation and then link any alternative quotations to the main one. After quotations are linked, any change to the status of one will influence the status of the others.

## Register alternative quotations

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  On the **Action Pane**, on the **Quotation** tab, in the **New** group, click **Sales quotation**.

3.  Create a quotation for a customer.

4.  Create one or more additional quotations for the same customer but with one or more differences from the first quotation, depending on the choices that you want to offer to the customer or prospect.

5.  Open the quotation that you want to use as the main quotation, and then on the **Action Pane**, on the **General** tab, in the **Related information** group, click **Alternative quotations**.

6.  In the **Alternative quotations** form, in the **Linked quotation** field, select the quotation or quotations that you want to use as alternatives to the main quotation.

## Update alternative quotations

You can update alternative quotations the same way that you update regular quotations.

The relationship between the linked quotations means that they can all be **Sent**. But if one quotation is updated to **Confirmed**, the others are automatically updated to **Lost**. To update a quotation to confirmed, do the following:

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select or open the linked quotation that you want to update to **Confirmed**.

3.  On the **Action Pane**, on the **Follow up** tab, in the **Generate** group, click **Confirm**.

4.  In the **Confirm quotation** form, click **OK**.

5.  In the **Lose or cancel alternative quotations** form, select the reason that the other quotations were lost.

## Delete the link to an alternative quotation

When you delete a link to the current quotation, the quotation itself will not be deleted. To delete the link to an alternative quotation, do the following:

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  Select or open the main quotation from which you want to delete the linked alternative quotation.

3.  On the **Action Pane**, on the **General** tab, in the **Related information** group, click **Alternative quotations**.

4.  Select the alternative quotation you want to delete, and then click **Delete**.

## See also

[Create a project quotation](create-a-project-quotation.md)

[Update project quotations](update-project-quotations.md)

[Generate and manage project quotations](generate-and-manage-project-quotations.md)

[Alternative quotations (form)](https://technet.microsoft.com/library/aa550641\(v=ax.60\))

[Delete quotations (form)](https://technet.microsoft.com/library/aa556468\(v=ax.60\))

  


