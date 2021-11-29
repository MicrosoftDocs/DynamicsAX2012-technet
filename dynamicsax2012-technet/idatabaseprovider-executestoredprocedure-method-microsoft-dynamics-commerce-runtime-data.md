---
title: IDatabaseProvider.ExecuteStoredProcedure Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ExecuteStoredProcedure Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.ExecuteStoredProcedure(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection,System.String,System.Collections.Generic.IEnumerable{System.Collections.Generic.KeyValuePair{System.String,System.Object}},System.Collections.Generic.IDictionary{System.String,System.Object},System.Action{Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult},System.Nullable{System.Int32}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseprovider.executestoredprocedure(v=AX.60)
ms:contentKeyID: 65318539
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.ExecuteStoredProcedure
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteStoredProcedure Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes a stored procedure against the database..

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Sub ExecuteStoredProcedure ( _
    connection As IDatabaseConnection, _
    procedureName As String, _
    parameters As IEnumerable(Of KeyValuePair(Of String, Object)), _
    outputParameters As IDictionary(Of String, Object), _
    resultCallback As Action(Of IDatabaseResult), _
    <OutAttribute> ByRef storeProcedureResultValue As Nullable(Of Integer) _
)
'Usage
Dim instance As IDatabaseProvider
Dim connection As IDatabaseConnection
Dim procedureName As String
Dim parameters As IEnumerable(Of KeyValuePair(Of String, Object))
Dim outputParameters As IDictionary(Of String, Object)
Dim resultCallback As Action(Of IDatabaseResult)
Dim storeProcedureResultValue As Nullable(Of Integer)

instance.ExecuteStoredProcedure(connection, _
    procedureName, parameters, outputParameters, _
    resultCallback, storeProcedureResultValue)
```

``` csharp
void ExecuteStoredProcedure(
    IDatabaseConnection connection,
    string procedureName,
    IEnumerable<KeyValuePair<string, Object>> parameters,
    IDictionary<string, Object> outputParameters,
    Action<IDatabaseResult> resultCallback,
    out Nullable<int> storeProcedureResultValue
)
```

``` c++
void ExecuteStoredProcedure(
    IDatabaseConnection^ connection, 
    String^ procedureName, 
    IEnumerable<KeyValuePair<String^, Object^>>^ parameters, 
    IDictionary<String^, Object^>^ outputParameters, 
    Action<IDatabaseResult^>^ resultCallback, 
    [OutAttribute] Nullable<int>% storeProcedureResultValue
)
```

#### Parameters

  - connection  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - procedureName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[KeyValuePair](https://technet.microsoft.com/library/5tbh8a42\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>\>  

<!-- end list -->

  - outputParameters  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  

<!-- end list -->

  - resultCallback  
    Type: [System.Action](https://technet.microsoft.com/library/018hxwa8\(v=ax.60\))\<[IDatabaseResult](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)\>  

<!-- end list -->

  - storeProcedureResultValue  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  

## See Also

#### Reference

[IDatabaseProvider Interface](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

