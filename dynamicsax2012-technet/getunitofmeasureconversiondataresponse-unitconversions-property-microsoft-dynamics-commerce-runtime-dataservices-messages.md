---
title: GetUnitOfMeasureConversionDataResponse.UnitConversions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: UnitConversions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataResponse.UnitConversions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getunitofmeasureconversiondataresponse.unitconversions(v=AX.60)
ms:contentKeyID: 65320370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataResponse.UnitConversions
dev_langs:
- CSharp
- C++
- VB
---

# UnitConversions Property

Gets the item of unit conversions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitConversions As ReadOnlyCollection(Of UnitOfMeasureConversion)
    Get
    Private Set
'Usage
Dim instance As GetUnitOfMeasureConversionDataResponse
Dim value As ReadOnlyCollection(Of UnitOfMeasureConversion)

value = instance.UnitConversions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<UnitOfMeasureConversion> UnitConversions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<UnitOfMeasureConversion^>^ UnitConversions {
    ReadOnlyCollection<UnitOfMeasureConversion^>^ get ();
    private: void set (ReadOnlyCollection<UnitOfMeasureConversion^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetUnitOfMeasureConversionDataResponse Class](getunitofmeasureconversiondataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

