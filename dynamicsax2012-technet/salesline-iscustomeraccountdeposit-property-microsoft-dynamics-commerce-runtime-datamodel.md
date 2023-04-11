---
title: SalesLine.IsCustomerAccountDeposit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCustomerAccountDeposit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsCustomerAccountDeposit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.iscustomeraccountdeposit(v=AX.60)
ms:contentKeyID: 65322488
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsCustomerAccountDeposit
dev_langs:
- CSharp
- C++
- VB
---

# IsCustomerAccountDeposit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISCUSTOMERACCOUNTDEPOSIT")> _
Public Property IsCustomerAccountDeposit As Boolean
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Boolean

value = instance.IsCustomerAccountDeposit

instance.IsCustomerAccountDeposit = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISCUSTOMERACCOUNTDEPOSIT")]
public bool IsCustomerAccountDeposit { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISCUSTOMERACCOUNTDEPOSIT")]
public:
property bool IsCustomerAccountDeposit {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

