---
title: ChangedProductsSearchRequest.RequestForChanges Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: RequestForChanges Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ChangedProductsSearchRequest.RequestForChanges
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.changedproductssearchrequest.requestforchanges(v=AX.60)
ms:contentKeyID: 62209258
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ChangedProductsSearchRequest.RequestForChanges
dev_langs:
- CSharp
- C++
- VB
---

# RequestForChanges Property

Gets or sets the request for changed products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property RequestForChanges As ChangedProductsSearchCriteria
    Get
    Set
'Usage
Dim instance As ChangedProductsSearchRequest
Dim value As ChangedProductsSearchCriteria

value = instance.RequestForChanges

instance.RequestForChanges = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ChangedProductsSearchCriteria RequestForChanges { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ChangedProductsSearchCriteria^ RequestForChanges {
    ChangedProductsSearchCriteria^ get ();
    void set (ChangedProductsSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The object representing the request for changed products.  

## See Also

#### Reference

[ChangedProductsSearchRequest Class](changedproductssearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

