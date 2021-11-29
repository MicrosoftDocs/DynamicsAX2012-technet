---
title: DeviceConfiguration.MustKeyInPriceIfZero Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MustKeyInPriceIfZero Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MustKeyInPriceIfZero
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.mustkeyinpriceifzero(v=AX.60)
ms:contentKeyID: 62212669
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MustKeyInPriceIfZero
dev_langs:
- CSharp
- C++
- VB
---

# MustKeyInPriceIfZero Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether must key in price if zero.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MUSTKEYINPRICEIFZERO")> _
<DataMemberAttribute> _
Public Property MustKeyInPriceIfZero As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.MustKeyInPriceIfZero

instance.MustKeyInPriceIfZero = value
```

``` csharp
[ColumnAttribute("MUSTKEYINPRICEIFZERO")]
[DataMemberAttribute]
public bool MustKeyInPriceIfZero { get; set; }
```

``` c++
[ColumnAttribute(L"MUSTKEYINPRICEIFZERO")]
[DataMemberAttribute]
public:
property bool MustKeyInPriceIfZero {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if must key in price if zero is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

