---
title: "Inserting context information"
parent: "Performance+Tool"
---
The Performance Tool (since version 1.2.1) has a special action to allow context specific information in the Performance Tool. This way you can see data like in the debugger and know which scenarios were chosen.

To add context information use the java action PerformanceTool.PerformanceToolInfoAction in your microflow as shown below.

![](attachments/19956341/20218034.png)             

You can use the info string for the action name and a message string. Optionally you can add 3 mendix objects that have all their attributes added.

***Notes***

1. *The attributes of the Mendix objects are added unsorted.*
2. *No references are added.*
3. *The action message is limited to 4000 characters at the moment.*

This leads to an action in the action list with context information:

![](attachments/19956341/20218032.png)

Details of the Performance Tool info action will look similar to the image below.

![](attachments/19956341/20218033.png)