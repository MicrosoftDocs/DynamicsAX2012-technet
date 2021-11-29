---
title: GetProductPartsDataServiceRequest.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.LanguageId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataservicerequest.languageid(v=AX.60)
ms:contentKeyID: 65321973
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the language identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property LanguageId As String
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceRequest
Dim value As String

value = instance.LanguageId
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string LanguageId { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ LanguageId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceRequest Class](getproductpartsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

