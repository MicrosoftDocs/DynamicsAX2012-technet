---
title: DeviceConfiguration.IncludeKitComponents Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IncludeKitComponents Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.IncludeKitComponents
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.includekitcomponents(v=AX.60)
ms:contentKeyID: 62213084
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.IncludeKitComponents
dev_langs:
- CSharp
- C++
- VB
---

# IncludeKitComponents Property

Gets or sets a value indicating whether kit components should be printed in receipts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INCLUDEKITCOMPONENTS")> _
Public Property IncludeKitComponents As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.IncludeKitComponents

instance.IncludeKitComponents = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INCLUDEKITCOMPONENTS")]
public bool IncludeKitComponents { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INCLUDEKITCOMPONENTS")]
public:
property bool IncludeKitComponents {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if kit component printing is enabeld; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

