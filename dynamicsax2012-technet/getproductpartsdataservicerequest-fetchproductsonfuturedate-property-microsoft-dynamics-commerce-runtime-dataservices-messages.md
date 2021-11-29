---
title: GetProductPartsDataServiceRequest.FetchProductsOnFutureDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: FetchProductsOnFutureDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.FetchProductsOnFutureDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataservicerequest.fetchproductsonfuturedate(v=AX.60)
ms:contentKeyID: 65316102
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.FetchProductsOnFutureDate
dev_langs:
- CSharp
- C++
- VB
---

# FetchProductsOnFutureDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether products that are assorted in a future date should be included in the result.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property FetchProductsOnFutureDate As Boolean
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceRequest
Dim value As Boolean

value = instance.FetchProductsOnFutureDate
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public bool FetchProductsOnFutureDate { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property bool FetchProductsOnFutureDate {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## Remarks

If this value is false, only products that have the search date between the assortment start and end dates will be retrieved.

If the value is true, only products that have the search date greater or equal to the assortment start date will be retrieved.

## See Also

#### Reference

[GetProductPartsDataServiceRequest Class](getproductpartsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

