---
title: CartDeliveryPreferences.LineDeliveryPreferences Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: LineDeliveryPreferences Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartDeliveryPreferences.LineDeliveryPreferences
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.cartdeliverypreferences.linedeliverypreferences(v=AX.60)
ms:contentKeyID: 65317978
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartDeliveryPreferences.LineDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# LineDeliveryPreferences Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineDeliveryPreferences As IEnumerable(Of LineDeliveryPreference)
    Get
    Set
'Usage
Dim instance As CartDeliveryPreferences
Dim value As IEnumerable(Of LineDeliveryPreference)

value = instance.LineDeliveryPreferences

instance.LineDeliveryPreferences = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<LineDeliveryPreference> LineDeliveryPreferences { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<LineDeliveryPreference^>^ LineDeliveryPreferences {
    IEnumerable<LineDeliveryPreference^>^ get ();
    void set (IEnumerable<LineDeliveryPreference^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[LineDeliveryPreference](linedeliverypreference-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CartDeliveryPreferences Class](cartdeliverypreferences-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

