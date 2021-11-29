---
title: ReasonCodeDatabaseAccessor.BuildReasonCodesQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BuildReasonCodesQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.BuildReasonCodesQuery(System.String,Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.reasoncodedatabaseaccessor.buildreasoncodesquery(v=AX.60)
ms:contentKeyID: 65317403
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.BuildReasonCodesQuery
dev_langs:
- CSharp
- C++
- VB
---

# BuildReasonCodesQuery Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub BuildReasonCodesQuery ( _
    reasonCodeId As String, _
    query As SqlPagedQuery _
)
'Usage
Dim instance As ReasonCodeDatabaseAccessor
Dim reasonCodeId As String
Dim query As SqlPagedQuery

instance.BuildReasonCodesQuery(reasonCodeId, _
    query)
```

``` csharp
public void BuildReasonCodesQuery(
    string reasonCodeId,
    SqlPagedQuery query
)
```

``` c++
public:
void BuildReasonCodesQuery(
    String^ reasonCodeId, 
    SqlPagedQuery^ query
)
```

#### Parameters

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ReasonCodeDatabaseAccessor Class](reasoncodedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

