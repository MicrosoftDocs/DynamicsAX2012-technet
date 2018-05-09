---
title: TenderDetail.BankBagNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BankBagNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.BankBagNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderdetail.bankbagnumber(v=AX.60)
ms:contentKeyID: 62202267
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.BankBagNumber
dev_langs:
- CSharp
- C++
- VB
---

# BankBagNumber Property

Gets or sets the bank bag number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BANKBAGNUMBER")> _
Public Property BankBagNumber As String
    Get
    Set
'Usage
Dim instance As TenderDetail
Dim value As String

value = instance.BankBagNumber

instance.BankBagNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BANKBAGNUMBER")]
public string BankBagNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BANKBAGNUMBER")]
public:
property String^ BankBagNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderDetail Class](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

