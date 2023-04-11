---
title: GetQuantityDiscountDataServiceRequest.OfferId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: OfferId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetQuantityDiscountDataServiceRequest.OfferId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getquantitydiscountdataservicerequest.offerid(v=AX.60)
ms:contentKeyID: 65316369
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetQuantityDiscountDataServiceRequest.OfferId
dev_langs:
- CSharp
- C++
- VB
---

# OfferId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the offer identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OfferId As String
    Get
    Private Set
'Usage
Dim instance As GetQuantityDiscountDataServiceRequest
Dim value As String

value = instance.OfferId
```

``` csharp
[DataMemberAttribute]
public string OfferId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OfferId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetQuantityDiscountDataServiceRequest Class](getquantitydiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

