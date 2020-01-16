---
title: About fixed asset acquisitions
TOCTitle: About fixed asset acquisitions
ms:assetid: e7c186f8-eb1c-4833-80e3-d1f00bd4f54a
ms:mtpsurl: https://technet.microsoft.com/library/Aa573194(v=AX.60)
ms:contentKeyID: 36059820
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About fixed asset acquisitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the **Fixed asset posting profiles** form, on the **Ledger accounts** tab, select **Acquisition** and **Acquisition adjustment** to set up fixed asset accounts to post to the ledger.

In journals and on purchase orders, **Ledger account** is typically the balance sheet account, where the acquisition value of the new fixed asset is debited. This account is not displayed in the journal and cannot be replaced in transactions.

**Offset account** is also a balance sheet account. In the general journal and in the fixed assets journal, this account often will be the bank account that is used to pay for the acquisition of the asset. The offset account is a default account, which is suggested in the journals. It can be changed in the journal to any other account from the chart of accounts or to a vendor account, if the fixed asset was purchase from a vendor.

When **Invoice journal** or **Purchase orders** in Accounts payable are used for fixed asset acquisitions, the offset account for the fixed asset transaction is replaced by the vendor account that is selected for the transaction.

For acquisitions posted using the **Inventory to fixed assets** journal in General ledger, the fixed asset is not bought from external sources, but transferred from the company's own inventory. Therefore, the offset account is an inventory issue account for the inventory item in Inventory management.

## See also

[Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md)

[Fixed asset posting profiles (form)](https://technet.microsoft.com/library/aa571467\(v=ax.60\))

  


