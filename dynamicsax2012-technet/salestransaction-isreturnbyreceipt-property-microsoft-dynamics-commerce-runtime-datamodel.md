---
title: SalesTransaction.IsReturnByReceipt Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsReturnByReceipt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsReturnByReceipt
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.isreturnbyreceipt(v=AX.60)
ms:contentKeyID: 62206523
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IsReturnByReceipt
dev_langs:
- CSharp
- C++
- VB
---

# IsReturnByReceipt Property

Gets or sets a value indicating whether the sales transaction is for return.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALEISRETURNSALE")> _
<DataMemberAttribute> _
Public Property IsReturnByReceipt As Boolean
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Boolean

value = instance.IsReturnByReceipt

instance.IsReturnByReceipt = value
```

``` csharp
[ColumnAttribute("SALEISRETURNSALE")]
[DataMemberAttribute]
public bool IsReturnByReceipt { get; set; }
```

``` c++
[ColumnAttribute(L"SALEISRETURNSALE")]
[DataMemberAttribute]
public:
property bool IsReturnByReceipt {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The value.  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

