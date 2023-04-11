---
title: IndiaGetInterStateTaxRegimeServiceResponse.TaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IndiaGetInterStateTaxRegimeServiceResponse.TaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.indiagetinterstatetaxregimeserviceresponse.taxgroup(v=AX.60)
ms:contentKeyID: 65322236
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IndiaGetInterStateTaxRegimeServiceResponse.TaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# TaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxGroup As String
    Get
    Private Set
'Usage
Dim instance As IndiaGetInterStateTaxRegimeServiceResponse
Dim value As String

value = instance.TaxGroup
```

``` csharp
[DataMemberAttribute]
public string TaxGroup { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TaxGroup {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IndiaGetInterStateTaxRegimeServiceResponse Class](indiagetinterstatetaxregimeserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

