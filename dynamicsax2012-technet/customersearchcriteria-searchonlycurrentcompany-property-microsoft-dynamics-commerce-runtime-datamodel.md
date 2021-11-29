---
title: CustomerSearchCriteria.SearchOnlyCurrentCompany Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchOnlyCurrentCompany Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria.SearchOnlyCurrentCompany
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customersearchcriteria.searchonlycurrentcompany(v=AX.60)
ms:contentKeyID: 62210023
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria.SearchOnlyCurrentCompany
dev_langs:
- CSharp
- C++
- VB
---

# SearchOnlyCurrentCompany Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to search only current company.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchOnlyCurrentCompany As Boolean
    Get
    Set
'Usage
Dim instance As CustomerSearchCriteria
Dim value As Boolean

value = instance.SearchOnlyCurrentCompany

instance.SearchOnlyCurrentCompany = value
```

``` csharp
[DataMemberAttribute]
public bool SearchOnlyCurrentCompany { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool SearchOnlyCurrentCompany {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if search only current company; otherwise, false.  

## See Also

#### Reference

[CustomerSearchCriteria Class](customersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

