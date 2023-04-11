---
title: GetProductPartsDataServiceResponse.LinkedProducts Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LinkedProducts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.LinkedProducts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataserviceresponse.linkedproducts(v=AX.60)
ms:contentKeyID: 65320554
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.LinkedProducts
dev_langs:
- CSharp
- C++
- VB
---

# LinkedProducts Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the linked products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property LinkedProducts As ReadOnlyCollection(Of LinkedProduct)
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceResponse
Dim value As ReadOnlyCollection(Of LinkedProduct)

value = instance.LinkedProducts
```

``` csharp
public ReadOnlyCollection<LinkedProduct> LinkedProducts { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<LinkedProduct^>^ LinkedProducts {
    ReadOnlyCollection<LinkedProduct^>^ get ();
    private: void set (ReadOnlyCollection<LinkedProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceResponse Class](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

