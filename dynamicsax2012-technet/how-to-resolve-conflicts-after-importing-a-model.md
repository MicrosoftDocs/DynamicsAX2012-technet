---
title: 'How to: Resolve Conflicts After Importing a Model'
TOCTitle: 'How to: Resolve Conflicts After Importing a Model'
ms:assetid: e59cf4ce-460c-48be-92c7-b1f24e49253a
ms:mtpsurl: https://technet.microsoft.com/library/Hh446521(v=AX.60)
ms:contentKeyID: 36956799
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# How to: Resolve Conflicts After Importing a Model 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you import a model into the model store, the resources in the model may have conflicts with resources in other models that are already part of that layer. If you use the push option when importing the model, the conflicting resources will be put into a new conflict model that is located in the patch layer for the current layer in the AOS. This new model will have a name that indicates it contains resources that have caused a conflict. For example the model named **Facility Management (Conflict 1)** contains the resources that caused a conflict when the Facility Management model was being imported.

Often, it is a developer responsibility to help resolve conflicts that occur when a model is imported. Use the following procedure as a general guideline to help you through this process.

## Resolving Conflicts after Importing a Model

### To resolve conflicts after importing a model

1.  Determine whether any conflicts occurred during the model import process.
    
      - If you imported a model from the command line, the results returned from the command will indicate whether conflicts occurred during the import process.
    
      - If you do not know the results of the import process, use the **Models installed** command as described in [How to: View Model Information](how-to-view-model-information.md) to view the list of models that are installed. If you see any conflict models in a patch layer, they will contain the resources that caused the conflict.

2.  Retrieve the list of resources that caused conflicts. Use the view command to see the list of resources in the conflict model. These are the conflicts that you have to resolve. For detailed information about how to list resources in a model, see [How to: View and Verify Contents of a Model](how-to-view-and-verify-contents-of-a-model.md). For example, the following command uses axutil.exe to list resources in the Facility Management (Conflict 1) model:
    
    axutil.exe view /model:"Facility Management (Conflict 1)" /verbose

3.  In the AOT, select a resource that has a conflict. Right-click the resource and choose **Compare**. In the **Comparison** window, click **Compare** to see the differences between the resource in the patch layer and the resource in the main layer.

4.  Resolve the conflict. There are many ways to resolve the conflict, depending on the resource type and the actual conflict. Some of the ways to resolve the conflict include the following:
    
      - Use the information and the available actions from the **Comparison** window to merge changes from the conflict model into an existing layer.
    
      - Make a change in the resource in an existing model in the current layer. For example, if two different models in the layer have modified the same resource, you could consider creating a new “shared” model in the layer that contains a single version of the resource that can be used by both of the other models.
    
      - Switch to the patch layer and modify the resource there. In some cases, this is the easiest way to resolve the conflict.
        

        > [!TIP]
        > <P>You can switch to the patch layer by creating a new configuration with the <STRONG>Microsoft Dynamics AX 2012 Configuration</STRONG> tool. You can also switch to a specific patch layer by using the following command to start Microsoft Dynamics AX:</P>
        > <P>Ax32.exe –AOL=USP</P>



5.  Repeat the conflict resolution process for each resource in the conflict model.

After you have resolved all of the conflicts, consider removing the conflict model from the patch layer. That way, somebody looking at the system will not assume that there are model conflicts that have to been resolved. If you are leaving a resource in the patch layer, move the resource out of the conflict model into another model in the patch layer. Then delete the conflict model.

## See also

[How to: Export and Import a Model](how-to-export-and-import-a-model.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

