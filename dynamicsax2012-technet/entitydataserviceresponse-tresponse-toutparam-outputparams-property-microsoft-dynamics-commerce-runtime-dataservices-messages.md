---
title: EntityDataServiceResponse(TResponse, TOutParam).OutputParams Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: OutputParams Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`2.OutputParams
ms:mtpsurl: https://technet.microsoft.com/library/Dn968289(v=AX.60)
ms:contentKeyID: 65320652
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`2.OutputParams
dev_langs:
- CSharp
- C++
- VB
---

# OutputParams Property

Gets the output parameters of data service call.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OutputParams As TOutParam()
    Get
    Private Set
'Usage
Dim instance As EntityDataServiceResponse
Dim value As TOutParam()

value = instance.OutputParams
```

``` csharp
[DataMemberAttribute]
public TOutParam[] OutputParams { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property array<TOutParam>^ OutputParams {
    array<TOutParam>^ get ();
    private: void set (array<TOutParam>^ value);
}
```

#### Property Value

Type: [TOutParam](entitydataserviceresponse-tresponse-toutparam-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)\[\]  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[EntityDataServiceResponse\<TResponse, TOutParam\> Class](entitydataserviceresponse-tresponse-toutparam-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

