---
title: GetProductDataServiceResponse.ProductDataXml Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ProductDataXml Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDataServiceResponse.ProductDataXml
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductdataserviceresponse.productdataxml(v=AX.60)
ms:contentKeyID: 65321799
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDataServiceResponse.ProductDataXml
dev_langs:
- CSharp
- C++
- VB
---

# ProductDataXml Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductDataXml As XDocument
    Get
    Private Set
'Usage
Dim instance As GetProductDataServiceResponse
Dim value As XDocument

value = instance.ProductDataXml
```

``` csharp
[DataMemberAttribute]
public XDocument ProductDataXml { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property XDocument^ ProductDataXml {
    XDocument^ get ();
    private: void set (XDocument^ value);
}
```

#### Property Value

Type: [System.Xml.Linq.XDocument](https://technet.microsoft.com/library/bb345449\(v=ax.60\))  

## See Also

#### Reference

[GetProductDataServiceResponse Class](getproductdataserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

