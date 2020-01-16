---
title: DeviceConfiguration.OpenDrawer Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OpenDrawer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OpenDrawer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.opendrawer(v=AX.60)
ms:contentKeyID: 65320367
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OpenDrawer
dev_langs:
- CSharp
- C++
- VB
---

# OpenDrawer Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OPENDRAWER")> _
Public Property OpenDrawer As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.OpenDrawer

instance.OpenDrawer = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OPENDRAWER")]
public string OpenDrawer { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OPENDRAWER")]
public:
property String^ OpenDrawer {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

