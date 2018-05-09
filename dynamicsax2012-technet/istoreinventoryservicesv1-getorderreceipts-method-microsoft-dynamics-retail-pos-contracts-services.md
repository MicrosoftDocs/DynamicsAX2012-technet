---
title: IStoreInventoryServicesV1.GetOrderReceipts Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetOrderReceipts Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.GetOrderReceipts
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.istoreinventoryservicesv1.getorderreceipts(v=AX.60)
ms:contentKeyID: 47344266
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.GetOrderReceipts
dev_langs:
- CSharp
- C++
- VB
---

# GetOrderReceipts Method

Sync the local list of order receipt documents with HQ.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetOrderReceipts As IList(Of IPRDocument)
'Usage
Dim instance As IStoreInventoryServicesV1
Dim returnValue As IList(Of IPRDocument)

returnValue = instance.GetOrderReceipts()
```

``` csharp
IList<IPRDocument> GetOrderReceipts()
```

``` c++
IList<IPRDocument^>^ GetOrderReceipts()
```

#### Return Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[IPRDocument](iprdocument-interface-microsoft-dynamics-retail-pos-contracts-services.md)\>  
A list of order receipts.  

## See Also

#### Reference

[IStoreInventoryServicesV1 Interface](istoreinventoryservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

