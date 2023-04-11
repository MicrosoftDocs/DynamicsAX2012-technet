---
title: GetItemDimensionsDataRequest.ItemIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ItemIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDimensionsDataRequest.ItemIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemdimensionsdatarequest.itemids(v=AX.60)
ms:contentKeyID: 65322333
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDimensionsDataRequest.ItemIds
dev_langs:
- CSharp
- C++
- VB
---

# ItemIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetItemDimensionsDataRequest
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
The item ids.  

## See Also

#### Reference

[GetItemDimensionsDataRequest Class](getitemdimensionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

