---
title: DeviceConfiguration.FontScheme Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FontScheme Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.FontScheme
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.fontscheme(v=AX.60)
ms:contentKeyID: 65318999
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.FontScheme
dev_langs:
- CSharp
- C++
- VB
---

# FontScheme Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FONTSCHEME")> _
Public Property FontScheme As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.FontScheme

instance.FontScheme = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FONTSCHEME")]
public int FontScheme { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FONTSCHEME")]
public:
property int FontScheme {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

