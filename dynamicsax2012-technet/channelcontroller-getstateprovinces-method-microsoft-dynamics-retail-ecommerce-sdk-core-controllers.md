---
title: ChannelController.GetStateProvinces Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetStateProvinces Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ChannelController.GetStateProvinces(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.channelcontroller.getstateprovinces(v=AX.60)
ms:contentKeyID: 65316762
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ChannelController.GetStateProvinces
dev_langs:
- CSharp
- C++
- VB
---

# GetStateProvinces Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetStateProvinces ( _
    countryCode As String _
) As IEnumerable(Of StateProvinceInfo)
'Usage
Dim instance As ChannelController
Dim countryCode As String
Dim returnValue As IEnumerable(Of StateProvinceInfo)

returnValue = instance.GetStateProvinces(countryCode)
```

``` csharp
public virtual IEnumerable<StateProvinceInfo> GetStateProvinces(
    string countryCode
)
```

``` c++
public:
virtual IEnumerable<StateProvinceInfo^>^ GetStateProvinces(
    String^ countryCode
)
```

#### Parameters

  - countryCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[StateProvinceInfo](stateprovinceinfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[ChannelController Class](channelcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

