---
title: StoreOperationsManager.ResumeShift Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ResumeShift Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.ResumeShift(System.String,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.resumeshift(v=AX.60)
ms:contentKeyID: 62208259
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.ResumeShift
dev_langs:
- CSharp
- C++
- VB
---

# ResumeShift Method

Resumes the specified shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function ResumeShift ( _
    terminalId As String, _
    shiftId As Long, _
    cashDrawer As String _
) As Shift
'Usage
Dim instance As StoreOperationsManager
Dim terminalId As String
Dim shiftId As Long
Dim cashDrawer As String
Dim returnValue As Shift

returnValue = instance.ResumeShift(terminalId, _
    shiftId, cashDrawer)
```

``` csharp
public Shift ResumeShift(
    string terminalId,
    long shiftId,
    string cashDrawer
)
```

``` c++
public:
Shift^ ResumeShift(
    String^ terminalId, 
    long long shiftId, 
    String^ cashDrawer
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - cashDrawer  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The shift object.  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

