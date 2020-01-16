---
title: ISuspendRetrieveSystemV2.GetLastSuspendedTransactionId Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetLastSuspendedTransactionId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV2.GetLastSuspendedTransactionId(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.isuspendretrievesystemv2.getlastsuspendedtransactionid(v=AX.60)
ms:contentKeyID: 62205310
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV2.GetLastSuspendedTransactionId
dev_langs:
- CSharp
- C++
- VB
---

# GetLastSuspendedTransactionId Method

Gets the last suspended transaction ID for the specified store and terminal.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetLastSuspendedTransactionId ( _
    storeId As String, _
    terminalId As String _
) As String
'Usage
Dim instance As ISuspendRetrieveSystemV2
Dim storeId As String
Dim terminalId As String
Dim returnValue As String

returnValue = instance.GetLastSuspendedTransactionId(storeId, _
    terminalId)
```

``` csharp
string GetLastSuspendedTransactionId(
    string storeId,
    string terminalId
)
```

``` c++
String^ GetLastSuspendedTransactionId(
    String^ storeId, 
    String^ terminalId
)
```

#### Parameters

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Last suspended transaction ID if found, null otherwise  

## See Also

#### Reference

[ISuspendRetrieveSystemV2 Interface](isuspendretrievesystemv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

