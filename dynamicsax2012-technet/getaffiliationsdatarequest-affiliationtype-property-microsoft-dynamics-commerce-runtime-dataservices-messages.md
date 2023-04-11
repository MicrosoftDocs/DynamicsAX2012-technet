---
title: GetAffiliationsDataRequest.AffiliationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: AffiliationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationsDataRequest.AffiliationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaffiliationsdatarequest.affiliationtype(v=AX.60)
ms:contentKeyID: 65321316
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationsDataRequest.AffiliationType
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the affiliation type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationType As RetailAffiliationType
    Get
    Private Set
'Usage
Dim instance As GetAffiliationsDataRequest
Dim value As RetailAffiliationType

value = instance.AffiliationType
```

``` csharp
[DataMemberAttribute]
public RetailAffiliationType AffiliationType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property RetailAffiliationType AffiliationType {
    RetailAffiliationType get ();
    private: void set (RetailAffiliationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailAffiliationType](retailaffiliationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailAffiliationType](retailaffiliationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetAffiliationsDataRequest Class](getaffiliationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

