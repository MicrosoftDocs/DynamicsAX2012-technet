---
title: GetProductPartsDataServiceResponse.ProductAttributeSchemaEntries Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductAttributeSchemaEntries Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.ProductAttributeSchemaEntries
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataserviceresponse.productattributeschemaentries(v=AX.60)
ms:contentKeyID: 65318489
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.ProductAttributeSchemaEntries
dev_langs:
- CSharp
- C++
- VB
---

# ProductAttributeSchemaEntries Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product attribute schema.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ProductAttributeSchemaEntries As ReadOnlyCollection(Of ProductAttributeSchemaEntry)
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceResponse
Dim value As ReadOnlyCollection(Of ProductAttributeSchemaEntry)

value = instance.ProductAttributeSchemaEntries
```

``` csharp
public ReadOnlyCollection<ProductAttributeSchemaEntry> ProductAttributeSchemaEntries { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<ProductAttributeSchemaEntry^>^ ProductAttributeSchemaEntries {
    ReadOnlyCollection<ProductAttributeSchemaEntry^>^ get ();
    private: void set (ReadOnlyCollection<ProductAttributeSchemaEntry^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductAttributeSchemaEntry](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceResponse Class](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

