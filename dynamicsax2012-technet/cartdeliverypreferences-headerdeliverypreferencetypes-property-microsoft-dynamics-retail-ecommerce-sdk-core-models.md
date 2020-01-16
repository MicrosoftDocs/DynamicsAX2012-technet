---
title: CartDeliveryPreferences.HeaderDeliveryPreferenceTypes Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: HeaderDeliveryPreferenceTypes Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartDeliveryPreferences.HeaderDeliveryPreferenceTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.cartdeliverypreferences.headerdeliverypreferencetypes(v=AX.60)
ms:contentKeyID: 65317222
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartDeliveryPreferences.HeaderDeliveryPreferenceTypes
dev_langs:
- CSharp
- C++
- VB
---

# HeaderDeliveryPreferenceTypes Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HeaderDeliveryPreferenceTypes As IEnumerable(Of DeliveryPreferenceType)
    Get
    Set
'Usage
Dim instance As CartDeliveryPreferences
Dim value As IEnumerable(Of DeliveryPreferenceType)

value = instance.HeaderDeliveryPreferenceTypes

instance.HeaderDeliveryPreferenceTypes = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<DeliveryPreferenceType> HeaderDeliveryPreferenceTypes { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<DeliveryPreferenceType>^ HeaderDeliveryPreferenceTypes {
    IEnumerable<DeliveryPreferenceType>^ get ();
    void set (IEnumerable<DeliveryPreferenceType>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DeliveryPreferenceType](deliverypreferencetype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CartDeliveryPreferences Class](cartdeliverypreferences-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

