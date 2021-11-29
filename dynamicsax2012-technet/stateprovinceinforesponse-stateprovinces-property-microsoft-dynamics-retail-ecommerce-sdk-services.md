---
title: StateProvinceInfoResponse.StateProvinces Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: StateProvinces Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StateProvinceInfoResponse.StateProvinces
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.stateprovinceinforesponse.stateprovinces(v=AX.60)
ms:contentKeyID: 65317406
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StateProvinceInfoResponse.StateProvinces
dev_langs:
- CSharp
- C++
- VB
---

# StateProvinces Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StateProvinces As IEnumerable(Of StateProvinceInfo)
    Get
    Friend Set
'Usage
Dim instance As StateProvinceInfoResponse
Dim value As IEnumerable(Of StateProvinceInfo)

value = instance.StateProvinces
```

``` csharp
[DataMemberAttribute]
public IEnumerable<StateProvinceInfo> StateProvinces { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<StateProvinceInfo^>^ StateProvinces {
    IEnumerable<StateProvinceInfo^>^ get ();
    internal: void set (IEnumerable<StateProvinceInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StateProvinceInfo](stateprovinceinfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[StateProvinceInfoResponse Class](stateprovinceinforesponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

