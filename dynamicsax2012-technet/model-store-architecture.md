---
title: Model store architecture
TOCTitle: Model store architecture
ms:assetid: a1a5dbe2-04cc-45d4-94c9-5c81be5a84be
ms:mtpsurl: https://technet.microsoft.com/library/Dd362019(v=AX.60)
ms:contentKeyID: 35132792
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Model store architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The model store is the database where all application elements for Microsoft Dynamics AX are stored. Customizations are also stored in the model store. The model store replaces the Application Object Data (AOD) files that were used in earlier versions of Microsoft Dynamics AX.


> [!IMPORTANT]
> <P>In Microsoft Dynamics AX 2012 R2, the model store was moved into a database that is separate from the business database. The name of the model store consists of the name of the business database plus <STRONG>_model</STRONG>.</P>



Layer information and model information are integral parts of the model store. The Application Object Server (AOS) has access to the model store. The AOS manages layer flattening or overshadowing at runtime. That is, when you make an object modification in one layer, the modification overshadows the object on a lower layer at runtime. You could, for example, decide to change a caption on a standard form. The change is saved on your layer only, and the revised—or flattened—form replaces the standard form at runtime. The AOS also provides all the Microsoft Dynamics AX subsystems with model data, such as form rendering, report rendering, and X++ code.

Microsoft Dynamics AX contains sixteen layers. Each layer consists of one or more logical parts called models. A model is generated for each layer. For example, **VAR Model** is the model that the system generates for the VAR layer. The system-generated models let you install and work with the base Microsoft Dynamics AX system. When you customize the Microsoft Dynamics AX program, you can take advantage of the capabilities of models.

The model store is used in the following ways in Microsoft Dynamics AX:

  - **Installation** – During installation, the Setup program uses axutillib.dll to import the .axmodel files from the installation path into the model store.

  - **Upgrade** – During an upgrade, the application files, or AOD files, from the earlier version are imported into the model store, which is the new model. The application files are also imported into the baseline model store, or the model store for the earlier version of the metadata. The baseline model store is similar to the **old** folder in earlier versions of Microsoft Dynamics AX.

  - **Development environment** – In the development environment, developers can continue to use .xpo files to export and import code. Use .axmodel files to migrate application elements from one environment to another, such as from a development environment to a test environment. Export models from the source system to .axmodel files, and then import .axmodel files into the target system.

  - **Run time** – At run time, an Application Object Server (AOS) instance retrieves the application elements, such as forms, reports, and classes, from the model store to respond to client requests.

The following diagram provides an overview of the model store architecture.

![Model store architecture](images/Dd362019.AX6_Sysdocs_model_store_architecture(AX.60).jpg "Model store architecture")

## See also

[System architecture](system-architecture.md)

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[Application Object Layers](http://go.microsoft.com/fwlink/?linkid=192797)

  


