---
title: CartLineData.IsReturnByReceipt Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsReturnByReceipt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsReturnByReceipt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.isreturnbyreceipt(v=AX.60)
ms:contentKeyID: 62212174
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsReturnByReceipt
dev_langs:
- CSharp
- C++
- VB
---

# IsReturnByReceipt Property

Gets or sets a value indicating whether the sales line is for return by receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETURNNOSALE")> _
Public Property IsReturnByReceipt As Boolean
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Boolean

value = instance.IsReturnByReceipt

instance.IsReturnByReceipt = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETURNNOSALE")]
public bool IsReturnByReceipt { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETURNNOSALE")]
public:
property bool IsReturnByReceipt {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

