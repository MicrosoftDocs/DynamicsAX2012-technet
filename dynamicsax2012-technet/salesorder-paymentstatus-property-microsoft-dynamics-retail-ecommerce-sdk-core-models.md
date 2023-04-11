---
title: SalesOrder.PaymentStatus Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: PaymentStatus Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SalesOrder.PaymentStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.salesorder.paymentstatus(v=AX.60)
ms:contentKeyID: 65315880
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SalesOrder.PaymentStatus
dev_langs:
- CSharp
- C++
- VB
---

# PaymentStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PaymentStatus As Integer
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As Integer

value = instance.PaymentStatus

instance.PaymentStatus = value
```

``` csharp
[DataMemberAttribute]
public int PaymentStatus { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int PaymentStatus {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

