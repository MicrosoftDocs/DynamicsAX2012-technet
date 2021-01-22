---
title: ConnectionRequest.LogOnType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogOnType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.LogOnType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.connectionrequest.logontype(v=AX.60)
ms:contentKeyID: 62210529
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.LogOnType
dev_langs:
- CSharp
- C++
- VB
---

# LogOnType Property

Gets or sets the LogOnType.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnType As Integer
    Get
    Set
'Usage
Dim instance As ConnectionRequest
Dim value As Integer

value = instance.LogOnType

instance.LogOnType = value
```

``` csharp
[DataMemberAttribute]
public int LogOnType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int LogOnType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
LogOn Type.  

## See Also

#### Reference

[ConnectionRequest Class](connectionrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

