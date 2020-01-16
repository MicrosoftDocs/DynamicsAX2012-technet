---
title: GetAffiliationByAffilationIdDataRequest.AffiliationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: AffiliationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationByAffilationIdDataRequest.AffiliationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaffiliationbyaffilationiddatarequest.affiliationid(v=AX.60)
ms:contentKeyID: 65315728
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationByAffilationIdDataRequest.AffiliationId
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationId Property

Gets affiliation id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationId As Long
    Get
    Private Set
'Usage
Dim instance As GetAffiliationByAffilationIdDataRequest
Dim value As Long

value = instance.AffiliationId
```

``` csharp
[DataMemberAttribute]
public long AffiliationId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property long long AffiliationId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[GetAffiliationByAffilationIdDataRequest Class](getaffiliationbyaffilationiddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

