---
title: ReceiptInfo.FooterLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FooterLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.FooterLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptinfo.footerlines(v=AX.60)
ms:contentKeyID: 62202595
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.FooterLines
dev_langs:
- CSharp
- C++
- VB
---

# FooterLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the number of lines in the footer of a receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FooterLines As Integer
    Get
    Set
'Usage
Dim instance As ReceiptInfo
Dim value As Integer

value = instance.FooterLines

instance.FooterLines = value
```

``` csharp
[DataMemberAttribute]
public int FooterLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int FooterLines {
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

