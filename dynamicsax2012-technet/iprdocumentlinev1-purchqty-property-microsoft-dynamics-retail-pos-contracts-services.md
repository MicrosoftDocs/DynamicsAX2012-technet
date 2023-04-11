---
title: IPRDocumentLineV1.PurchQty Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PurchQty Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPRDocumentLineV1.PurchQty
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprdocumentlinev1.purchqty(v=AX.60)
ms:contentKeyID: 47344452
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPRDocumentLineV1.PurchQty
dev_langs:
- CSharp
- C++
- VB
---

# PurchQty Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PurchQty As Decimal
    Get
    Set
'Usage
Dim instance As IPRDocumentLineV1
Dim value As Decimal

value = instance.PurchQty

instance.PurchQty = value
```

``` csharp
decimal PurchQty { get; set; }
```

``` c++
property Decimal PurchQty {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IPRDocumentLineV1 Interface](iprdocumentlinev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

