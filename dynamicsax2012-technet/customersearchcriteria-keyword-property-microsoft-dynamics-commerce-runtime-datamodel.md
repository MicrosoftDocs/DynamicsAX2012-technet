---
title: CustomerSearchCriteria.Keyword Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Keyword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria.Keyword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customersearchcriteria.keyword(v=AX.60)
ms:contentKeyID: 62203228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria.Keyword
dev_langs:
- CSharp
- C++
- VB
---

# Keyword Property

Gets or sets search keyword.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Keyword As String
    Get
    Set
'Usage
Dim instance As CustomerSearchCriteria
Dim value As String

value = instance.Keyword

instance.Keyword = value
```

``` csharp
[DataMemberAttribute]
public string Keyword { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Keyword {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CustomerSearchCriteria Class](customersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

