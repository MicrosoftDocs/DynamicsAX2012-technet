---
title: IRoundingV1.RoundAmount Method (Decimal, String, String, Boolean) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RoundAmount Method (Decimal, String, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundAmount(System.Decimal,System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.roundamount(v=AX.60)
ms:contentKeyID: 47344489
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RoundAmount Method (Decimal, String, String, Boolean)

Rounds the tender amount according to store.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RoundAmount ( _
    value As Decimal, _
    storeId As String, _
    tenderTypeId As String, _
    useCurrencySymbol As Boolean _
) As String
'Usage
Dim instance As IRoundingV1
Dim value As Decimal
Dim storeId As String
Dim tenderTypeId As String
Dim useCurrencySymbol As Boolean
Dim returnValue As String

returnValue = instance.RoundAmount(value, _
    storeId, tenderTypeId, useCurrencySymbol)
```

``` csharp
string RoundAmount(
    decimal value,
    string storeId,
    string tenderTypeId,
    bool useCurrencySymbol
)
```

``` c++
String^ RoundAmount(
    Decimal value, 
    String^ storeId, 
    String^ tenderTypeId, 
    bool useCurrencySymbol
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderTypeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - useCurrencySymbol  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The rounded amount.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[RoundAmount Overload](iroundingv1-roundamount-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

