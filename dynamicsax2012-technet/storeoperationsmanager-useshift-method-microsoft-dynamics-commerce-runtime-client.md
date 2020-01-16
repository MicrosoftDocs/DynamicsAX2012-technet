---
title: StoreOperationsManager.UseShift Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UseShift Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.UseShift(System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.useshift(v=AX.60)
ms:contentKeyID: 62208787
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.UseShift
dev_langs:
- CSharp
- C++
- VB
---

# UseShift Method

Use the specified shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UseShift ( _
    terminalId As String, _
    shiftId As Long _
) As Shift
'Usage
Dim instance As StoreOperationsManager
Dim terminalId As String
Dim shiftId As Long
Dim returnValue As Shift

returnValue = instance.UseShift(terminalId, _
    shiftId)
```

``` csharp
public Shift UseShift(
    string terminalId,
    long shiftId
)
```

``` c++
public:
Shift^ UseShift(
    String^ terminalId, 
    long long shiftId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The shift object.  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

