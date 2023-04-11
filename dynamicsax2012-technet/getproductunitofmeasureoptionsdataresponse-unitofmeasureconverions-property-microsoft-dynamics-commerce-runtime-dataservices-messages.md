---
title: GetProductUnitOfMeasureOptionsDataResponse.UnitOfMeasureConverions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: UnitOfMeasureConverions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataResponse.UnitOfMeasureConverions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductunitofmeasureoptionsdataresponse.unitofmeasureconverions(v=AX.60)
ms:contentKeyID: 65316800
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductUnitOfMeasureOptionsDataResponse.UnitOfMeasureConverions
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasureConverions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the products' unit of measure options.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property UnitOfMeasureConverions As ReadOnlyCollection(Of UnitOfMeasureConversion)
    Get
    Private Set
'Usage
Dim instance As GetProductUnitOfMeasureOptionsDataResponse
Dim value As ReadOnlyCollection(Of UnitOfMeasureConversion)

value = instance.UnitOfMeasureConverions
```

``` csharp
public ReadOnlyCollection<UnitOfMeasureConversion> UnitOfMeasureConverions { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<UnitOfMeasureConversion^>^ UnitOfMeasureConverions {
    ReadOnlyCollection<UnitOfMeasureConversion^>^ get ();
    private: void set (ReadOnlyCollection<UnitOfMeasureConversion^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductUnitOfMeasureOptionsDataResponse Class](getproductunitofmeasureoptionsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

