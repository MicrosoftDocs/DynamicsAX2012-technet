---
title: Set up graphic parameters
TOCTitle: Set up graphic parameters
ms:assetid: abba4893-a446-4cb1-a7ca-e3f21066ddc1
ms:mtpsurl: https://technet.microsoft.com/library/Aa498552(v=AX.60)
ms:contentKeyID: 36058914
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up graphic parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Click **Product information management** \> **Common** \> **Product builder** \> **Product models**. On the **Action Pane**, in the **Setup** group, click **Graphic**.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  In the **Default graphic** field, specify the path and the name of the default graphic file.

2.  In the **Path to saved graphics** field, specify the path and the name of the folder where the graphic files should be saved

3.  In the **File name format** field, specify the format to generate the file name. Use the '%n' signs to refer to variables selected in the **Variable** field that will be replaced with the values of the variable in the n position in the variable list. Specify the graphic file name extension, also.

4.  In the **Variable** field, select, in the appropriate order, the variables that influence the item graphical representation and that will be considered when the file name is generated.

5.  Fill in the **Index** field if array variables are used.

6.  In the **Length** field, specify the length of text of the current variable value in the generated file name.

7.  If you will set up intervals for the variable, select the variable and then click **Interval** to open the **Interval** form.
    

    > [!NOTE]
    > <P>You can set up intervals for numeric variables only.</P>



8.  Click CTRL+N. Two lines will appear. In the **Variable** field, a unique identifier of the selected variable will be displayed.

9.  In the **Operator** field, select an operator for the current line.

10. In the **Interval** field, type the value for the interval.
    

    > [!NOTE]
    > <P>The value that you enter in the first line will define the first interval (from 0 to this value). In the second line, set up the next interval. It will be from the value specified in the previous line to the value that you enter in the current line. You can create as many intervals as needed.</P>



11. In the **Value** field, specify the variable value that will be used to generate the file name

  


