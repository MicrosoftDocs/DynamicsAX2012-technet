---
title: ShiftTenderLine.TenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.tendercurrency(v=AX.60)
ms:contentKeyID: 62210015
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# TenderCurrency Property

Gets or sets currency of tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CURRENCY")> _
Public Property TenderCurrency As String
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As String

value = instance.TenderCurrency

instance.TenderCurrency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CURRENCY")]
public string TenderCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CURRENCY")]
public:
property String^ TenderCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

