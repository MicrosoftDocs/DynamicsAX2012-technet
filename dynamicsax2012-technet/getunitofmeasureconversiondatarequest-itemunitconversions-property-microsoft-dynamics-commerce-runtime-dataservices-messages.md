---
title: GetUnitOfMeasureConversionDataRequest.ItemUnitConversions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ItemUnitConversions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataRequest.ItemUnitConversions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getunitofmeasureconversiondatarequest.itemunitconversions(v=AX.60)
ms:contentKeyID: 65317614
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetUnitOfMeasureConversionDataRequest.ItemUnitConversions
dev_langs:
- CSharp
- C++
- VB
---

# ItemUnitConversions Property

Gets the item unit conversions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemUnitConversions As IEnumerable(Of ItemUnitConversion)
    Get
    Private Set
'Usage
Dim instance As GetUnitOfMeasureConversionDataRequest
Dim value As IEnumerable(Of ItemUnitConversion)

value = instance.ItemUnitConversions
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemUnitConversion> ItemUnitConversions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemUnitConversion^>^ ItemUnitConversions {
    IEnumerable<ItemUnitConversion^>^ get ();
    private: void set (IEnumerable<ItemUnitConversion^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnitConversion](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetUnitOfMeasureConversionDataRequest Class](getunitofmeasureconversiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

