---
title: StoreOperationsManager.OpenShift Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: OpenShift Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.OpenShift(System.Nullable{System.Int64},System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.openshift(v=AX.60)
ms:contentKeyID: 65320518
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.OpenShift
dev_langs:
- CSharp
- C++
- VB
---

# OpenShift Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function OpenShift ( _
    shiftId As Nullable(Of Long), _
    cashDrawer As String, _
    isShared As Boolean _
) As Shift
'Usage
Dim instance As StoreOperationsManager
Dim shiftId As Nullable(Of Long)
Dim cashDrawer As String
Dim isShared As Boolean
Dim returnValue As Shift

returnValue = instance.OpenShift(shiftId, _
    cashDrawer, isShared)
```

``` csharp
public Shift OpenShift(
    Nullable<long> shiftId,
    string cashDrawer,
    bool isShared
)
```

``` c++
public:
Shift^ OpenShift(
    Nullable<long long> shiftId, 
    String^ cashDrawer, 
    bool isShared
)
```

#### Parameters

  - shiftId  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - cashDrawer  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isShared  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

