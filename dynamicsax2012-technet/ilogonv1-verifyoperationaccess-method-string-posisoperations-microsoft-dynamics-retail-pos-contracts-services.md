---
title: ILogOnV1.VerifyOperationAccess Method (String, PosisOperations) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: VerifyOperationAccess Method (String, PosisOperations)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnV1.VerifyOperationAccess(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ilogonv1.verifyoperationaccess(v=AX.60)
ms:contentKeyID: 49842090
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# VerifyOperationAccess Method (String, PosisOperations)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Verifies if the operator has access for a given operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function VerifyOperationAccess ( _
    operatorID As String, _
    operation As PosisOperations _
) As Boolean
'Usage
Dim instance As ILogOnV1
Dim operatorID As String
Dim operation As PosisOperations
Dim returnValue As Boolean

returnValue = instance.VerifyOperationAccess(operatorID, _
    operation)
```

``` csharp
bool VerifyOperationAccess(
    string operatorID,
    PosisOperations operation
)
```

``` c++
bool VerifyOperationAccess(
    String^ operatorID, 
    PosisOperations operation
)
```

#### Parameters

  - operatorID  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - operation  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if operator has access, false other wise.  

## See Also

#### Reference

[ILogOnV1 Interface](ilogonv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[VerifyOperationAccess Overload](ilogonv1-verifyoperationaccess-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

