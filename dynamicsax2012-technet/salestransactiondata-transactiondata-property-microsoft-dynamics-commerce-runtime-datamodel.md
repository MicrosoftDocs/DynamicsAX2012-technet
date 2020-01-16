---
title: SalesTransactionData.TransactionData Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.TransactionData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata.transactiondata(v=AX.60)
ms:contentKeyID: 62210856
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.TransactionData
dev_langs:
- CSharp
- C++
- VB
---

# TransactionData Property

Gets or sets the serialized sales transaction data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TRANSACTIONDATA")> _
<IgnoreDataMemberAttribute> _
Public Property TransactionData As Byte()
    Get
    Set
'Usage
Dim instance As SalesTransactionData
Dim value As Byte()

value = instance.TransactionData

instance.TransactionData = value
```

``` csharp
[ColumnAttribute("TRANSACTIONDATA")]
[IgnoreDataMemberAttribute]
public byte[] TransactionData { get; set; }
```

``` c++
[ColumnAttribute(L"TRANSACTIONDATA")]
[IgnoreDataMemberAttribute]
public:
property array<unsigned char>^ TransactionData {
    array<unsigned char>^ get ();
    void set (array<unsigned char>^ value);
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  
Returns [Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransactionData Class](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

