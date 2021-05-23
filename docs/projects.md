---
title: "Projects Page"
layout: single
permalink: /docs/projects
sidebar:
  nav: "docs"
---

## Overview

When the app is first started, the first page the user will see if the Projects page.

This page shows the list of current projects being managed by the app, with the ability to create/import projects, share and delete the projects.

More information about each project can be obtained by selecting (pressing on) the list entry of interest.


## Create Project

To create a new project, select the `+` symbol in the bottom right hand corner of the top level Projects page. This will show the file explorer window. Select the appropriate PDF file representing the script to be associated with the project.

![](/assets/images/projects-new-project.png)

If the name of the script can be extracted from the PDF file, then it will be pre-filled within the name field. Otherwise an appropriate name should be entered.

The dialog box also provides information about the number scenes that were extracted from the document. This should be verified to ensure the correct number have been located. If this is not correct, it is likely that the application has not been able to detect those scenes.

We are continually looking to improve the reliability of the application. If you identify a situation where not all scenes are correctly located, and feel it is an issue with the application rather than a formatting problem with the script, then please feel free to send the script (or a cut down version demonstrating the issue) to **bugs@pre2post.online** with an explanation of the problem.
{: .notice--danger}

## Share Project

To share a project, select the **Share** menu item associated with the project:

![](/assets/images/projects-menu.png)

The app will show the sharing dialog to enable the project to be shared via different platforms. The project is shared as a `.json` file.


## Import Project

Importing is similar to the way a project is created, using the `+` button on the _Projects_ page, except that instead of loading a PDF script you would locate the project's `.json` file.

When the project has been loaded, it will show a dialog box allowing the name of the project to be changed if necessary. The project name must be unique, so if you already have a project with the same name, you will need to modify the name of the imported project.


## Delete Project

To delete a project, select the **Delete** menu item associated with the project:

![](/assets/images/projects-menu.png)

The app will show a dialog to request confirmation before performing the deletion.