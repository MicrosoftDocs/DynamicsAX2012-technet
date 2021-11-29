---
title: TransactionServiceClient.InvokeExtensionMethod Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: InvokeExtensionMethod Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.InvokeExtensionMethod(System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.invokeextensionmethod(v=AX.60)
ms:contentKeyID: 49845714
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.InvokeExtensionMethod
dev_langs:
- CSharp
- C++
- VB
---

# InvokeExtensionMethod Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Invoke extension method with given method name and parameter list from AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function InvokeExtensionMethod ( _
    methodName As String, _
    ParamArray parameters As Object() _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As TransactionServiceClient
Dim methodName As String
Dim parameters As Object()
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.InvokeExtensionMethod(methodName, _
    parameters)
```

``` csharp
public ReadOnlyCollection<Object> InvokeExtensionMethod(
    string methodName,
    params Object[] parameters
)
```

``` c++
public:
ReadOnlyCollection<Object^>^ InvokeExtensionMethod(
    String^ methodName, 
    ... array<Object^>^ parameters
)
```

#### Parameters

  - methodName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
A list of retuen items if avilable.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/ms405965(v=ax.60)">CommunicationException</a></td>
<td><p>Throw if the call failed.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

