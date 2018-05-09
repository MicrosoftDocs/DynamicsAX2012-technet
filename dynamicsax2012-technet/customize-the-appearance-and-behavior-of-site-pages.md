---
title: Customize the appearance and behavior of site pages
TOCTitle: Customize the appearance and behavior of site pages
ms:assetid: eb612216-bf56-4a68-acf1-f80a90091a80
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn151160(v=AX.60)
ms:contentKeyID: 53095772
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Customize the appearance and behavior of site pages 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can customize the visual design of the Microsoft Dynamics AX 2012 R2 starter store by modifying certain types of files. Cascading style sheet (CSS) provide the page layouts with styling and formatting. For example, you can change the color of elements on store pages by making modifications to CSS files. For more information, see [Walkthrough: Creating and Modifying a CSS File](http://msdn.microsoft.com/en-us/library/bb398932.aspx).

The Welcome page for the starter store contains a slide show with a counter. This topic shows you how to modify the CSS file for the Welcome page to change the colors that highlight the current slide number.


> [!NOTE]
> <P>You can also change the appearance and behavior of the site by using JavaScript. JavaScript files provide the page layouts with client-side scripting functionality. For more information, see <A href="http://go.microsoft.com/fwlink/?linkid=301739&amp;clcid=0x409">How to: Complete basic operations using JavaScript library code in SharePoint 2013</A>. Typically, files that contain JavaScript for the starter store pages are found in a path that resembles the following:</P>
> <P>…\Program Files\Common Files\Microsoft Shared\Web Server Extensions\15\TEMPLATE\LAYOUTS\Storefront\js</P>
> <P>For more information about how to modify JavaScript in the starter store, see <A href="customize-the-functionality-of-an-online-store.md">Customize the functionality of an online store</A>.</P>



### To update the CSS file for the Welcome Page to change the color of the slide counter

1.  Open a web browser and open the Welcome page for the starter store. Typically, the URL for the Welcome page resembles the following:
    
    http://\<your-server-name\>:40002/sites/RetailPublishingPortal
    

    > [!NOTE]
    > <P>Observe the behavior of the page. A slide show cycles through three pictures representing product categories. In the lower-right-hand corner of the slides, a counter displays the current slide number. The following illustration shows the counter displaying the slide number in the original colors of gray and white.</P>

    
    ![Welcome page displaying original slide counter](images/Dn151160.RetailOnlineStore-Welcome-NoColor(en-us,AX.60).jpg "Welcome page displaying original slide counter")

2.  Navigate to the folders on the computer where the online starter store is deployed. Typically, the path for the folder location for CSS files resembles the following:
    
    …\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\15\\TEMPLATE\\LAYOUTS\\1033\\STYLES\\Storefront

3.  Open the Welcome.css file. You can use Visual Studio or any editor that you prefer. For example, consider the slide show on the Welcome page. That is the first page that you see when you access the store on port 40002. The indicator displays the number of the current slide. In the starter store, these are numbered 1, 2, and 3, and the numbers are white on a black background.
    
    The following code from Welcome.css shows initial values for color and border:
    
        .msax-reel_paging a {
        padding: 5px;
        text-decoration: none;
        color: #fff;
        }
        
        
        .msax-reel_paging a.active {
        font-weight: bold;
        background: #1c2023;
        border: 1px solid #101315;
        -moz-border-radius: 3px;
        -khtml-border-radius: 3px;
        -webkit-border-radius: 3px;
        }
    
    The following table lists the original colors that are used.
    
    <table>
    <colgroup>
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Parameter</p></th>
    <th><p>Element</p></th>
    <th><p>Color Code</p></th>
    <th><p>Color</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>color:</p></td>
    <td><p>Text</p></td>
    <td><p>#fff</p></td>
    <td><p>White</p></td>
    </tr>
    <tr class="even">
    <td><p>border:</p></td>
    <td><p>Border for text</p></td>
    <td><p>#101315</p></td>
    <td><p>Dark grey</p></td>
    </tr>
    </tbody>
    </table>


4.  Modify the values for color and border as shown in the following code to create a display that has text in red (\#f00) and highlights the current slide number in green (\#3c8a3c):
    
        .msax-reel_paging a {
        padding: 5px;
        text-decoration: none;
        color: #f00;
        }
        
        .msax-reel_paging a.active {
        font-weight: bold;
        background: #1c2023;
        border: 1px solid #3c8a3c;
        -moz-border-radius: 3px;
        -khtml-border-radius: 3px;
        -webkit-border-radius: 3px;
        }
    
    The following table lists the new colors you have entered.
    
    <table>
    <colgroup>
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Parameter</p></th>
    <th><p>Element</p></th>
    <th><p>Color Code</p></th>
    <th><p>Color</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>color:</p></td>
    <td><p>Text</p></td>
    <td><p>#f00</p></td>
    <td><p>Red</p></td>
    </tr>
    <tr class="even">
    <td><p>border:</p></td>
    <td><p>Border for text</p></td>
    <td><p>#3c8a3c</p></td>
    <td><p>Green</p></td>
    </tr>
    </tbody>
    </table>


5.  Save and close the file.

6.  Refresh the Welcome page in your initial browser session to see your changes.
    
    The following illustration shows the slide show counter with colors corresponding to the changes you made.
    
    ![Welcome page displaying colors in slide counter](images/Dn151160.RetailOnlineStore-Welcome-Color(en-us,AX.60).jpg "Welcome page displaying colors in slide counter")

## See also

[Cascading style sheet (CSS) files for Retail online store](cascading-style-sheet-css-files-for-retail-online-store.md)

[Overview of the SharePoint 2013 page model](http://go.microsoft.com/fwlink/?linkid=294931&clcid=0x409)

[JavaScript API reference for SharePoint 2013](http://go.microsoft.com/fwlink/?linkid=301741&clcid=0x409)

[Execute basic tasks using the JavaScript object model](http://go.microsoft.com/fwlink/?linkid=301743&clcid=0x409)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

