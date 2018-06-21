---
title: (IND) Withholding tax calculation
TOCTitle: (IND) Withholding tax calculation
ms:assetid: 4326760d-9d7a-4565-928c-2ebd003988b2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn306811(v=AX.60)
ms:contentKeyID: 54925756
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Withholding tax calculation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012_

You can set up and calculate withholding tax for the tax deducted at source (TDS) and tax collected at source (TCS) tax types on the following transaction values:

  - The net transaction value that excludes indirect tax.

  - The net transaction value that excludes charges.

  - The net transaction value that excludes indirect tax and charges.

  - The gross transaction value that includes indirect tax.

  - The gross transaction value that includes taxes and charges.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## Can I calculate withholding tax without including charges on the transaction?

Yes. You can calculate withholding tax without including charges on the transaction. To exclude charges from the calculation of withholding tax, in the **Withholding tax groups** form, create a withholding tax group for the **TDS** or **TCS** tax type, and then in the **Exclude charges for TDS or TCS calculation** field, select **Yes**.

## Can I calculate withholding tax excluding service tax where service tax is also applicable on a transaction?

Yes. You can calculate withholding tax on the net transaction value that excludes the service tax. To calculate withholding tax by excluding service tax, in the **Withholding tax groups** form, create a withholding tax group for the **TDS** or **TCS** tax type, and then in the **Exclude tax for TDS or TCS calculation** field, select **Service tax**.

## How can I calculate TCS that excludes service tax and charges?

To calculate TCS that excludes service tax and charges, in the **Withholding tax groups** form, create a withholding tax group for the **TCS** tax type, and then perform the following tasks:

1.  In the **Exclude charges for TDS or TCS calculation** field, select **Service tax**.

2.  In the **Exclude charges for TDS or TCS calculation** field, select **Yes**.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

