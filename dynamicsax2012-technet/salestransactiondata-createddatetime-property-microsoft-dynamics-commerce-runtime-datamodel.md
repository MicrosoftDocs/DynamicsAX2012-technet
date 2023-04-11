---
title: SalesTransactionData.CreatedDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreatedDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.CreatedDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata.createddatetime(v=AX.60)
ms:contentKeyID: 65319816
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.CreatedDateTime
dev_langs:
- CSharp
- C++
- VB
---

# CreatedDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CREATEDDATETIME")> _
<RequiredToBeUtcAttribute(True)> _
Public Property CreatedDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As SalesTransactionData
Dim value As DateTimeOffset

value = instance.CreatedDateTime

instance.CreatedDateTime = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CREATEDDATETIME")]
[RequiredToBeUtcAttribute(true)]
public DateTimeOffset CreatedDateTime { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CREATEDDATETIME")]
[RequiredToBeUtcAttribute(true)]
public:
property DateTimeOffset CreatedDateTime {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[SalesTransactionData Class](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

