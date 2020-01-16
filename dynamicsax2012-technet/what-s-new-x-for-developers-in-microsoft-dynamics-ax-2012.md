---
title: "What's New: X++ for Developers in Microsoft Dynamics AX 2012"
TOCTitle: X++ for Developers
ms:assetid: 13705815-6e30-4a3f-a4f1-81f288f3856d
ms:mtpsurl: https://technet.microsoft.com/library/Gg843765(v=AX.60)
ms:contentKeyID: 35240596
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# What's New: X++ for Developers in Microsoft Dynamics AX 2012 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the new and enhanced X++ features that are available in Microsoft Dynamics AX 2012.

## What is new or changed?

This section provides details about the improvements that were made in X++.

  - .NET Proxies to X++ Classes

  - X++ Attributes

  - New Expression Operators in X++ for Inheritance

  - Events in X++

  - X++ Compiled to .NET CIL is Faster

### ![Gg843765.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg843765.collapse_all(en-us,AX.60).gif").NET Proxies to X++ Classes

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create proxy classes to represent .NET interop to X++.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>A .NET proxy is a .NET managed class that represents a class or table that exists in Microsoft Dynamics AX. Your managed program can call proxy methods, just as your X++ code can call methods on a table or class.</p>
<p>The C# compiler detects errors in your calls to the proxy at compile time. You can use this early-bound programming model to fix errors in your code before the code is run. The internal logic of the proxy class uses the late-bound programming model of .NET Business Connector. However, the tools that automatically generate the source code of the proxy have been rigorously tested.</p></td>
<td><p>Proxy classes enable you to write managed classes that interoperate with your X++ classes, to form a unified application.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/library/gg879799(v=ax.60)">Proxy Classes for .NET Interop to X++</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg843765.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg843765.collapse_all(en-us,AX.60).gif")X++ Attributes

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use X++ attribute classes for metadata.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>X++ classes and methods can now have metadata in the form of attribute classes. An attribute class is any non-abstract class that inherits from the SysAttribute class. Detailed metadata is assigned through the constructor of the attribute class.</p>
<p>Tables and interfaces can also have attribute classes.</p></td>
<td><p>By using attributes, you can associate declarative information with X++ code. After an attribute is associated with a program entity, the attribute can be queried at run time and used in many ways.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/library/gg846588(v=ax.60)">Attributes on X++ Types and Methods</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg843765.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg843765.collapse_all(en-us,AX.60).gif")New Expression Operators in X++ for Inheritance

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use the is operator to test whether X++ objects are a type or a subtype of a specific class.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>The X++ language now has the expression operator is. You use the is operator to test whether an object is a type or a subtype of a specific class or table.</p></td>
<td><p>When the is operator is used, your code can test whether a particular downcast assignment would be valid.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/library/gg843452(v=ax.60)">Expression Operators: Is and As for Inheritance</a>.</p></td>
</tr>
<tr class="even">
<td><p>Use the as operator to make downcast assignments explicit.</p></td>
<td><p>The feature was not supported.</p>
<p>In Microsoft Dynamics AX 2009, downcast assignments were implicit. Flawed X++ code sometimes assigned an object to a variable type that was outside the inheritance hierarchy of the object. This incorrect assignment sometimes caused confusing errors during run time.</p></td>
<td><p>You can use the as operator to make downcast assignments explicit.</p></td>
<td><p>When the as operator is used to make a downcast assignment explicit, the incorrect assignment of the object is prevented during run time. The null value is assigned instead. Therefore, it is easier to diagnose the run-time error.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/library/gg843452(v=ax.60)">Expression Operators: Is and As for Inheritance</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg843765.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg843765.collapse_all(en-us,AX.60).gif")Events in X++

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Implement events and event handling in X++.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>The X++ language now has the delegate keyword. When program conditions meet the programmer's criteria for the event, the X++ code can call the delegate. The delegate then calls all the event handler methods that were subscribed to the delegate.</p>
<p>The members of a class can include both methods and delegates.</p>
<p>You can subscribe methods to a delegate by dragging the methods onto the node for the delegate in the Application Object Tree (AOT). Alternatively, you can subscribe methods to the delegate in X++ code by using the += operator together with the eventHandler keyword.</p>
<p>An X++ event can be handled by event handler methods that are written in either X++ or managed languages such as C#.</p></td>
<td><p>The event programming model can reduce the chance that your customizations are affected by upgrades to your program or to Microsoft Dynamics AX.</p></td>
<td><p>For more information about events and delegates, see the following topics:</p>
<ul>
<li><p><a href="https://technet.microsoft.com/library/gg864037(v=ax.60)">Event Terminology and Keywords</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/gg839762(v=ax.60)">Event Handler Nodes in the AOT</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/gg881685(v=ax.60)">X++, C# Comparison: Event</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Pre-method and post-method events are generated by the system.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>The methods on your X++ class each raise an event immediately before they start. The methods raise another event immediately after they end. These two events offer opportunities for custom code to intervene in the program flow.</p>
<p>The pre-method event handler can modify the parameter values before the values are passed to the method. Before the caller of the method receives the value that is returned by the method, the post-method event handler can modify the return value.</p>
<p>The CalledWhen property of each event handler in the AOT Properties window makes it easy to choose between a subscription to the Pre or Post event of the method.</p></td>
<td><p>The pre-method and post-method events are stable points at which custom code can run.</p></td>
<td><p>For more information about pre-method and post-method events, see <a href="https://technet.microsoft.com/library/gg839762(v=ax.60)">Event Handler Nodes in the AOT</a>.</p></td>
</tr>
</tbody>
</table>


### ![Gg843765.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Gg843765.collapse_all(en-us,AX.60).gif")X++ Compiled to .NET CIL is Faster

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Speed up X++ batch jobs.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>Some X++ batch jobs can now complete in much less time. All X++ code that runs on the AX32.exe client still runs as interpreted p-code. However, all batch jobs now run as Microsoft .NET Framework CIL, which is often much faster than p-code.</p>
<p>The X++ developer must now complete the extra step of compiling X++ p-code to CIL. To compile p-code to CIL, right-click <strong>AOT</strong>, and then click <strong>Add-ins</strong> &gt; <strong>Incremental CIL generation from X++</strong>.</p>
<p>Next, if the installation uses multiple instances of Application Object Server (AOS), all AOS instances must be stopped and then restarted. This causes the AOS instances to load the updated assembly.</p>
<p>Finally, a service or a batch job must run the X++ code that was compiled to CIL. Services and batch jobs now run only as CIL.</p></td>
<td><p>Some batch jobs run much faster as CIL than they did as p-code.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/library/gg839855(v=ax.60)">X++ Compiled to .NET CIL</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[What's New in Microsoft Dynamics AX 2012 for Developers](https://technet.microsoft.com/library/gg845327\(v=ax.60\))

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

