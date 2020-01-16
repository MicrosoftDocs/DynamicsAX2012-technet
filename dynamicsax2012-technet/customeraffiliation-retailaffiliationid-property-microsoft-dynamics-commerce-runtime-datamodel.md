---
title: CustomerAffiliation.RetailAffiliationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailAffiliationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerAffiliation.RetailAffiliationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customeraffiliation.retailaffiliationid(v=AX.60)
ms:contentKeyID: 62211012
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerAffiliation.RetailAffiliationId
dev_langs:
- CSharp
- C++
- VB
---

# RetailAffiliationId Property

Gets or sets the retail affiliation id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETAILAFFILIATIONID")> _
<DataMemberAttribute> _
Public Property RetailAffiliationId As Long
    Get
    Set
'Usage
Dim instance As CustomerAffiliation
Dim value As Long

value = instance.RetailAffiliationId

instance.RetailAffiliationId = value
```

``` csharp
[ColumnAttribute("RETAILAFFILIATIONID")]
[DataMemberAttribute]
public long RetailAffiliationId { get; set; }
```

``` c++
[ColumnAttribute(L"RETAILAFFILIATIONID")]
[DataMemberAttribute]
public:
property long long RetailAffiliationId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The retail affiliation id.  

## See Also

#### Reference

[CustomerAffiliation Class](customeraffiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

