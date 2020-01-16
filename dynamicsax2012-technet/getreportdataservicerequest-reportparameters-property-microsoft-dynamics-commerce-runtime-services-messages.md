---
title: GetReportDataServiceRequest.ReportParameters Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReportParameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceRequest.ReportParameters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreportdataservicerequest.reportparameters(v=AX.60)
ms:contentKeyID: 65316197
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceRequest.ReportParameters
dev_langs:
- CSharp
- C++
- VB
---

# ReportParameters Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReportParameters As IEnumerable(Of CommerceProperty)
    Get
    Private Set
'Usage
Dim instance As GetReportDataServiceRequest
Dim value As IEnumerable(Of CommerceProperty)

value = instance.ReportParameters
```

``` csharp
[DataMemberAttribute]
public IEnumerable<CommerceProperty> ReportParameters { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<CommerceProperty^>^ ReportParameters {
    IEnumerable<CommerceProperty^>^ get ();
    private: void set (IEnumerable<CommerceProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReportDataServiceRequest Class](getreportdataservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

