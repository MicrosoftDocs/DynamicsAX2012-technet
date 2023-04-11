---
title: ReasonCodeDatabaseAccessor.BuildSubReasonCodesQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BuildSubReasonCodesQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.BuildSubReasonCodesQuery(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.reasoncodedatabaseaccessor.buildsubreasoncodesquery(v=AX.60)
ms:contentKeyID: 65316344
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.BuildSubReasonCodesQuery
dev_langs:
- CSharp
- C++
- VB
---

# BuildSubReasonCodesQuery Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub BuildSubReasonCodesQuery ( _
    reasonCodeIds As IEnumerable(Of String), _
    reasonSubCodeId As String, _
    query As SqlPagedQuery _
)
'Usage
Dim instance As ReasonCodeDatabaseAccessor
Dim reasonCodeIds As IEnumerable(Of String)
Dim reasonSubCodeId As String
Dim query As SqlPagedQuery

instance.BuildSubReasonCodesQuery(reasonCodeIds, _
    reasonSubCodeId, query)
```

``` csharp
public void BuildSubReasonCodesQuery(
    IEnumerable<string> reasonCodeIds,
    string reasonSubCodeId,
    SqlPagedQuery query
)
```

``` c++
public:
void BuildSubReasonCodesQuery(
    IEnumerable<String^>^ reasonCodeIds, 
    String^ reasonSubCodeId, 
    SqlPagedQuery^ query
)
```

#### Parameters

  - reasonCodeIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - reasonSubCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ReasonCodeDatabaseAccessor Class](reasoncodedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

