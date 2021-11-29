---
title: ReceiptInfo.PrintAsSlip Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintAsSlip Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.PrintAsSlip
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptinfo.printasslip(v=AX.60)
ms:contentKeyID: 62208328
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.PrintAsSlip
dev_langs:
- CSharp
- C++
- VB
---

# PrintAsSlip Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value indicating if the receipt was printed as slip.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTASSLIP")> _
<DataMemberAttribute> _
Public Property PrintAsSlip As Integer
    Get
    Set
'Usage
Dim instance As ReceiptInfo
Dim value As Integer

value = instance.PrintAsSlip

instance.PrintAsSlip = value
```

``` csharp
[ColumnAttribute("PRINTASSLIP")]
[DataMemberAttribute]
public int PrintAsSlip { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTASSLIP")]
[DataMemberAttribute]
public:
property int PrintAsSlip {
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

