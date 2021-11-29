---
title: CartLineData.IsCustomerAccountDeposit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCustomerAccountDeposit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsCustomerAccountDeposit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.iscustomeraccountdeposit(v=AX.60)
ms:contentKeyID: 65316785
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsCustomerAccountDeposit
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
<ColumnAttribute("ISCUSTOMERACCOUNTDEPOSIT")> _
<DataMemberAttribute> _
Public Property IsCustomerAccountDeposit As Boolean
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Boolean

value = instance.IsCustomerAccountDeposit

instance.IsCustomerAccountDeposit = value
```

``` csharp
[ColumnAttribute("ISCUSTOMERACCOUNTDEPOSIT")]
[DataMemberAttribute]
public bool IsCustomerAccountDeposit { get; set; }
```

``` c++
[ColumnAttribute(L"ISCUSTOMERACCOUNTDEPOSIT")]
[DataMemberAttribute]
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

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

