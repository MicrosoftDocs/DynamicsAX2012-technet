---
title: GetReportDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetReportDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceRequest.#ctor(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getreportdataservicerequest.getreportdataservicerequest(v=AX.60)
ms:contentKeyID: 65315498
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetReportDataServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    reportId As String, _
    locale As String, _
    reportParameters As IEnumerable(Of CommerceProperty) _
)
'Usage
Dim reportId As String
Dim locale As String
Dim reportParameters As IEnumerable(Of CommerceProperty)

Dim instance As New GetReportDataServiceRequest(reportId, _
    locale, reportParameters)
```

``` csharp
public GetReportDataServiceRequest(
    string reportId,
    string locale,
    IEnumerable<CommerceProperty> reportParameters
)
```

``` c++
public:
GetReportDataServiceRequest(
    String^ reportId, 
    String^ locale, 
    IEnumerable<CommerceProperty^>^ reportParameters
)
```

#### Parameters

  - reportId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reportParameters  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReportDataServiceRequest Class](getreportdataservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

