---
title: Wizard for product model creation
TOCTitle: Wizard for product model creation
ms:assetid: 5f11d9f5-642b-4fa8-9c01-fceb64c2a6b9
ms:mtpsurl: https://technet.microsoft.com/library/Aa549114(v=AX.60)
ms:contentKeyID: 36057586
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Wizard for product model creation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use a wizard to create product models. In the **Product models** form, in the **Action Pane**, on the **Models** tab, click **Wizard**.


> [!NOTE]
> <P>This information applies only to Product builder.</P>




> [!NOTE]
> <P>In the <STRONG>Product models</STRONG> form, a wizard option is available. To see this option, from the <STRONG>Product models</STRONG> form, double-click a product model from the list. In the <STRONG>Product models</STRONG> form, click <STRONG>Setup</STRONG> and select <STRONG>Options</STRONG>. A dialog box will appear with a <STRONG>Use wizard when creating</STRONG> check box. If this check box is selected, all new product models will be created by using the wizard. If the check box is cleared, all new product models must be created manually. In the <STRONG>Product models</STRONG> form, in the <STRONG>Action Pane</STRONG>, on the <STRONG>Models</STRONG> tab, click the <STRONG>Wizard</STRONG>.</P>



The wizard guides the user through the following steps:

1.  **Welcome** – Read the information on the page, and then, click **Next \>** to create a product model or click **Cancel** to close the form.

2.  **Product model** – Specify the product model number and type its description.
    
      - If the number sequence for product model identification is enabled, the **Product model number** field is completed automatically. Click **Next \>** to continue.
    
      - If you click **Copy from product model**, a new form will appear. In this form you can select an existing model to copy. Select the one to copy from, and then click **OK**.
        

        > [!NOTE]
        > <P>If you use this option, you do not create the new product model from the beginning. Instead, you copy an existing product model and change it with the help of the wizard.</P>



3.  **Modeling variables** – You can create the modeling variables that will be used in your new product model. If you click **Modeling variables**, the **Modeling variables** form opens, where you can create new variables or change the existing ones. Click **Next \>** to continue.

4.  **Variable group** – You can create the variable groups to display in the user dialog box. If you click **Variable group**, the **Variable group** form will open, where you can create new groups or change the existing ones. Click **Next \>** to continue.

5.  **Modeling tree** – You can create the product model contents. If you click **Product model**, the **Product model** form opens. Use this form to set up the selection of groups, the modeling variables, the modeling tree structure, and the validation rules that are required for product model creation. Click **Next \>** to continue.

6.  **Generate items and dimensions** – You can set up the parameters that will be used when a new item number must be generated for the configured item. Click **Generate items and dimensions** to call the appropriate **Generate items and dimensions** form. Click **Next \>** to continue.

7.  **Compile** – If you click **Compile product model**, the compilation of the product model will be performed. Afterward, an Infolog that displays information about errors will open.

8.  **Test model** – The newly created model can be tested for errors. Click **Test model**. The **Product Builder configuration** dialog box opens. Click **OK** to close it and then click **Next \>** to continue.

9.  **Approve** – The last step is to approve and enable the new product model and select the item that the model will apply to. When you click **Test model**, the **Product model details** form will open. If you use this form, you can also export the model, set up price combinations, graphic parameters, and validation rules.

10. Click **Finish** to finish creating the product model.

  


