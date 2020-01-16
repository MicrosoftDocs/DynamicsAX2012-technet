---
title: IStoreInventoryServicesV1.GetOrderReceiptLines Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetOrderReceiptLines Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.GetOrderReceiptLines(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.Services.PRCountingType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.istoreinventoryservicesv1.getorderreceiptlines(v=AX.60)
ms:contentKeyID: 47343979
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServicesV1.GetOrderReceiptLines
dev_langs:
- CSharp
- C++
- VB
---

# GetOrderReceiptLines Method

Syncs the local list of order receipt document lines by receipt document ID with HQ.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetOrderReceiptLines ( _
    orderNumber As String, _
    prType As PRCountingType _
) As IList(Of IPRDocumentLine)
'Usage
Dim instance As IStoreInventoryServicesV1
Dim orderNumber As String
Dim prType As PRCountingType
Dim returnValue As IList(Of IPRDocumentLine)

returnValue = instance.GetOrderReceiptLines(orderNumber, _
    prType)
```

``` csharp
IList<IPRDocumentLine> GetOrderReceiptLines(
    string orderNumber,
    PRCountingType prType
)
```

``` c++
IList<IPRDocumentLine^>^ GetOrderReceiptLines(
    String^ orderNumber, 
    PRCountingType prType
)
```

#### Parameters

  - orderNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - prType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PRCountingType](prcountingtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[IPRDocumentLine](iprdocumentline-interface-microsoft-dynamics-retail-pos-contracts-services.md)\>  
Returns an order document that has a list of receipt document lines.  

## See Also

#### Reference

[IStoreInventoryServicesV1 Interface](istoreinventoryservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

