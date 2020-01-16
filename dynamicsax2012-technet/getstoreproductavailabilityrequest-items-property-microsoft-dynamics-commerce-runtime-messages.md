---
title: GetStoreProductAvailabilityRequest.Items Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Items Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.Items
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoreproductavailabilityrequest.items(v=AX.60)
ms:contentKeyID: 49841350
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property

Gets or sets the list of items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Items As IEnumerable(Of ItemUnit)
    Get
    Set
'Usage
Dim instance As GetStoreProductAvailabilityRequest
Dim value As IEnumerable(Of ItemUnit)

value = instance.Items

instance.Items = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemUnit> Items { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemUnit^>^ Items {
    IEnumerable<ItemUnit^>^ get ();
    void set (IEnumerable<ItemUnit^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The items.  

## See Also

#### Reference

[GetStoreProductAvailabilityRequest Class](getstoreproductavailabilityrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

