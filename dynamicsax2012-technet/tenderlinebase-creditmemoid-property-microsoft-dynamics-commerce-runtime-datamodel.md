---
title: TenderLineBase.CreditMemoId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreditMemoId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CreditMemoId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.creditmemoid(v=AX.60)
ms:contentKeyID: 62213741
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CreditMemoId
dev_langs:
- CSharp
- C++
- VB
---

# CreditMemoId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets credit memo identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CREDITMEMOID")> _
<DataMemberAttribute> _
Public Property CreditMemoId As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.CreditMemoId

instance.CreditMemoId = value
```

``` csharp
[ColumnAttribute("CREDITMEMOID")]
[DataMemberAttribute]
public string CreditMemoId { get; set; }
```

``` c++
[ColumnAttribute(L"CREDITMEMOID")]
[DataMemberAttribute]
public:
property String^ CreditMemoId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

