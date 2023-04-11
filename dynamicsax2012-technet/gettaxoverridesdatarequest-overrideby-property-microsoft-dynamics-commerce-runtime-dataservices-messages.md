---
title: GetTaxOverridesDataRequest.OverrideBy Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: OverrideBy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverridesDataRequest.OverrideBy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettaxoverridesdatarequest.overrideby(v=AX.60)
ms:contentKeyID: 65315505
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverridesDataRequest.OverrideBy
dev_langs:
- CSharp
- C++
- VB
---

# OverrideBy Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the override by.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OverrideBy As TaxOverrideBy
    Get
    Private Set
'Usage
Dim instance As GetTaxOverridesDataRequest
Dim value As TaxOverrideBy

value = instance.OverrideBy
```

``` csharp
[DataMemberAttribute]
public TaxOverrideBy OverrideBy { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TaxOverrideBy OverrideBy {
    TaxOverrideBy get ();
    private: void set (TaxOverrideBy value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetTaxOverridesDataRequest Class](gettaxoverridesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

