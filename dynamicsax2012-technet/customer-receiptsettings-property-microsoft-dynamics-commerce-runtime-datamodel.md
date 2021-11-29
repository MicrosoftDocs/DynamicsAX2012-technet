---
title: Customer.ReceiptSettings Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.ReceiptSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.receiptsettings(v=AX.60)
ms:contentKeyID: 62209791
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.ReceiptSettings
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptSettings Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets receipt settings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RECEIPTSETTINGS")> _
Public Property ReceiptSettings As Integer
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Integer

value = instance.ReceiptSettings

instance.ReceiptSettings = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RECEIPTSETTINGS")]
public int ReceiptSettings { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RECEIPTSETTINGS")]
public:
property int ReceiptSettings {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

