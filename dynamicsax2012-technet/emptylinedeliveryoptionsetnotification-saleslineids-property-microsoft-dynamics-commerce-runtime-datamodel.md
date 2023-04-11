---
title: EmptyLineDeliveryOptionSetNotification.SalesLineIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesLineIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyLineDeliveryOptionSetNotification.SalesLineIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.emptylinedeliveryoptionsetnotification.saleslineids(v=AX.60)
ms:contentKeyID: 65320494
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyLineDeliveryOptionSetNotification.SalesLineIds
dev_langs:
- CSharp
- C++
- VB
---

# SalesLineIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of sales line identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesLineIds As ICollection(Of String)
    Get
    Private Set
'Usage
Dim instance As EmptyLineDeliveryOptionSetNotification
Dim value As ICollection(Of String)

value = instance.SalesLineIds
```

``` csharp
[DataMemberAttribute]
public ICollection<string> SalesLineIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<String^>^ SalesLineIds {
    ICollection<String^>^ get ();
    private: void set (ICollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[EmptyLineDeliveryOptionSetNotification Class](emptylinedeliveryoptionsetnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

