---
title: SalesLine.Store Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Store Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.Store
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.store(v=AX.60)
ms:contentKeyID: 62210602
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.Store
dev_langs:
- CSharp
- C++
- VB
---

# Store Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the store number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STORE")> _
Public Property Store As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.Store

instance.Store = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STORE")]
public string Store { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STORE")]
public:
property String^ Store {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The store number.  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

