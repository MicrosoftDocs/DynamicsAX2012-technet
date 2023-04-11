---
title: SalesTransaction.IsRequiredAmountPaid Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsRequiredAmountPaid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsRequiredAmountPaid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.isrequiredamountpaid(v=AX.60)
ms:contentKeyID: 65315974
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsRequiredAmountPaid
dev_langs:
- CSharp
- C++
- VB
---

# IsRequiredAmountPaid Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISREQUIREDAMOUNTPAID")> _
<ReadOnlyAttribute("ISREQUIREDAMOUNTPAID")> _
<DataMemberAttribute> _
Public Property IsRequiredAmountPaid As Boolean
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Boolean

value = instance.IsRequiredAmountPaid

instance.IsRequiredAmountPaid = value
```

``` csharp
[ColumnAttribute("ISREQUIREDAMOUNTPAID")]
[ReadOnlyAttribute("ISREQUIREDAMOUNTPAID")]
[DataMemberAttribute]
public bool IsRequiredAmountPaid { get; set; }
```

``` c++
[ColumnAttribute(L"ISREQUIREDAMOUNTPAID")]
[ReadOnlyAttribute(L"ISREQUIREDAMOUNTPAID")]
[DataMemberAttribute]
public:
property bool IsRequiredAmountPaid {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

