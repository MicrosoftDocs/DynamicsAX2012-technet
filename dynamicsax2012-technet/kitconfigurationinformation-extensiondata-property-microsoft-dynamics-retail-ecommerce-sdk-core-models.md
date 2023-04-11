---
title: KitConfigurationInformation.ExtensionData Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: ExtensionData Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.KitConfigurationInformation.ExtensionData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.kitconfigurationinformation.extensiondata(v=AX.60)
ms:contentKeyID: 65316677
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.KitConfigurationInformation.ExtensionData
dev_langs:
- CSharp
- C++
- VB
---

# ExtensionData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Property ExtensionData As ExtensionDataObject
    Get
    Set
'Usage
Dim instance As KitConfigurationInformation
Dim value As ExtensionDataObject

value = instance.ExtensionData

instance.ExtensionData = value
```

``` csharp
public ExtensionDataObject ExtensionData { get; set; }
```

``` c++
public:
virtual property ExtensionDataObject^ ExtensionData {
    ExtensionDataObject^ get () sealed;
    void set (ExtensionDataObject^ value) sealed;
}
```

#### Property Value

Type: [System.Runtime.Serialization.ExtensionDataObject](https://technet.microsoft.com/library/ms574816\(v=ax.60\))  

#### Implements

[IExtensibleDataObject.ExtensionData](https://technet.microsoft.com/library/ms553662\(v=ax.60\))  

## See Also

#### Reference

[KitConfigurationInformation Class](kitconfigurationinformation-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

