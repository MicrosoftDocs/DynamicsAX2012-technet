---
title: GetReportDataServiceRequest.ReportId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReportId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceRequest.ReportId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreportdataservicerequest.reportid(v=AX.60)
ms:contentKeyID: 65321325
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceRequest.ReportId
dev_langs:
- CSharp
- C++
- VB
---

# ReportId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property ReportId As String
    Get
    Private Set
'Usage
Dim instance As GetReportDataServiceRequest
Dim value As String

value = instance.ReportId
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public string ReportId { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property String^ ReportId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetReportDataServiceRequest Class](getreportdataservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

