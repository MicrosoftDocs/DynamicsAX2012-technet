---
title: GetChangedPricesServiceResponse.Products Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Products Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangedPricesServiceResponse.Products
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchangedpricesserviceresponse.products(v=AX.60)
ms:contentKeyID: 62207089
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangedPricesServiceResponse.Products
dev_langs:
- CSharp
- C++
- VB
---

# Products Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of products whose prices have changed and recalculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Products As IEnumerable(Of Product)
    Get
    Private Set
'Usage
Dim instance As GetChangedPricesServiceResponse
Dim value As IEnumerable(Of Product)

value = instance.Products
```

``` csharp
[DataMemberAttribute]
public IEnumerable<Product> Products { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<Product^>^ Products {
    IEnumerable<Product^>^ get ();
    private: void set (IEnumerable<Product^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetChangedPricesServiceResponse Class](getchangedpricesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

