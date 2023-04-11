---
title: ChargeConfiguration.ChargeMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ChargeMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.chargemethod(v=AX.60)
ms:contentKeyID: 49823491
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ChargeMethod
dev_langs:
- CSharp
- C++
- VB
---

# ChargeMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the calculation method of the charge configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MARKUPMETHOD")> _
<DataMemberAttribute> _
Public Property ChargeMethod As ChargeMethod
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As ChargeMethod

value = instance.ChargeMethod

instance.ChargeMethod = value
```

``` csharp
[ColumnAttribute("MARKUPMETHOD")]
[DataMemberAttribute]
public ChargeMethod ChargeMethod { get; set; }
```

``` c++
[ColumnAttribute(L"MARKUPMETHOD")]
[DataMemberAttribute]
public:
property ChargeMethod ChargeMethod {
    ChargeMethod get ();
    void set (ChargeMethod value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeMethod](chargemethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeMethod](chargemethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

