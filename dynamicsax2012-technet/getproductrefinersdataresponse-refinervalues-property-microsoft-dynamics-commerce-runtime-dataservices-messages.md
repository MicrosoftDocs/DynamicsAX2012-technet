---
title: GetProductRefinersDataResponse.RefinerValues Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: RefinerValues Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataResponse.RefinerValues
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductrefinersdataresponse.refinervalues(v=AX.60)
ms:contentKeyID: 65320956
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataResponse.RefinerValues
dev_langs:
- CSharp
- C++
- VB
---

# RefinerValues Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of values for the refiners.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property RefinerValues As ReadOnlyCollection(Of ProductRefinerValue)
    Get
    Private Set
'Usage
Dim instance As GetProductRefinersDataResponse
Dim value As ReadOnlyCollection(Of ProductRefinerValue)

value = instance.RefinerValues
```

``` csharp
public ReadOnlyCollection<ProductRefinerValue> RefinerValues { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<ProductRefinerValue^>^ RefinerValues {
    ReadOnlyCollection<ProductRefinerValue^>^ get ();
    private: void set (ReadOnlyCollection<ProductRefinerValue^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductRefinerValue](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductRefinersDataResponse Class](getproductrefinersdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

