---
title: MissingLineShippingInfoNotification.LineIdsWithMissingDeliveryMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineIdsWithMissingDeliveryMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.MissingLineShippingInfoNotification.LineIdsWithMissingDeliveryMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.missinglineshippinginfonotification.lineidswithmissingdeliverymode(v=AX.60)
ms:contentKeyID: 65318182
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.MissingLineShippingInfoNotification.LineIdsWithMissingDeliveryMode
dev_langs:
- CSharp
- C++
- VB
---

# LineIdsWithMissingDeliveryMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the line identifiers that are missing a delivery mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineIdsWithMissingDeliveryMode As ReadOnlyCollection(Of String)
    Get
    Private Set
'Usage
Dim instance As MissingLineShippingInfoNotification
Dim value As ReadOnlyCollection(Of String)

value = instance.LineIdsWithMissingDeliveryMode
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<string> LineIdsWithMissingDeliveryMode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<String^>^ LineIdsWithMissingDeliveryMode {
    ReadOnlyCollection<String^>^ get ();
    private: void set (ReadOnlyCollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[MissingLineShippingInfoNotification Class](missinglineshippinginfonotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

