---
title: ConnectionRequest.ExtraData Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExtraData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.ExtraData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.connectionrequest.extradata(v=AX.60)
ms:contentKeyID: 62208039
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.ExtraData
dev_langs:
- CSharp
- C++
- VB
---

# ExtraData Property

Gets or sets the Extra Data for the provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExtraData As String
    Get
    Set
'Usage
Dim instance As ConnectionRequest
Dim value As String

value = instance.ExtraData

instance.ExtraData = value
```

``` csharp
[DataMemberAttribute]
public string ExtraData { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ExtraData {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The device token.  

## See Also

#### Reference

[ConnectionRequest Class](connectionrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

