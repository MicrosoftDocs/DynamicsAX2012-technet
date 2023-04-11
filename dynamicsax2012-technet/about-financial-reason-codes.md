---
title: About financial reason codes
TOCTitle: About financial reason codes
ms:assetid: 750939e7-3e09-4f55-8d61-31605e5cad28
ms:mtpsurl: https://technet.microsoft.com/library/Gg212968(v=AX.60)
ms:contentKeyID: 36058161
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About financial reason codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A reason code is a code that users can select to record the reason for a change, such as a write-down adjustment or payment reversal. After a reason code has been entered, you can view it by using a journal form or history form.

You can create reason codes that are specific to your organization. Users must select reason codes only if the parameters for a module are set up to require them. For more information, see [Set up reason codes for financial modules](set-up-reason-codes-for-financial-modules.md).

After you have created reason codes, you can select reason codes for various types of transactions or other entries.

## Reason comments

You can enter a reason comment in the same forms where you can select reason codes. Reason comments are optional. Although you can set up default reason comments for each reason code, this setup is not required.

If you select a reason code for a transaction, the default comment that is set up in the reasons form for each module is displayed in the **Reason comment** field. You can change the default reason comment. If you enter a reason comment first and then select a reason code, the reason comment that you entered is not replaced.

## Reason codes in Fixed assets

In Fixed assets, you can require reason codes when specific asset transaction types are entered in journals, or you can require reason codes when the **Sales value**, **Service life**, **Depreciation periods**, or **Expected scrap value** fields are modified in the **Value models** or **Depreciation books** forms.

If you require a reason when one of the field values changes, a **Reason** form is displayed when you save the changes, and you must enter a reason before you can close the **Value models** or **Depreciation books** form.

**Example**

A vehicle accident caused the value of a vehicle to decrease from 20,000 to 15,000. You enter a write-down adjustment for 5,000 in the **Fixed assets** journal form, and you select **VECL** as the reason code in the transaction line.

You then open the value model for the vehicle and reduce the service life by one year, reduce the depreciation periods by one period, and reduce the expected scrap value by 5,000. Because Fixed assets is set up to require a reason code for changes to these fields, you are prompted to select a reason in the **Reason** form when you save the value model. You select **VEHACDT** and then click **OK**. You then open the depreciation book for the vehicle and modify the same fields as for the value model, and you select the **VECL** reason code when you are prompted to specify a reason.

## Reason codes in Accounts receivable

In Accounts receivable, you can set up parameters to require reason codes when transactions are reversed or canceled, or when return orders are posted. You can then view historical reasons in the **Customer transactions** and **Voucher transactions** forms.

Both financial reason codes and return reason codes are used in Accounts receivable. You set up financial reason codes in either the **Financial reasons** form in Organization administration or in the **Customer reasons** form in Accounts receivable, and you can use them with free text invoices, reversals, and cancellations. You set up return reason codes in the **Return reason codes** form, and you can use them with return orders.

## See also

[Reason for asset changes (form)](https://technet.microsoft.com/library/hh208987\(v=ax.60\))

[Fixed asset changes history (form)](https://technet.microsoft.com/library/hh209392\(v=ax.60\))

[Reasons (form)](https://technet.microsoft.com/library/hh209362\(v=ax.60\))

[Set up reason codes for financial modules](set-up-reason-codes-for-financial-modules.md)

  


