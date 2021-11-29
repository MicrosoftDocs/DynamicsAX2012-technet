---
title: LevelStatusDelegate Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: LevelStatusDelegate Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.LevelStatusDelegate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.levelstatusdelegate(v=AX.60)
ms:contentKeyID: 47344075
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.LevelStatusDelegate
dev_langs:
- CSharp
- C++
- VB
---

# LevelStatusDelegate Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Level status delegate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub LevelStatusDelegate ( _
    warningType As CashGuardWarningType, _
    denomination As Integer, _
    numberOf As Short, _
    typeString As String, _
    denominationString As String, _
    warningMessage As String, _
    extInfo As String _
)
'Usage
Dim instance As New LevelStatusDelegate(AddressOf HandlerMethod)
```

``` csharp
public delegate void LevelStatusDelegate(
    CashGuardWarningType warningType,
    int denomination,
    short numberOf,
    string typeString,
    string denominationString,
    string warningMessage,
    string extInfo
)
```

``` c++
public delegate void LevelStatusDelegate(
    CashGuardWarningType warningType, 
    int denomination, 
    short numberOf, 
    String^ typeString, 
    String^ denominationString, 
    String^ warningMessage, 
    String^ extInfo
)
```

#### Parameters

  - warningType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardWarningType](cashguardwarningtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - denomination  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - numberOf  
    Type: [System.Int16](https://technet.microsoft.com/library/e07e6fds\(v=ax.60\))  

<!-- end list -->

  - typeString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - denominationString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - warningMessage  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - extInfo  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

