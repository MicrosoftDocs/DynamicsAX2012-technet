---
title: GetProductCatalogsResponse.ActiveCatalogs Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ActiveCatalogs Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductCatalogsResponse.ActiveCatalogs
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getproductcatalogsresponse.activecatalogs(v=AX.60)
ms:contentKeyID: 62208612
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductCatalogsResponse.ActiveCatalogs
dev_langs:
- CSharp
- C++
- VB
---

# ActiveCatalogs Property

Gets the channel active catalogs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActiveCatalogs As ReadOnlyCollection(Of ProductCatalog)
    Get
    Private Set
'Usage
Dim instance As GetProductCatalogsResponse
Dim value As ReadOnlyCollection(Of ProductCatalog)

value = instance.ActiveCatalogs
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ProductCatalog> ActiveCatalogs { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ProductCatalog^>^ ActiveCatalogs {
    ReadOnlyCollection<ProductCatalog^>^ get ();
    private: void set (ReadOnlyCollection<ProductCatalog^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductCatalogsResponse Class](getproductcatalogsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

