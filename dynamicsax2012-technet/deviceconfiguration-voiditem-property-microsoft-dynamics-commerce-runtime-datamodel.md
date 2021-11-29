---
title: DeviceConfiguration.VoidItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VoidItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.VoidItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.voiditem(v=AX.60)
ms:contentKeyID: 62206231
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.VoidItem
dev_langs:
- CSharp
- C++
- VB
---

# VoidItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the void item reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VOIDISPRESSED")> _
<DataMemberAttribute> _
Public Property VoidItem As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.VoidItem

instance.VoidItem = value
```

``` csharp
[ColumnAttribute("VOIDISPRESSED")]
[DataMemberAttribute]
public string VoidItem { get; set; }
```

``` c++
[ColumnAttribute(L"VOIDISPRESSED")]
[DataMemberAttribute]
public:
property String^ VoidItem {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the void item reason code.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

