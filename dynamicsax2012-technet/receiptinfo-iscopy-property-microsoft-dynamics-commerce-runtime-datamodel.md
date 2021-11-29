---
title: ReceiptInfo.IsCopy Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsCopy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.IsCopy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptinfo.iscopy(v=AX.60)
ms:contentKeyID: 62210205
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.IsCopy
dev_langs:
- CSharp
- C++
- VB
---

# IsCopy Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the receipt is a copy.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCopy As Boolean
    Get
    Set
'Usage
Dim instance As ReceiptInfo
Dim value As Boolean

value = instance.IsCopy

instance.IsCopy = value
```

``` csharp
[DataMemberAttribute]
public bool IsCopy { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCopy {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptInfo Class](receiptinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

