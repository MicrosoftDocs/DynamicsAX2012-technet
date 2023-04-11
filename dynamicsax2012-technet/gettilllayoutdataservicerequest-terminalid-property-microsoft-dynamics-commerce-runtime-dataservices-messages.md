---
title: GetTillLayoutDataServiceRequest.TerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTillLayoutDataServiceRequest.TerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettilllayoutdataservicerequest.terminalid(v=AX.60)
ms:contentKeyID: 65321412
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTillLayoutDataServiceRequest.TerminalId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the terminal identifier (surrogate key) if specified.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TerminalId As Nullable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetTillLayoutDataServiceRequest
Dim value As Nullable(Of Long)

value = instance.TerminalId
```

``` csharp
[DataMemberAttribute]
public Nullable<long> TerminalId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<long long> TerminalId {
    Nullable<long long> get ();
    private: void set (Nullable<long long> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[GetTillLayoutDataServiceRequest Class](gettilllayoutdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

