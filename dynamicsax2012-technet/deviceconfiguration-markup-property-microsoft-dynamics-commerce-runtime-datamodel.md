---
title: DeviceConfiguration.MarkUp Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MarkUp Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MarkUp
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.markup(v=AX.60)
ms:contentKeyID: 65321321
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MarkUp
dev_langs:
- CSharp
- C++
- VB
---

# MarkUp Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MARKUP")> _
Public Property MarkUp As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.MarkUp

instance.MarkUp = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MARKUP")]
public string MarkUp { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MARKUP")]
public:
property String^ MarkUp {
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

