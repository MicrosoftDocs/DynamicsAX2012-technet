---
title: GetReportDataRequest.ReportId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReportId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReportDataRequest.ReportId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreportdatarequest.reportid(v=AX.60)
ms:contentKeyID: 62206463
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReportDataRequest.ReportId
dev_langs:
- CSharp
- C++
- VB
---

# ReportId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the report identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReportId As String
    Get
    Set
'Usage
Dim instance As GetReportDataRequest
Dim value As String

value = instance.ReportId

instance.ReportId = value
```

``` csharp
[DataMemberAttribute]
public string ReportId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReportId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The report identifier.  

## See Also

#### Reference

[GetReportDataRequest Class](getreportdatarequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

