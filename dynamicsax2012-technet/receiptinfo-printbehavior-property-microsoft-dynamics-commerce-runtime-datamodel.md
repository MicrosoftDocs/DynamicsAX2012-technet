---
title: ReceiptInfo.PrintBehavior Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintBehavior Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.PrintBehavior
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptinfo.printbehavior(v=AX.60)
ms:contentKeyID: 62210777
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.PrintBehavior
dev_langs:
- CSharp
- C++
- VB
---

# PrintBehavior Property

Gets or sets the print behaviour of a receipt template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTBEHAVIOUR")> _
Public Property PrintBehavior As Integer
    Get
    Set
'Usage
Dim instance As ReceiptInfo
Dim value As Integer

value = instance.PrintBehavior

instance.PrintBehavior = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTBEHAVIOUR")]
public int PrintBehavior { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTBEHAVIOUR")]
public:
property int PrintBehavior {
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

