---
title: Verify that exchange rate information has been entered
TOCTitle: Verify that exchange rate information has been entered
ms:assetid: 0dc6d13d-abc7-411c-9d00-162767163465
ms:mtpsurl: https://technet.microsoft.com/library/Gg751349(v=AX.60)
ms:contentKeyID: 35132540
author: Khairunj
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Verify that exchange rate information has been entered 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following procedures to make sure that information about exchange rates is available to the cubes. Complete these procedures by using the Microsoft Dynamics AX client.

## Select a system currency and an exchange rate type

Complete the following procedure to select a system currency and an exchange rate type. When Microsoft SQL Server Analysis Services generates monetary amounts in a cube, the amounts are calculated by using the system currency and exchange rate type.

1.  Click **System administration** \> **Setup** \> **System parameters**.

2.  From the **System currency** list, select a currency.

3.  From the **System exchange rate type** list, select an exchange rate type.

## Verify the exchange rate information

Complete the following procedure to verify that the system currency and exchange rate type that you selected in the previous procedure are displayed in the **System currency and exchange rate type** form.

1.  Click **System administration** \> **Setup** \> **Business intelligence** \> **Analysis Services** \> **System currency and exchange rate type**.

2.  Verify that the system currency and exchange rate type that you selected in the previous procedure are displayed in this form.

  


