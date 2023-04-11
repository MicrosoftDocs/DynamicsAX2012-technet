---
title: Customer.UrlLogisticsLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UrlLogisticsLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.UrlLogisticsLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.urllogisticslocationid(v=AX.60)
ms:contentKeyID: 62204358
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.UrlLogisticsLocationId
dev_langs:
- CSharp
- C++
- VB
---

# UrlLogisticsLocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the URL logistics location id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("URLLOCATIONID")> _
<IgnoreDataMemberAttribute> _
Public Property UrlLogisticsLocationId As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.UrlLogisticsLocationId

instance.UrlLogisticsLocationId = value
```

``` csharp
[ColumnAttribute("URLLOCATIONID")]
[IgnoreDataMemberAttribute]
public string UrlLogisticsLocationId { get; set; }
```

``` c++
[ColumnAttribute(L"URLLOCATIONID")]
[IgnoreDataMemberAttribute]
public:
property String^ UrlLogisticsLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The URL logistics location id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

