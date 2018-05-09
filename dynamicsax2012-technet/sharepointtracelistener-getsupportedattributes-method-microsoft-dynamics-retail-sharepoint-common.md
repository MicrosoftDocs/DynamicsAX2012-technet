---
title: SharePointTraceListener.GetSupportedAttributes Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetSupportedAttributes Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTraceListener.GetSupportedAttributes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.sharepointtracelistener.getsupportedattributes(v=AX.60)
ms:contentKeyID: 62205820
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTraceListener.GetSupportedAttributes
dev_langs:
- CSharp
- C++
- VB
---

# GetSupportedAttributes Method

Gets custom attributes supported by the trace listener.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetSupportedAttributes As String()
'Usage
Dim returnValue As String()

returnValue = Me.GetSupportedAttributes()
```

``` csharp
protected override string[] GetSupportedAttributes()
```

``` c++
protected:
virtual array<String^>^ GetSupportedAttributes() override
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\[\]  
Names of supported attributes.  

## See Also

#### Reference

[SharePointTraceListener Class](sharepointtracelistener-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

