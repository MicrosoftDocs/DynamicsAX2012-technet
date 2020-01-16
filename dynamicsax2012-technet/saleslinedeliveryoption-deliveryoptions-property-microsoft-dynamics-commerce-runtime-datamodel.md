---
title: SalesLineDeliveryOption.DeliveryOptions Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryOptions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineDeliveryOption.DeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.saleslinedeliveryoption.deliveryoptions(v=AX.60)
ms:contentKeyID: 49819134
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineDeliveryOption.DeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryOptions Property

Gets the collection of delivery options for this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryOptions As ICollection(Of DeliveryOption)
    Get
    Private Set
'Usage
Dim instance As SalesLineDeliveryOption
Dim value As ICollection(Of DeliveryOption)

value = instance.DeliveryOptions
```

``` csharp
[DataMemberAttribute]
public ICollection<DeliveryOption> DeliveryOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<DeliveryOption^>^ DeliveryOptions {
    ICollection<DeliveryOption^>^ get ();
    private: void set (ICollection<DeliveryOption^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SalesLineDeliveryOption Class](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

