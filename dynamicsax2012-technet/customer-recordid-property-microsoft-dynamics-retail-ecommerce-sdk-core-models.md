---
title: Customer.RecordId Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: RecordId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer.RecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.customer.recordid(v=AX.60)
ms:contentKeyID: 65316886
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer.RecordId
dev_langs:
- CSharp
- C++
- VB
---

# RecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RecordId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.RecordId

instance.RecordId = value
```

``` csharp
[DataMemberAttribute]
public long RecordId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long RecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

