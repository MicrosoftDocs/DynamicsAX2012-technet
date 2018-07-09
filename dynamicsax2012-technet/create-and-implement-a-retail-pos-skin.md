---
title: Create and implement a Retail POS skin
TOCTitle: Create and implement a Retail POS skin
ms:assetid: 9084b4f5-9cbe-4d83-bdb1-00608f307336
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ937979(v=AX.60)
ms:contentKeyID: 50950767
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Create and implement a Retail POS skin [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can change the look and feel of Microsoft Dynamics AX for Retail POS registers by creating new Retail POS skins. To create or modify existing Retail POS skins, you must obtain a license from [DevExpress](http://www.devexpress.com/). Retail POS uses DXExperience Winforms created by DevExpress. You can develop your own forms without using DevExpress, but it is recommended you use these to maintain a consistent look and feel.

### Creating a new skin

1.  Go to the SkinEditor tool, which is typically found at \<root\>\\Program Files (x86)\\DevExpress 2011.2\\Components\\Tools\\Windows Forms (where 2011.2 is the version number of the product). Double-click the SkinEditor icon to launch the tool.

2.  ![CreatingNewRetailPOSSkinProject](images/JJ937979.CreatingNewRetailPOSSkinProject(en-us,AX.60).png "CreatingNewRetailPOSSkinProject")
    
    Click **File**-\>**New** to open the **New Project** window.

3.  Set the **Project Name:** field to MyFirstCustomSkin.

4.  Change the **Template Skin:** field from **DevExpressStyle** to **Office 2010 Blue** using the dropdown arrow.

5.  Set the **Skin Name:** to MyFirstCustomSkin and click the **OK** button. Your new skin project is now loaded within the SkinEditor tool, which contains a list of UI elements called Products. For the remainder of this topic, Products will be referred to as controls.
    
    ![NewSkinPropertyOptions](images/JJ937979.NewSkinPropertyOptions(en-us,AX.60).png "NewSkinPropertyOptions")

### Setting color properties on your new skin

1.  The UI elements that ship with Retail POS use only a subset of the controls and properties available in DevExpress SkinEditor. They are listed in the following table:
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>UI element</p></th>
    <th><p>Navigation path</p></th>
    <th><p>Property</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>TabPane background</p></td>
    <td><p>Tab &gt; TabPane</p></td>
    <td><p>SolidImageCenterColor</p></td>
    </tr>
    <tr class="even">
    <td><p>TabPane font</p></td>
    <td><p>Tab &gt; TabPane</p></td>
    <td><p>ForeColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Form background</p></td>
    <td><p>Common &gt; Group Panel</p></td>
    <td><p>SolidImageCenterColor</p></td>
    </tr>
    <tr class="even">
    <td><p>Label font</p></td>
    <td><p>Common &gt; label</p></td>
    <td><p>ForeColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Group panel font</p></td>
    <td><p>Common &gt; GroupPanel &gt; NoBorder</p></td>
    <td><p>ForeColor</p></td>
    </tr>
    <tr class="even">
    <td><p>Status bar center</p></td>
    <td><p>Bars &gt; LinkBorderPainter</p></td>
    <td><p>SolidImageCenterColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Status bar inner</p></td>
    <td><p>Bars &gt; StatusBar</p></td>
    <td><p>SolidImageCenterColor</p></td>
    </tr>
    <tr class="even">
    <td><p>Status bar border</p></td>
    <td><p>Bars &gt; StatusBar</p></td>
    <td><p>BackColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Link border</p></td>
    <td><p>Bars &gt; LinkBorderPainter</p></td>
    <td><p>&lt;imagefile&gt;</p></td>
    </tr>
    <tr class="even">
    <td><p>Form background</p></td>
    <td><p>Common &gt; GroupPanel</p></td>
    <td><p>BackColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Form header</p></td>
    <td><p>Common &gt; GroupPanel</p></td>
    <td><p>ForeColor</p></td>
    </tr>
    <tr class="even">
    <td><p>Grid ColumnHeader</p></td>
    <td><p>Grid &gt; Header</p></td>
    <td><p>SolidImageCenterColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Grid ColumnHeader Left</p></td>
    <td><p>Grid &gt; Header &gt; Left</p></td>
    <td><p>SolidImageCenterColor</p></td>
    </tr>
    <tr class="even">
    <td><p>Grid ColumnHeader Right</p></td>
    <td><p>Grid &gt; Header &gt; Right</p></td>
    <td><p>SolidImageCenterColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Grid ColumnHeader font</p></td>
    <td><p>Grid &gt; Header</p></td>
    <td><p>ForeColor</p></td>
    </tr>
    <tr class="even">
    <td><p>Grid Grid Line</p></td>
    <td><p>Grid &gt; GridLine</p></td>
    <td><p>BackColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Grid Row Font</p></td>
    <td><p>Grid &gt; GridRow</p></td>
    <td><p>ForeColor</p></td>
    </tr>
    <tr class="even">
    <td><p>Grid Row Background</p></td>
    <td><p>Grid &gt; GridRow</p></td>
    <td><p>BackColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Grid EmptyAreaBackground</p></td>
    <td><p>Grid &gt; GridEmptyArea</p></td>
    <td><p>BackColor</p></td>
    </tr>
    <tr class="even">
    <td><p>Button font</p></td>
    <td><p>Common &gt; Button</p></td>
    <td><p>ForeColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Button DisabledFont</p></td>
    <td><p>Common &gt; Button</p></td>
    <td><p>DisabledText</p></td>
    </tr>
    <tr class="even">
    <td><p>Button Background</p></td>
    <td><p>Common &gt; Button</p></td>
    <td><p>SolidImageCenterColor</p></td>
    </tr>
    <tr class="odd">
    <td><p>Grid Row Comment</p></td>
    <td><p>Grid &gt; GridPreview</p></td>
    <td><p>ForeColor</p></td>
    </tr>
    </tbody>
    </table>


2.  Set the Common \> Control color property to Blue.

3.  Set the Common \> ControlText color property to White.

4.  Click **File**-\>**Save** .

5.  You must now convert your project into an assembly that will be used by Retail POS. Click **File**-\>**Create Assembly**. You should see a confirmation dialog similar to the following:
    
    ![SkinAssemblyConfirmation](images/JJ937979.SkinAssemblyConfirmation(en-us,AX.60).png "SkinAssemblyConfirmation")
    
    Typically, newly generated skin assemblies are placed in the \<root\>:\\Users\\\<username\>\\Documents\\My DXSkins\\ directory. There will be a folder beneath that directory with the same name as your skin, in this case MyFirstCustomSkin. Inside that folder, you will find a MyFirstCustomSkin.dll.

## Launching Retail POS with your new skin

In order for Retail POS to load your new skin, you must place the skin assembly in the Retail POS runtime folder. Copy the MyFirstCustomSkin.dll to the Skins folder underneath the Retail POS runtime directory.

You also need to make Retail POS aware of your new skin.

### Using Commerce Data Exchange: Synch Service

1.  Open Microsoft Dynamics AX for Retail Headquarters and go to **Retail**-\>**Setup**-\>**POS**-\>**Profiles**-\>**Visual Profiles**.

2.  Right-click the **Theme** dropdown and click **View Details**.

3.  Click the **New** button and set the **POS skin name** field to MyFirstCustomSkin.

4.  Close the **POS skins** form and with the **POS visual profiles** form still open, set the **Theme** dropdown to MyFirstCustomSkin. Close the form.

5.  Go to **Retail**-\>**Periodic**-\>**Data Distribution**-\>**Distribution Schedule**. Select the **N-1090** job and then click the **Run directly** button. This will synch the new skin to Retail POS. You can run the following query against the AXRetailPOS database to make sure this procedure worked:
    
        SELECT POSSKINNAME, * from RetailVisualProfile

6.  Launch Retail POS and your new skin’s visualization effects should display similar to the following image.
    
    ![NewPOSSkin](images/JJ937979.NewSkin(en-us,AX.60).png "NewPOSSkin")

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

