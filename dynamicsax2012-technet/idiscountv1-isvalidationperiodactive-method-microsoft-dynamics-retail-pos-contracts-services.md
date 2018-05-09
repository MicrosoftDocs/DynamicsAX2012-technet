---
title: IDiscountV1.IsValidationPeriodActive Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IsValidationPeriodActive Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.IsValidationPeriodActive(System.String,System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.isvalidationperiodactive(v=AX.60)
ms:contentKeyID: 47344420
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.IsValidationPeriodActive
dev_langs:
- CSharp
- C++
- VB
---

# IsValidationPeriodActive Method

Finds the discount validation period and determines whether it is active for the given date and time

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsValidationPeriodActive ( _
    validationPeriodId As String, _
    transDateTime As DateTime _
) As Boolean
'Usage
Dim instance As IDiscountV1
Dim validationPeriodId As String
Dim transDateTime As DateTime
Dim returnValue As Boolean

returnValue = instance.IsValidationPeriodActive(validationPeriodId, _
    transDateTime)
```

``` csharp
bool IsValidationPeriodActive(
    string validationPeriodId,
    DateTime transDateTime
)
```

``` c++
bool IsValidationPeriodActive(
    String^ validationPeriodId, 
    DateTime transDateTime
)
```

#### Parameters

  - validationPeriodId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transDateTime  
    Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if the validation period is active for the given date and time; otherwise, false.  

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

