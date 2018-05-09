---
title: GetReportDataRequest.ReportParameters Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReportParameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReportDataRequest.ReportParameters
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getreportdatarequest.reportparameters(v=AX.60)
ms:contentKeyID: 62208086
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReportDataRequest.ReportParameters
dev_langs:
- CSharp
- C++
- VB
---

# ReportParameters Property

Gets the report parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReportParameters As IEnumerable(Of CommerceProperty)
    Get
    Private Set
'Usage
Dim instance As GetReportDataRequest
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

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The report parameters.  

## See Also

#### Reference

[GetReportDataRequest Class](getreportdatarequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

