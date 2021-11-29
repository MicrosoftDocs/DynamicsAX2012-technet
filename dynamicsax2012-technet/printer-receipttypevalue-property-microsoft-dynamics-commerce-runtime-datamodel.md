---
title: Printer.ReceiptTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.ReceiptTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.printer.receipttypevalue(v=AX.60)
ms:contentKeyID: 62211843
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.ReceiptTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the ReceiptType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ReceiptTypeValue As Integer
    Get
    Set
'Usage
Dim instance As Printer
Dim value As Integer

value = instance.ReceiptTypeValue

instance.ReceiptTypeValue = value
```

``` csharp
[IgnoreDataMemberAttribute]
public int ReceiptTypeValue { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property int ReceiptTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Printer Class](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

