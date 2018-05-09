---
title: ErrorEventDelegate Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ErrorEventDelegate Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ErrorEventDelegate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.erroreventdelegate(v=AX.60)
ms:contentKeyID: 47344503
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ErrorEventDelegate
dev_langs:
- CSharp
- C++
- VB
---

# ErrorEventDelegate Delegate

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ErrorEventDelegate interface is the error event delegate class.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub ErrorEventDelegate ( _
    errorCode As Integer, _
    error As String _
)
'Usage
Dim instance As New ErrorEventDelegate(AddressOf HandlerMethod)
```

``` csharp
public delegate void ErrorEventDelegate(
    int errorCode,
    string error
)
```

``` c++
public delegate void ErrorEventDelegate(
    int errorCode, 
    String^ error
)
```

#### Parameters

  - errorCode  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - error  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

