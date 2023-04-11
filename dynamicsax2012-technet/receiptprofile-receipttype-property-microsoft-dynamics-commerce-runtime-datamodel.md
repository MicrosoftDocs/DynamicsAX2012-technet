---
title: ReceiptProfile.ReceiptType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptProfile.ReceiptType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptprofile.receipttype(v=AX.60)
ms:contentKeyID: 62209146
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptProfile.ReceiptType
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the the receipt type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RECEIPTTYPE")> _
Public Property ReceiptType As String
    Get
    Set
'Usage
Dim instance As ReceiptProfile
Dim value As String

value = instance.ReceiptType

instance.ReceiptType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RECEIPTTYPE")]
public string ReceiptType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RECEIPTTYPE")]
public:
property String^ ReceiptType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptProfile Class](receiptprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

