---
title: TenderType.ChangeTenderTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeTenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.ChangeTenderTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.changetendertypeid(v=AX.60)
ms:contentKeyID: 62211686
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.ChangeTenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# ChangeTenderTypeId Property

Gets or sets the change tender type identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANGETENDERID")> _
Public Property ChangeTenderTypeId As String
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As String

value = instance.ChangeTenderTypeId

instance.ChangeTenderTypeId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANGETENDERID")]
public string ChangeTenderTypeId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANGETENDERID")]
public:
property String^ ChangeTenderTypeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

