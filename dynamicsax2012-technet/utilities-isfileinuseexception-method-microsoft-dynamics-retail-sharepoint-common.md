---
title: Utilities.IsFileInUseException Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: IsFileInUseException Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.IsFileInUseException(System.Exception)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.utilities.isfileinuseexception(v=AX.60)
ms:contentKeyID: 62203221
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.IsFileInUseException
dev_langs:
- CSharp
- C++
- VB
---

# IsFileInUseException Method

Checks if the exception is of type "The process cannot access the file because it is being used by another process.". ERROR\_SHARING\_VIOLATION 32 (0x20)

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsFileInUseException ( _
    exception As Exception _
) As Boolean
'Usage
Dim exception As Exception
Dim returnValue As Boolean

returnValue = Utilities.IsFileInUseException(exception)
```

``` csharp
public static bool IsFileInUseException(
    Exception exception
)
```

``` c++
public:
static bool IsFileInUseException(
    Exception^ exception
)
```

#### Parameters

  - exception  
    Type: [System.Exception](https://technet.microsoft.com/en-us/library/c18k6c59\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Bool value indicating if this is a file in use exception or not.  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

