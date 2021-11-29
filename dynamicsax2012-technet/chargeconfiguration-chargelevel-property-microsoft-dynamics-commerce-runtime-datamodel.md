---
title: ChargeConfiguration.ChargeLevel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeLevel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ChargeLevel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.chargelevel(v=AX.60)
ms:contentKeyID: 49855245
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ChargeLevel
dev_langs:
- CSharp
- C++
- VB
---

# ChargeLevel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether the configuration is at the transaction or line level.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MODULECATEGORY")> _
<DataMemberAttribute> _
Public Property ChargeLevel As ChargeLevel
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As ChargeLevel

value = instance.ChargeLevel

instance.ChargeLevel = value
```

``` csharp
[ColumnAttribute("MODULECATEGORY")]
[DataMemberAttribute]
public ChargeLevel ChargeLevel { get; set; }
```

``` c++
[ColumnAttribute(L"MODULECATEGORY")]
[DataMemberAttribute]
public:
property ChargeLevel ChargeLevel {
    ChargeLevel get ();
    void set (ChargeLevel value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLevel](chargelevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeLevel](chargelevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

