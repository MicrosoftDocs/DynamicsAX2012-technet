---
title: DeviceConfiguration.OverridePrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OverridePrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OverridePrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.overrideprice(v=AX.60)
ms:contentKeyID: 62203156
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OverridePrice
dev_langs:
- CSharp
- C++
- VB
---

# OverridePrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the override price reason code info.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OVERRIDEPRICE")> _
Public Property OverridePrice As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.OverridePrice

instance.OverridePrice = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OVERRIDEPRICE")]
public string OverridePrice { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OVERRIDEPRICE")]
public:
property String^ OverridePrice {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing override price reason code.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

