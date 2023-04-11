---
title: SalesOrder.RequestedDeliveryDate Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: RequestedDeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SalesOrder.RequestedDeliveryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.salesorder.requesteddeliverydate(v=AX.60)
ms:contentKeyID: 65318373
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SalesOrder.RequestedDeliveryDate
dev_langs:
- CSharp
- C++
- VB
---

# RequestedDeliveryDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RequestedDeliveryDate As String
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As String

value = instance.RequestedDeliveryDate

instance.RequestedDeliveryDate = value
```

``` csharp
[DataMemberAttribute]
public string RequestedDeliveryDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ RequestedDeliveryDate {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

