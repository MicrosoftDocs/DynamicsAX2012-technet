---
title: Task recorder
TOCTitle: Task recorder
ms:assetid: 5f681f94-d8e7-470b-ac73-94a18ec28f92
ms:mtpsurl: https://technet.microsoft.com/library/Dn497765(v=AX.60)
ms:contentKeyID: 62200077
author: Khairunj
ms.date: 08/27/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Task recorder 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can use Task recorder in Microsoft Dynamics AX to quickly document a business process or task for training or other purposes. You can use Task recorder to create videos or documents in Microsoft Word, Microsoft PowerPoint, and Microsoft Visio. If you are using Task recorder in advanced mode, you can also captures additional metadata that can be packaged and then uploaded to Business process modeler in Microsoft Dynamics Lifecycle Services. The file that you upload includes cross-functional flowcharts and activities that you can modify to identify business requirements and generate implementation artifacts.

## Why are some of the value changes that I recorded not included in the finished document?

If the last step in a recording is a value change, and the form is left open when you stop recording, the value change is not recorded. The recording of a value change is triggered by a change of focus, for example, by selecting another tab in the form or by closing the form. Also, if the same control is changed multiple times without changing focus, only the last change is recorded. To ensure that all of the value changes that you make are included in the finished document, change focus between each value change and close the form as the last step in the recording.

Also, the control types TreeView, HTML, ActiveX, and ListBox are not fully supported in Task Recorder. If you use these controls during recording, you might have to manually add steps that reflect their use by modifying the finished document.

## Why do some of the value changes that I recorded appear multiple times in the finished document?

In forms in which controls are implemented by using a lookup button and a grid that displays possible values, a change of value is recorded multiple times. To remove the duplicate recordings, modify the finished document.

## Why are screen shots missing from the document or presentation that I created?

When you record a task, if you change your focus at a speed that is faster than one second, the changes are recorded, but a screen shot is not taken. During the recording, make sure that you change tabs slowly enough for Task recorder to create a screen shot.

## Why are some of the steps that I recorded not illustrated with a screen shot in the document or presentation?

To include all of the steps that you perform for a task in the document or presentation, you must complete the steps from the application menu. Any steps that are performed from the Microsoft Dynamics AX development Application Object Tree (AOT) are not included in the recording.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Use Task recorder to create documents and other training material](use-task-recorder-to-create-documents-and-other-training-material.md)

[Task recorder update (white paper)](https://www.microsoft.com/en-us/download/details.aspx?id=39353)

  


