---
title: SharePointTraceListener.WriteLine Method (String) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: WriteLine Method (String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTraceListener.WriteLine(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.sharepointtracelistener.writeline(v=AX.60)
ms:contentKeyID: 62204464
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# WriteLine Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Writes the string and a new line to the listener.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub WriteLine ( _
    message As String _
)
'Usage
Dim instance As SharePointTraceListener
Dim message As String

instance.WriteLine(message)
```

``` csharp
public override void WriteLine(
    string message
)
```

``` c++
public:
virtual void WriteLine(
    String^ message
) override
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SharePointTraceListener Class](sharepointtracelistener-class-microsoft-dynamics-retail-sharepoint-common.md)

[WriteLine Overload](sharepointtracelistener-writeline-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

