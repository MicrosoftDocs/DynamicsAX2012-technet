---
title: LineDeliveryPreference.DeliveryPreferenceTypes Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: DeliveryPreferenceTypes Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LineDeliveryPreference.DeliveryPreferenceTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.linedeliverypreference.deliverypreferencetypes(v=AX.60)
ms:contentKeyID: 65316810
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LineDeliveryPreference.DeliveryPreferenceTypes
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryPreferenceTypes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryPreferenceTypes As IEnumerable(Of DeliveryPreferenceType)
    Get
    Set
'Usage
Dim instance As LineDeliveryPreference
Dim value As IEnumerable(Of DeliveryPreferenceType)

value = instance.DeliveryPreferenceTypes

instance.DeliveryPreferenceTypes = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<DeliveryPreferenceType> DeliveryPreferenceTypes { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<DeliveryPreferenceType>^ DeliveryPreferenceTypes {
    IEnumerable<DeliveryPreferenceType>^ get ();
    void set (IEnumerable<DeliveryPreferenceType>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DeliveryPreferenceType](deliverypreferencetype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LineDeliveryPreference Class](linedeliverypreference-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

