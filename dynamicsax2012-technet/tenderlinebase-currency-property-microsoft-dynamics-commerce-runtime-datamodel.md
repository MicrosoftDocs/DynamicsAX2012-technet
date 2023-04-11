---
title: TenderLineBase.Currency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Currency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.Currency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.currency(v=AX.60)
ms:contentKeyID: 62210535
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.Currency
dev_langs:
- CSharp
- C++
- VB
---

# Currency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CURRENCY")> _
Public Property Currency As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.Currency

instance.Currency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CURRENCY")]
public string Currency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CURRENCY")]
public:
property String^ Currency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The currency.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

