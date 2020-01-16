---
title: FindPriceAdjustmentsDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: FindPriceAdjustmentsDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.FindPriceAdjustmentsDataServiceRequest.#ctor(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{System.Int64},System.String,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.findpriceadjustmentsdataservicerequest.findpriceadjustmentsdataservicerequest(v=AX.60)
ms:contentKeyID: 65322637
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.FindPriceAdjustmentsDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# FindPriceAdjustmentsDataServiceRequest Constructor

Initializes a new instance of the [FindPriceAdjustmentsDataServiceRequest](findpriceadjustmentsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productId As Long, _
    distinctProductVariantId As Long, _
    priceGroupIds As IEnumerable(Of Long), _
    currencyCode As String, _
    unitOfMeasure As String, _
    activeDate As DateTimeOffset _
)
'Usage
Dim productId As Long
Dim distinctProductVariantId As Long
Dim priceGroupIds As IEnumerable(Of Long)
Dim currencyCode As String
Dim unitOfMeasure As String
Dim activeDate As DateTimeOffset

Dim instance As New FindPriceAdjustmentsDataServiceRequest(productId, _
    distinctProductVariantId, priceGroupIds, _
    currencyCode, unitOfMeasure, activeDate)
```

``` csharp
public FindPriceAdjustmentsDataServiceRequest(
    long productId,
    long distinctProductVariantId,
    IEnumerable<long> priceGroupIds,
    string currencyCode,
    string unitOfMeasure,
    DateTimeOffset activeDate
)
```

``` c++
public:
FindPriceAdjustmentsDataServiceRequest(
    long long productId, 
    long long distinctProductVariantId, 
    IEnumerable<long long>^ priceGroupIds, 
    String^ currencyCode, 
    String^ unitOfMeasure, 
    DateTimeOffset activeDate
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - distinctProductVariantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - priceGroupIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasure  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[FindPriceAdjustmentsDataServiceRequest Class](findpriceadjustmentsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

