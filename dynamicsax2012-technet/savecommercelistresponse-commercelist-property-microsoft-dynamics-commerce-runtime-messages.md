---
title: SaveCommerceListResponse.CommerceList Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CommerceList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCommerceListResponse.CommerceList
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.savecommercelistresponse.commercelist(v=AX.60)
ms:contentKeyID: 62212007
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCommerceListResponse.CommerceList
dev_langs:
- CSharp
- C++
- VB
---

# CommerceList Property

Gets the updated commerce list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommerceList As CommerceList
    Get
    Private Set
'Usage
Dim instance As SaveCommerceListResponse
Dim value As CommerceList

value = instance.CommerceList
```

``` csharp
[DataMemberAttribute]
public CommerceList CommerceList { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CommerceList^ CommerceList {
    CommerceList^ get ();
    private: void set (CommerceList^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveCommerceListResponse Class](savecommercelistresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

