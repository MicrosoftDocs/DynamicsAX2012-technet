---
title: ReceiptInfo.Uppercase Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Uppercase Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.Uppercase
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.receiptinfo.uppercase(v=AX.60)
ms:contentKeyID: 62213917
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.Uppercase
dev_langs:
- CSharp
- C++
- VB
---

# Uppercase Property

Gets or sets the value indicating the uppercase flag.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("UPPERCASE")> _
Public Property Uppercase As Integer
    Get
    Set
'Usage
Dim instance As ReceiptInfo
Dim value As Integer

value = instance.Uppercase

instance.Uppercase = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("UPPERCASE")]
public int Uppercase { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"UPPERCASE")]
public:
property int Uppercase {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptInfo Class](receiptinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

