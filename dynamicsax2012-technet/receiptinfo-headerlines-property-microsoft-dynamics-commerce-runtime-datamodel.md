---
title: ReceiptInfo.HeaderLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HeaderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.HeaderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptinfo.headerlines(v=AX.60)
ms:contentKeyID: 62205741
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.HeaderLines
dev_langs:
- CSharp
- C++
- VB
---

# HeaderLines Property

Gets or sets the number of lines in the header of a receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HeaderLines As Integer
    Get
    Set
'Usage
Dim instance As ReceiptInfo
Dim value As Integer

value = instance.HeaderLines

instance.HeaderLines = value
```

``` csharp
[DataMemberAttribute]
public int HeaderLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int HeaderLines {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptInfo Class](receiptinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

