---
title: Define the look and feel of mobile device displays
TOCTitle: Define the look and feel of mobile device displays
ms:assetid: 837eb722-acda-423a-974c-4d3fac2bc002
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553175(v=AX.60)
ms:contentKeyID: 62200110
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- color
- display
- menu
- keyword
- text
- Forms.WHSRFColor
- Forms.WHSWorkUserDisplaySettings
- mobile devices
---

# Define the look and feel of mobile device displays 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up the appearance of a mobile device display, and how to map shortcut keys to controls, such as buttons.

## Specify the font color for system messages

You can select the color to use for the text in system-generated messages, such as error messages.

To specify text colors for the system messages, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Mobile device text colors**.

2.  Click **New** to create a new line.

3.  In the **Text** field, select the type of message to define a color for. Each type of message has a different meaning, as described in the following table. It’s a good idea to select a color that indicates the intent or severity of the message. The following table describes the types of messages that are displayed.  
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Message type</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Default</p></td>
    <td><p>Use the default color settings for all messages.</p>
    <div>

    > [!TIP]
    > <P>The default colors are specified by the cascading style sheet for the Windows Mobile Device Portal (WMDP). This is described in the next section in this topic.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p>Error</p></td>
    <td><p>Indicates a problem that a user must resolve before continuing.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Success</p></td>
    <td><p>Confirms that an action was successful.</p></td>
    </tr>
    <tr class="even">
    <td><p>Warning</p></td>
    <td><p>Informs the worker that there either is a problem, or there could be a problem if the worker proceeds, but the worker can continue without resolving the problem.</p></td>
    </tr>
    </tbody>
    </table>


4.  Click **Select text color**. In the **Color** window, select the color to apply by clicking in the palette or by entering the values. Click **OK**.  

## Specify styles, map shortcut keys, and assign a menu

You must specify the cascading style sheet (CSS) that will define the styles for the menu and all forms, and assign the menu to a specific device. Optionally, you can also map shortcut keys to the HTML controls.


> [!NOTE]
> <P>To complete this procedure, you must know the names of the CSS file and the ASPX view file. These files are located on the installation root of the host for the Windows Mobile Device Portal. If you don’t know the file names, ask your system administrator.</P>
> <P>Additionally, if you want to map the controls on the page to shortcut keys on the keyboard, you must know the numeric codes for the keys.<BR></P>



To set up mobile device display settings, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Mobile device** \> **Work user mobile device display settings**.

2.  Click **New** to create a new line.

3.  In the **Name** field, enter a name for the display setting. This should indicate where the device will be used.

4.  Optional: To use the display settings by default, select the **Default** check box.

5.  In the **CSS file** field, enter the file name of the cascading style sheet to use. Include the .css file name extension in the file name.

6.  In the **Mobile device display settings view** field, enter the file name of the ASPX view file to use. Do not include the .aspx file name extension in the file name.

7.  In the **Keyboard shortcut** field, map the key on the keyboard to the button on the mobile device display.  
    

    > [!NOTE]
    > <P>You must use the following syntax to create the mapping:</P>
    > <P>&lt;control name&gt;(&lt;key name&gt;)=&lt;key code&gt;;</P>
    > <UL>
    > <LI>
    > <P>&lt;control name&gt; – The name of the control, for example, a button, that is rendered in HTML.</P>
    > <LI>
    > <P>(&lt;key name&gt;) – The name of the keyboard key that you’re creating the shortcut for.</P>
    > <LI>
    > <P>&lt;Key code&gt; – The numeric character code for the key that you want to use for the shortcut key.</P></LI></UL>



8.  In the **Criteria** field, map the mobile device setting to a particular device.  
    

    > [!NOTE]
    > <P>You must use a .NET regular expression to create the mapping. The expression must consist of three sections that are separated by a vertical bar ( | ), as follows:</P>
    > <P>Request.UserHostAddress=&lt;user host address&gt;|HostName=&lt;user host name&gt;|Request.UserAgent=&lt;user agent&gt;</P>
    > <UL>
    > <LI>
    > <P>&lt;user host address&gt; - A .NET regular expression to match the requestor IP address.</P>
    > <LI>
    > <P>&lt;user host name&gt; - A .NET regular expression to match the network name of the requestor.</P>
    > <LI>
    > <P>&lt;user agent&gt; - A .NET regular expression to match the identification of the browser used by the requestor.</P></LI></UL>
    > <P>The following example enables the use of Internet Explorer 8.</P>
    > <UL>
    > <LI>
    > <P>Request.UserHostAddress=.*|HostName=.*|Request.UserAgent=MSIE\s8\.0</P></LI></UL>



## Define the date format to use on mobile devices

You can extend the list of accepted date formats for each installation. For example, this can be useful if you want to provide a format that makes it easier for a worker to enter a date on a mobile device. The default format for dates is determined by the default language of the user account that the Internet Information Services (IIS) application pool that runs the WMDP uses to access Microsoft Dynamics AX. To change a date format, you must be familiar with regular expressions in the .NET Framework. For more information, see [.Net Framework Regular Expressions](http://go.microsoft.com/fwlink/?linkid=391260).

You can define date formats by editing the Dates.ini file, which is located on the WMDP server in Content\\Settings\\Dates.ini. This file uses .NET regular expressions to determine the date format. The regular expression must contain sub-expressions that create named groups for day, month, and year (DDMMYY), as shown in the following example:

^(?\<day\>\\d{2})(?\<month\>\\d{2})(?\<year\>\\d{2})$

Each of the sub-expressions requires 1-2 digits for the day and month, and 1-4 digits for the year. The following example is a sub-expression that defines a named group for a year, and requires a minimum of two or a maximum of four digits:

(?\<year\>\\d{2,4})

You can specify more than one expression on separate lines in the same file, however, the first expression that is matched is used to parse the date.

## Next step

The next step in the process of setting up mobile devices is to set up user accounts for workers. For more information, see [Set up mobile device user accounts for workers](set-up-mobile-device-user-accounts-for-workers.md).

## Related tasks

[Set up mobile device menus to display work or activities](set-up-mobile-device-menus-to-display-work-or-activities.md)

[Define the types of work orders that a mobile device can process](define-the-types-of-work-orders-that-a-mobile-device-can-process.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

