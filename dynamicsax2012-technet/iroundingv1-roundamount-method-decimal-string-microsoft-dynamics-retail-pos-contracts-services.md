---
title: IRoundingV1.RoundAmount Method (Decimal, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RoundAmount Method (Decimal, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundAmount(System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.roundamount(v=AX.60)
ms:contentKeyID: 47344298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RoundAmount Method (Decimal, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Rounds the tender amount according to store.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RoundAmount ( _
    value As Decimal, _
    storeId As String _
) As Decimal
'Usage
Dim instance As IRoundingV1
Dim value As Decimal
Dim storeId As String
Dim returnValue As Decimal

returnValue = instance.RoundAmount(value, _
    storeId)
```

``` csharp
decimal RoundAmount(
    decimal value,
    string storeId
)
```

``` c++
Decimal RoundAmount(
    Decimal value, 
    String^ storeId
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The rounded amount.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[RoundAmount Overload](iroundingv1-roundamount-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

