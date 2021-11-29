---
title: SalesLine.ReturnStore Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnStore Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnStore
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.returnstore(v=AX.60)
ms:contentKeyID: 62213912
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnStore
dev_langs:
- CSharp
- C++
- VB
---

# ReturnStore Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the return store number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETURNSTORE")> _
Public Property ReturnStore As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.ReturnStore

instance.ReturnStore = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETURNSTORE")]
public string ReturnStore { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETURNSTORE")]
public:
property String^ ReturnStore {
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

