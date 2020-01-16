---
title: GetPriceAndDiscountDataServiceRequest.ItemUnits Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ItemUnits Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.ItemUnits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.itemunits(v=AX.60)
ms:contentKeyID: 65322953
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.ItemUnits
dev_langs:
- CSharp
- C++
- VB
---

# ItemUnits Property

Gets or sets the list of item units.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemUnits As IEnumerable(Of ItemUnit)
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As IEnumerable(Of ItemUnit)

value = instance.ItemUnits

instance.ItemUnits = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemUnit> ItemUnits { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemUnit^>^ ItemUnits {
    IEnumerable<ItemUnit^>^ get ();
    protected: void set (IEnumerable<ItemUnit^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

