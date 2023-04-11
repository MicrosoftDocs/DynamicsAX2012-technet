---
title: Maintaining Installation-Specific Element IDs and Element Handles
TOCTitle: Maintaining Installation-Specific Element IDs and Element Handles
ms:assetid: e41443b8-1acf-4144-9b7f-2b7c216916ef
ms:mtpsurl: https://technet.microsoft.com/library/Hh352326(v=AX.60)
ms:contentKeyID: 36687956
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Maintaining Installation-Specific Element IDs and Element Handles 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how element IDs and element handles are assigned. This topic also explains how to avoid changing element IDs and element handles, and describes how to recover a system if element IDs and element handles are changed.

In Microsoft Dynamics AX 2012, the way that element IDs are assigned and the number of available IDs differ from earlier versions. Element IDs are also backward compatible and forward compatible. Because of the way that element IDs are assigned, you must avoid randomizing element IDs when you install models or import the model store. Element IDs are assigned to tables, classes, security keys, configuration keys, and license codes.

Element handles are a new concept in Microsoft Dynamics AX 2012. Element handles are assigned to all pieces of metadata in the Application Object Tree (AOT). Element handles are record IDs that are stored in the ModelElement table. You must also avoid randomizing element handles when you install models or import the model store.

## How element IDs and element handles are assigned

In Microsoft Dynamics AX 2012, the model file that contains a set of elements does not contain any element IDs or element handles. Instead, element IDs and element handles are assigned when a customization is installed or imported. Therefore, the same elements have different IDs and handles in different installations. We refer to these IDs and handles as installation-specific IDs and handles. Element IDs and element handles are not tied to layers. In other words, layers no longer have an ID range.

The number of available element IDs has increased, because IDs are now 32-bit. To make element IDs backward compatible, we introduced a new int property for all ID-based elements: **LegacyID**. This property was assigned the ID value from earlier versions of Microsoft Dynamics AX.

Element IDs and element handles are also forward compatible. In other words, they support situations in which a class is renamed in the future. To make element IDs and element handles forward compatible, we introduced the **Origin** GUID property for all ID-based elements and all root elements. This property is set when an element is created, and it remains static for the lifetime of the element.

During import, element IDs are assigned based on the following rules, in this order:

1.  If an element already exists that has the same **Origin** value as the imported element, replace the existing element and reuse its ID.

2.  If an element already exists that has the same **Type**, **Name**, and **ParentID** values as the imported element, replace the existing element and reuse its ID.

3.  If the imported element has a **LegacyID** value, and the **LegacyID**value is available on the target system, add the following setting to the element: ID = LegacyID.

4.  Assign a new installation-specific ID from a guaranteed free range that does not collide with any **LegacyID** values.
    
      - For fields that are in tables that use table inheritance, use an ID number that is greater than 20000.
    
      - For fields that are not in tables that use table inheritance, use an ID number that is greater than 60000.
    
      - For indexes, use an ID number that is greater than 60000.
    
      - For all other elements, use an ID number that is greater than 100000.

During import, element handles are assigned based on the following rules, in this order:

1.  If an element already exists that has the same **Origin** value as the imported element, replace the existing element and reuse its handle.

2.  If an element already exists that has the same **Type**, **Name**, and **ParentHandle** values as the imported element, replace the existing element and reuse its handle.

3.  Assign a new installation-specific handle that uses the next free handle, or Max+1.

## Avoiding changing element IDs and element handles


> [!IMPORTANT]
> <P>Element IDs and element handles are assigned at installation. Therefore, if you delete a model, and you then reimport that model or import a newer version of it, IDs and handles are randomized, and data integrity can be affected.</P>
> <P>Instead of deleting a model before you reimport or upgrade it, import the model over the existing model.</P>



The element IDs and element handles in an environment may change in the following circumstances:

  - A model is deleted and then reimported, instead of being imported over the existing model.

  - A model store is imported from a source system that has different records IDs than the target system. For more information about how to use model stores to deploy customizations, see [Deploying Customizations Across Microsoft Dynamics AX 2012 Environments (White paper)](deploying-customizations-across-microsoft-dynamics-ax-2012-environments-white-paper.md).
    

    > [!WARNING]
    > <P>Unless you are initializing an environment, avoid importing a model store from an environment that has different record IDs.</P>



  - Models are exported one at a time, and then imported into a new environment.

Data can be affected when element IDs and handles are changed. Security tables can be especially affected, because users can be locked out of the system.

Observe the following best practices:

  - Do not delete a model, and then reimport it. Instead, import the model over the existing model.

  - Before you import a model or model store, back up the database of the target system.

## Recovering a system if element IDs and element handles have been changed

This section describes steps that you can take to remap the element IDs and element handles if you accidentally change the IDs and handles in an environment. In the following steps, the target environment is the environment that you are updating. The source environment is the environment that updates are taken from.

1.  Restore a backup of the target environment that was made before the element IDs and element handles were changed.

2.  Export the updated model from the source environment, and then import the model into the target environment.

For more information about specific steps in this process, see [How to: Export and Import a Model](how-to-export-and-import-a-model.md).

## See also

[Table Inheritance Overview](https://technet.microsoft.com/library/gg881053\(v=ax.60\))

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

