---
title: TrackingConfig.TrackingNumbers Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TrackingNumbers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingConfig.TrackingNumbers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.trackingconfig.trackingnumbers(v=AX.60)
ms:contentKeyID: 49819644
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingConfig.TrackingNumbers
dev_langs:
- CSharp
- C++
- VB
---

# TrackingNumbers Property

Gets the collection of tracking numbers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property TrackingNumbers As Collection(Of String)
    Get
    Private Set
'Usage
Dim instance As TrackingConfig
Dim value As Collection(Of String)

value = instance.TrackingNumbers
```

``` csharp
public Collection<string> TrackingNumbers { get; private set; }
```

``` c++
public:
property Collection<String^>^ TrackingNumbers {
    Collection<String^>^ get ();
    private: void set (Collection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[TrackingConfig Class](trackingconfig-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

