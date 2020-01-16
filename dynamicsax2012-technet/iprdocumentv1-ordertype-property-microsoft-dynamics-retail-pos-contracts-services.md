---
title: IPRDocumentV1.OrderType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: OrderType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPRDocumentV1.OrderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprdocumentv1.ordertype(v=AX.60)
ms:contentKeyID: 47344017
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPRDocumentV1.OrderType
dev_langs:
- CSharp
- C++
- VB
---

# OrderType Property

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property OrderType As PRCountingType
    Get
    Set
'Usage
Dim instance As IPRDocumentV1
Dim value As PRCountingType

value = instance.OrderType

instance.OrderType = value
```

``` csharp
PRCountingType OrderType { get; set; }
```

``` c++
property PRCountingType OrderType {
    PRCountingType get ();
    void set (PRCountingType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PRCountingType](prcountingtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [PRCountingType](prcountingtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) type.  

## See Also

#### Reference

[IPRDocumentV1 Interface](iprdocumentv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

