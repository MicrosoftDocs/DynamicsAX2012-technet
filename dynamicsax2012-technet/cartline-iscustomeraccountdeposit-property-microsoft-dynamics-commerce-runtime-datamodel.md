---
title: CartLine.IsCustomerAccountDeposit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCustomerAccountDeposit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.IsCustomerAccountDeposit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.iscustomeraccountdeposit(v=AX.60)
ms:contentKeyID: 65321940
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.IsCustomerAccountDeposit
dev_langs:
- CSharp
- C++
- VB
---

# IsCustomerAccountDeposit Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCustomerAccountDeposit As Boolean
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Boolean

value = instance.IsCustomerAccountDeposit

instance.IsCustomerAccountDeposit = value
```

``` csharp
[DataMemberAttribute]
public bool IsCustomerAccountDeposit { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCustomerAccountDeposit {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

