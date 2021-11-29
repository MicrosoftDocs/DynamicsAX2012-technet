---
title: GetUnitsOfMeasureResponse.UnitsOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: UnitsOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureResponse.UnitsOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getunitsofmeasureresponse.unitsofmeasure(v=AX.60)
ms:contentKeyID: 62208187
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetUnitsOfMeasureResponse.UnitsOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# UnitsOfMeasure Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of units of measure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitsOfMeasure As ReadOnlyCollection(Of UnitOfMeasure)
    Get
    Private Set
'Usage
Dim instance As GetUnitsOfMeasureResponse
Dim value As ReadOnlyCollection(Of UnitOfMeasure)

value = instance.UnitsOfMeasure
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<UnitOfMeasure> UnitsOfMeasure { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<UnitOfMeasure^>^ UnitsOfMeasure {
    ReadOnlyCollection<UnitOfMeasure^>^ get ();
    private: void set (ReadOnlyCollection<UnitOfMeasure^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[UnitOfMeasure](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetUnitsOfMeasureResponse Class](getunitsofmeasureresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

