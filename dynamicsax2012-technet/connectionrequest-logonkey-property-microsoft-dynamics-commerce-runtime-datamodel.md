---
title: ConnectionRequest.LogOnKey Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogOnKey Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.LogOnKey
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.connectionrequest.logonkey(v=AX.60)
ms:contentKeyID: 62211864
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.LogOnKey
dev_langs:
- CSharp
- C++
- VB
---

# LogOnKey Property

Gets or sets the LogOn Key for the provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnKey As String
    Get
    Set
'Usage
Dim instance As ConnectionRequest
Dim value As String

value = instance.LogOnKey

instance.LogOnKey = value
```

``` csharp
[DataMemberAttribute]
public string LogOnKey { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LogOnKey {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The LogOn Key.  

## See Also

#### Reference

[ConnectionRequest Class](connectionrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

