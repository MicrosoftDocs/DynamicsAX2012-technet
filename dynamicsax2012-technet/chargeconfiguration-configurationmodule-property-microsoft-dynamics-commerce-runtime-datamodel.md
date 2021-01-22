---
title: ChargeConfiguration.ConfigurationModule Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConfigurationModule Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ConfigurationModule
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.configurationmodule(v=AX.60)
ms:contentKeyID: 49841022
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ConfigurationModule
dev_langs:
- CSharp
- C++
- VB
---

# ConfigurationModule Property

Gets or sets whether the configuration is for sales or shipping.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MODULETYPE")> _
Public Property ConfigurationModule As ChargeModule
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As ChargeModule

value = instance.ConfigurationModule

instance.ConfigurationModule = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MODULETYPE")]
public ChargeModule ConfigurationModule { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MODULETYPE")]
public:
property ChargeModule ConfigurationModule {
    ChargeModule get ();
    void set (ChargeModule value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeModule](chargemodule-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeModule](chargemodule-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

