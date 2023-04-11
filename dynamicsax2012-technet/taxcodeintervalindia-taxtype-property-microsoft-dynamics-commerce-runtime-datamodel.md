---
title: TaxCodeIntervalIndia.TaxType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeIntervalIndia.TaxType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeintervalindia.taxtype(v=AX.60)
ms:contentKeyID: 62210904
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeIntervalIndia.TaxType
dev_langs:
- CSharp
- C++
- VB
---

# TaxType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXTYPE_IN")> _
Public Property TaxType As TaxTypeIndia
    Get
    Friend Set
'Usage
Dim instance As TaxCodeIntervalIndia
Dim value As TaxTypeIndia

value = instance.TaxType
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXTYPE_IN")]
public TaxTypeIndia TaxType { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXTYPE_IN")]
public:
property TaxTypeIndia TaxType {
    TaxTypeIndia get ();
    internal: void set (TaxTypeIndia value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxTypeIndia](taxtypeindia-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TaxTypeIndia](taxtypeindia-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TaxCodeIntervalIndia Class](taxcodeintervalindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

