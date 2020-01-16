---
title: VerifyProductExistenceRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.verifyproductexistencerequest.criteria(v=AX.60)
ms:contentKeyID: 62204600
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property

Gets or sets the criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property Criteria As ProductExistenceCriteria
    Get
    Set
'Usage
Dim instance As VerifyProductExistenceRequest
Dim value As ProductExistenceCriteria

value = instance.Criteria

instance.Criteria = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ProductExistenceCriteria Criteria { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ProductExistenceCriteria^ Criteria {
    ProductExistenceCriteria^ get ();
    void set (ProductExistenceCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria](productexistencecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductExistenceCriteria](productexistencecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[VerifyProductExistenceRequest Class](verifyproductexistencerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

