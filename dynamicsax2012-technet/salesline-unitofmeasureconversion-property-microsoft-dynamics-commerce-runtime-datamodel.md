---
title: SalesLine.UnitOfMeasureConversion Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitOfMeasureConversion Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.UnitOfMeasureConversion
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.unitofmeasureconversion(v=AX.60)
ms:contentKeyID: 49846722
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.UnitOfMeasureConversion
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasureConversion Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit of measure conversion.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitOfMeasureConversion As UnitOfMeasureConversion
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As UnitOfMeasureConversion

value = instance.UnitOfMeasureConversion

instance.UnitOfMeasureConversion = value
```

``` csharp
[DataMemberAttribute]
public UnitOfMeasureConversion UnitOfMeasureConversion { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property UnitOfMeasureConversion^ UnitOfMeasureConversion {
    UnitOfMeasureConversion^ get ();
    void set (UnitOfMeasureConversion^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The unit of measure conversion.  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

