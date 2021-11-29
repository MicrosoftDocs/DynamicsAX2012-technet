---
title: PaymentErrors.GetHResult Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetHResult Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.PaymentErrors.GetHResult(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.paymenterrors.gethresult(v=AX.60)
ms:contentKeyID: 65322056
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.PaymentErrors.GetHResult
dev_langs:
- CSharp
- C++
- VB
---

# GetHResult Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetHResult ( _
    error As String _
) As Integer
'Usage
Dim error As String
Dim returnValue As Integer

returnValue = PaymentErrors.GetHResult(error)
```

``` csharp
public static int GetHResult(
    string error
)
```

``` c++
public:
static int GetHResult(
    String^ error
)
```

#### Parameters

  - error  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[PaymentErrors Class](paymenterrors-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

