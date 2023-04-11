---
title: SingleEntityDataServiceResponse(T).Entity Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Entity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SingleEntityDataServiceResponse`1.Entity
ms:mtpsurl: https://technet.microsoft.com/library/Dn991043(v=AX.60)
ms:contentKeyID: 65322485
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SingleEntityDataServiceResponse`1.Entity
dev_langs:
- CSharp
- C++
- VB
---

# Entity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the entity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Entity As T
    Get
    Private Set
'Usage
Dim instance As SingleEntityDataServiceResponse
Dim value As T

value = instance.Entity
```

``` csharp
[DataMemberAttribute]
public T Entity { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property T Entity {
    T get ();
    private: void set (T value);
}
```

#### Property Value

Type: [T](singleentitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
Returns \[{0}\].  

## See Also

#### Reference

[SingleEntityDataServiceResponse\<T\> Class](singleentitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

