---
title: GetItemDimensionsRequest.ItemIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ItemIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemDimensionsRequest.ItemIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemdimensionsrequest.itemids(v=AX.60)
ms:contentKeyID: 62215203
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemDimensionsRequest.ItemIds
dev_langs:
- CSharp
- C++
- VB
---

# ItemIds Property

Gets or sets the list of item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemIds As IEnumerable(Of String)
    Get
    Set
'Usage
Dim instance As GetItemDimensionsRequest
Dim value As IEnumerable(Of String)

value = instance.ItemIds

instance.ItemIds = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ItemIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ItemIds {
    IEnumerable<String^>^ get ();
    void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetItemDimensionsRequest Class](getitemdimensionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

