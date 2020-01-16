---
title: StoreOperationsManager.RoundAmountByTenderType Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: RoundAmountByTenderType Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.RoundAmountByTenderType(System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.roundamountbytendertype(v=AX.60)
ms:contentKeyID: 65320502
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.RoundAmountByTenderType
dev_langs:
- CSharp
- C++
- VB
---

# RoundAmountByTenderType Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function RoundAmountByTenderType ( _
    amount As Decimal, _
    tenderTypeId As String _
) As Decimal
'Usage
Dim instance As StoreOperationsManager
Dim amount As Decimal
Dim tenderTypeId As String
Dim returnValue As Decimal

returnValue = instance.RoundAmountByTenderType(amount, _
    tenderTypeId)
```

``` csharp
public decimal RoundAmountByTenderType(
    decimal amount,
    string tenderTypeId
)
```

``` c++
public:
Decimal RoundAmountByTenderType(
    Decimal amount, 
    String^ tenderTypeId
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - tenderTypeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

