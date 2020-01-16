---
title: MissingLineShippingInfoNotification.LineIdsWithMissingInventoryLocation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineIdsWithMissingInventoryLocation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.MissingLineShippingInfoNotification.LineIdsWithMissingInventoryLocation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.missinglineshippinginfonotification.lineidswithmissinginventorylocation(v=AX.60)
ms:contentKeyID: 65321308
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.MissingLineShippingInfoNotification.LineIdsWithMissingInventoryLocation
dev_langs:
- CSharp
- C++
- VB
---

# LineIdsWithMissingInventoryLocation Property

Gets the line identifiers that are missing an inventory location.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineIdsWithMissingInventoryLocation As ReadOnlyCollection(Of String)
    Get
    Private Set
'Usage
Dim instance As MissingLineShippingInfoNotification
Dim value As ReadOnlyCollection(Of String)

value = instance.LineIdsWithMissingInventoryLocation
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<string> LineIdsWithMissingInventoryLocation { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<String^>^ LineIdsWithMissingInventoryLocation {
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

