---
title: GetChannelCategoryAttributesDataRequest.CategoryIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CategoryIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelCategoryAttributesDataRequest.CategoryIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getchannelcategoryattributesdatarequest.categoryids(v=AX.60)
ms:contentKeyID: 65321770
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelCategoryAttributesDataRequest.CategoryIds
dev_langs:
- CSharp
- C++
- VB
---

# CategoryIds Property

Gets the category identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property CategoryIds As IEnumerable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetChannelCategoryAttributesDataRequest
Dim value As IEnumerable(Of Long)

value = instance.CategoryIds
```

``` csharp
public IEnumerable<long> CategoryIds { get; private set; }
```

``` c++
public:
property IEnumerable<long long>^ CategoryIds {
    IEnumerable<long long>^ get ();
    private: void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCategoryAttributesDataRequest Class](getchannelcategoryattributesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

