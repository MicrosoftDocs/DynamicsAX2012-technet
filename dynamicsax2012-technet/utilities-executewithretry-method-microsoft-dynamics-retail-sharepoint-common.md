---
title: Utilities.ExecuteWithRetry Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: ExecuteWithRetry Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.ExecuteWithRetry(System.Action,System.Func`2,System.Boolean,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/library/Dn694247(v=AX.60)
ms:contentKeyID: 62204671
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.ExecuteWithRetry
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteWithRetry Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ExecuteWithRetry ( _
    codeBlock As Action, _
    retryTestCodeBlock As Func, _
    numberOfMaxTries As Boolean, _
    retryInterval As Exception _
)
'Usage
Dim codeBlock As Action
Dim retryTestCodeBlock As Func
Dim numberOfMaxTries As Boolean
Dim retryInterval As Exception

Utilities.ExecuteWithRetry(codeBlock, _
    retryTestCodeBlock, numberOfMaxTries, _
    retryInterval)
```

``` csharp
public static void ExecuteWithRetry(
    Action codeBlock,
    Func retryTestCodeBlock,
    bool numberOfMaxTries,
    Exception retryInterval
)
```

``` c++
public:
static void ExecuteWithRetry(
    Action^ codeBlock, 
    Func^ retryTestCodeBlock, 
    bool numberOfMaxTries, 
    Exception^ retryInterval
)
```

#### Parameters

  - codeBlock  
    Type: [System.Action](https://technet.microsoft.com/library/bb534741\(v=ax.60\))  

<!-- end list -->

  - retryTestCodeBlock  
    Type: [System.Func\<T, TResult\>](https://technet.microsoft.com/library/bb549151\(v=ax.60\))  

<!-- end list -->

  - numberOfMaxTries  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - retryInterval  
    Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

