---
title: ProductDiscontinuedFromChannelNotification.ItemIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDiscontinuedFromChannelNotification.ItemIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productdiscontinuedfromchannelnotification.itemids(v=AX.60)
ms:contentKeyID: 65321120
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDiscontinuedFromChannelNotification.ItemIds
dev_langs:
- CSharp
- C++
- VB
---

# ItemIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of discontinued item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As ProductDiscontinuedFromChannelNotification
Dim value As IEnumerable(Of String)

value = instance.ItemIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ItemIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ItemIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ProductDiscontinuedFromChannelNotification Class](productdiscontinuedfromchannelnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

