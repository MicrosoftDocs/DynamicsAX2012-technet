---
title: ExchangeRate.ValidTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate.ValidTo
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.exchangerate.validto(v=AX.60)
ms:contentKeyID: 65322625
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ExchangeRate.ValidTo
dev_langs:
- CSharp
- C++
- VB
---

# ValidTo Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDTO")> _
<IgnoreDataMemberAttribute> _
<RequiredToBeUtcAttribute(False)> _
Public Property ValidTo As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ExchangeRate
Dim value As DateTimeOffset

value = instance.ValidTo
```

``` csharp
[ColumnAttribute("VALIDTO")]
[IgnoreDataMemberAttribute]
[RequiredToBeUtcAttribute(false)]
public DateTimeOffset ValidTo { get; internal set; }
```

``` c++
[ColumnAttribute(L"VALIDTO")]
[IgnoreDataMemberAttribute]
[RequiredToBeUtcAttribute(false)]
public:
property DateTimeOffset ValidTo {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[ExchangeRate Class](exchangerate-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

