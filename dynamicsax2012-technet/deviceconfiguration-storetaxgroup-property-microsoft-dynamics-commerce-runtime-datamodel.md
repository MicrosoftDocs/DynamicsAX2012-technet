---
title: DeviceConfiguration.StoreTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StoreTaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.storetaxgroup(v=AX.60)
ms:contentKeyID: 62204005
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StoreTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# StoreTaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the store tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXGROUP")> _
<DataMemberAttribute> _
Public Property StoreTaxGroup As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.StoreTaxGroup

instance.StoreTaxGroup = value
```

``` csharp
[ColumnAttribute("TAXGROUP")]
[DataMemberAttribute]
public string StoreTaxGroup { get; set; }
```

``` c++
[ColumnAttribute(L"TAXGROUP")]
[DataMemberAttribute]
public:
property String^ StoreTaxGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the store tax group.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

