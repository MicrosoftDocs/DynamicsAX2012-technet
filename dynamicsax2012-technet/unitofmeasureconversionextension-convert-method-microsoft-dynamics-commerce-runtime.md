---
title: UnitOfMeasureConversionExtension.Convert Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Convert Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.UnitOfMeasureConversionExtension.Convert(Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.unitofmeasureconversionextension.convert(v=AX.60)
ms:contentKeyID: 49856555
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.UnitOfMeasureConversionExtension.Convert
dev_langs:
- CSharp
- C++
- VB
---

# Convert Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Convert quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Convert ( _
    unitOfMeasureConversion As UnitOfMeasureConversion, _
    fromQuantity As Decimal _
) As Decimal
'Usage
Dim unitOfMeasureConversion As UnitOfMeasureConversion
Dim fromQuantity As Decimal
Dim returnValue As Decimal

returnValue = unitOfMeasureConversion.Convert(fromQuantity)
```

``` csharp
public static decimal Convert(
    this UnitOfMeasureConversion unitOfMeasureConversion,
    decimal fromQuantity
)
```

``` c++
[ExtensionAttribute]
public:
static Decimal Convert(
    UnitOfMeasureConversion^ unitOfMeasureConversion, 
    Decimal fromQuantity
)
```

#### Parameters

  - unitOfMeasureConversion  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - fromQuantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
To quantity.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[UnitOfMeasureConversionExtension Class](unitofmeasureconversionextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

