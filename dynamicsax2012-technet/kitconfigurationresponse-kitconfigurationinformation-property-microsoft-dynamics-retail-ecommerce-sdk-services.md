---
title: KitConfigurationResponse.KitConfigurationInformation Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: KitConfigurationInformation Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.KitConfigurationResponse.KitConfigurationInformation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.kitconfigurationresponse.kitconfigurationinformation(v=AX.60)
ms:contentKeyID: 65317458
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.KitConfigurationResponse.KitConfigurationInformation
dev_langs:
- CSharp
- C++
- VB
---

# KitConfigurationInformation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitConfigurationInformation As KitConfigurationInformation
    Get
    Set
'Usage
Dim instance As KitConfigurationResponse
Dim value As KitConfigurationInformation

value = instance.KitConfigurationInformation

instance.KitConfigurationInformation = value
```

``` csharp
[DataMemberAttribute]
public KitConfigurationInformation KitConfigurationInformation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property KitConfigurationInformation^ KitConfigurationInformation {
    KitConfigurationInformation^ get ();
    void set (KitConfigurationInformation^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.KitConfigurationInformation](kitconfigurationinformation-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[KitConfigurationResponse Class](kitconfigurationresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

