---
title: GetTerminalByRecordIdDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetTerminalByRecordIdDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTerminalByRecordIdDataRequest.#ctor(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getterminalbyrecordiddatarequest.getterminalbyrecordiddatarequest(v=AX.60)
ms:contentKeyID: 65320985
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTerminalByRecordIdDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetTerminalByRecordIdDataRequest Constructor

Initializes a new instance of the [GetTerminalByRecordIdDataRequest](getterminalbyrecordiddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    terminalRecordId As Long, _
    columns As ColumnSet _
)
'Usage
Dim terminalRecordId As Long
Dim columns As ColumnSet

Dim instance As New GetTerminalByRecordIdDataRequest(terminalRecordId, _
    columns)
```

``` csharp
public GetTerminalByRecordIdDataRequest(
    long terminalRecordId,
    ColumnSet columns
)
```

``` c++
public:
GetTerminalByRecordIdDataRequest(
    long long terminalRecordId, 
    ColumnSet^ columns
)
```

#### Parameters

  - terminalRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[GetTerminalByRecordIdDataRequest Class](getterminalbyrecordiddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

