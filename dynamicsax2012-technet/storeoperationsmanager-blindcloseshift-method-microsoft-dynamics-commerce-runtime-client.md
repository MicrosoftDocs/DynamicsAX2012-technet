---
title: StoreOperationsManager.BlindCloseShift Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: BlindCloseShift Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.BlindCloseShift(System.String,System.Int64,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.blindcloseshift(v=AX.60)
ms:contentKeyID: 65322856
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.BlindCloseShift
dev_langs:
- CSharp
- C++
- VB
---

# BlindCloseShift Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function BlindCloseShift ( _
    terminalId As String, _
    shiftId As Long, _
    transactionId As String, _
    canForceClose As Boolean _
) As Shift
'Usage
Dim instance As StoreOperationsManager
Dim terminalId As String
Dim shiftId As Long
Dim transactionId As String
Dim canForceClose As Boolean
Dim returnValue As Shift

returnValue = instance.BlindCloseShift(terminalId, _
    shiftId, transactionId, canForceClose)
```

``` csharp
public Shift BlindCloseShift(
    string terminalId,
    long shiftId,
    string transactionId,
    bool canForceClose
)
```

``` c++
public:
Shift^ BlindCloseShift(
    String^ terminalId, 
    long long shiftId, 
    String^ transactionId, 
    bool canForceClose
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - canForceClose  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

