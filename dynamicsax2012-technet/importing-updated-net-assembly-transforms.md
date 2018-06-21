---
title: Importing Updated .NET Assembly Transforms
TOCTitle: Importing Updated .NET Assembly Transforms
ms:assetid: 5055c786-f9f9-4720-970d-ace4219332fa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg861992(v=AX.60)
ms:contentKeyID: 35244192
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Importing Updated .NET Assembly Transforms [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you have imported a transform assembly (DLL) into Microsoft Dynamics AX, you may need to make changes to the assembly. Depending on what type of changes you make, the assembly may or may not need to be imported again. This topic covers the different types of changes you can make to an assembly and what you need to do in Microsoft Dynamics AX to be able to use the new transformation logic in the Application Integration Framework (AIF) pipeline.


> [!NOTE]
> <P>You must be logged into Windows Server as an administrator to add a new transform.</P>



## Changing Code in the Transform Method

If you change code within the Transform method of a transform class, you do not need to import the assembly again if you have already done so. However, in order for the changes to be reflected in Microsoft Dynamics AX, you will need to do the following:

1.  Copy the DLL to the server bin directory. This directory varies depending on your installation, but it may be named something like C:\\Program Files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\Bin

2.  Copy the DLL to the client bin directory. This directory varies depending on your installation, but it may be named something like C:\\Program Files\\Microsoft Dynamics AX\\60\\Client\\Bin

3.  Restart the AOS to load the updated assembly.

## Changing the Namespace or Class Name

If you change the namespace or the class name of a transform class, you do not need to import the assembly again if you have already done so. But you will need to go into the **Manage transforms** form and update the **Class** field as shown in the following steps:

1.  Copy the DLL to the server bin directory. This directory varies depending on your installation, but it may be named something like C:\\Program Files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\Bin

2.  Copy the DLL to the client bin directory. This directory varies depending on your installation, but it may be named something like C:\\Program Files\\Microsoft Dynamics AX\\60\\Client\\Bin

3.  Restart the AOS to load the updated assembly.

4.  Open Microsoft Dynamics AX and type CTRL+SHIFT+W to open a new development workspace.

5.  Select **Tools** \> **Application Integration Framework** \> **Manage transforms**.

6.  Select the assembly in the grid, and in the **Class** field, select the new class.

7.  Type CTRL+S to save the transform.

## Adding a New Transform Class to the Assembly

If you add a new transform class to an assembly and you want to use that new transform in the AIF pipeline, you must re-import the assembly as shown in the following steps.

1.  Copy the DLL to the server bin directory. This directory varies depending on your installation, but it may be named something like C:\\Program Files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\Bin

2.  Copy the DLL to the client bin directory. This directory varies depending on your installation, but it may be named something like C:\\Program Files\\Microsoft Dynamics AX\\60\\Client\\Bin

3.  Restart the AOS to load the updated assembly.

4.  Open Microsoft Dynamics AX and type CTRL+SHIFT+W to open a new development workspace.

5.  Select **Tools** \> **Application Integration Framework** \> **Manage transforms**.

6.  In the **Manage transforms** form, type CTRL+N to add a new transform.

7.  In the **Name** field, enter a unique name of up to 30 characters.

8.  In the **Description** field, enter a description of the transform of up to 1,000 characters.

9.  In the **Type** field, select **.NET Assembly**.

10. Click **Load**, navigate to the assembly that you copied to the client bin directory, and click **Open**.

11. In the **Class** field, select the new class that was added to the assembly.

12. Type CTRL+S to save the transform.

## Renaming the Assembly

If you rename an assembly, you must first delete any transforms that reference the assembly and then re-import them as shown in the following steps:


> [!TIP]
> <P>You should not delete a transform that is used in the AIF pipeline for any port. You should verify that the transform that you delete is not being used in any integration ports.</P>



1.  Open Microsoft Dynamics AX and type CTRL+SHIFT+W to open a new development workspace.

2.  Select **Tools** \> **Application Integration Framework** \> **Manage transforms**.

3.  In the **Manage transforms** form, select the transform you want to delete, and type ALT+F9. When the delete confirmation appears, click **Yes**. You must delete each transform contained in the assembly that you have re-named.

4.  Import the re-named assembly by following the steps in topic [How to: Import a .NET Assembly Transform](how-to-import-a-net-assembly-transform.md)

## See also

[About the AIF Pipeline and Transforms](about-the-aif-pipeline-and-transforms.md)

[Walkthrough: Creating a .NET Assembly Transform](walkthrough-creating-a-net-assembly-transform.md)

[How to: Import a .NET Assembly Transform](how-to-import-a-net-assembly-transform.md)

[Messages and transforms in AIF](messages-and-transforms-in-aif.md)

[Configure processing options](configure-processing-options.md)

