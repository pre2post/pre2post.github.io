---
title: "Set Up Page"
layout: single
permalink: /docs/setup
sidebar:
  nav: "docs"
---

## Overview of Takes

The _Set Up_ page provides details of the set up (i.e. shot type, camera motion and optional details) along with a summary table of the Takes recorded for the scene and set up.

## Document Take

When initially viewing a new set up for a scene, it will appear as follows:

![](/assets/images/takes-none.png)

The Takes table will minimally show columns for the take number and actions that can be performed (only currently `Edit`). However, if any crew member has been given approval responsibility, then each such responsibility will be represented in its own column.

When selecting the `+` button at the bottom right of the page, a new dialog window will be displayed to capture information about a Take:

![](/assets/images/takes-no-roll.png)

In the above image, the roll has not been specified (which is fine as it is optional). However, if a roll should be specified, then the camera (a letter) can be selected, followed by the card or film roll number:

![](/assets/images/takes-with-roll.png)

At this stage, the take can be triggered in two ways.

1) If a manual clapperboard is being used, then the first _play_ button can be used to start a counter.

2) The app can be used to both announce the take, and then automatically provide a simulated clapperboard. This is triggered using the second _clapperboard with play_ button.

The following image shows the type of information that will be displayed if the second button is pressed:

![](/assets/images/takes-clapperboard.png)

Whichever button has been pressed, once Take has been triggered it will eventually (after clapperboard simulation in the second case) start a counter to track the duration of the Take:

![](/assets/images/takes-counter.png)

At this point, the take can either be _restarted_ (if prematurely triggered) or _stopped_ when the take is completed.

Once stopped, the Take's start date and time will be displayed, along with the duration of the Take. The user will be able to add an adhoc comment with the Take, which may provide some useful information when the Take is later reviewed.

![](/assets/images/takes-add-no-approval.png)

Once the _Add_ button is pressed, the new Take will be added to the set up's table:

![](/assets/images/takes-list-1.png)


## Using Approvals

The app provides a capability for crew members to be responsible for approving a Take in the context of a particular responsibility.

In the project's _Crew_ tab, the crew member can be edited and the _Approval Responsibility_ defined:

![](/assets/images/project-crew-update-approval.png)

When crew members have had their approval responsibilities set, the set up page's Take table will now include columns for each of those approval responsibilities:

![](/assets/images/takes-list-1-with-approval.png)

When a Take has completed, the approvals can be recorded before the Take is added:

![](/assets/images/takes-add-with-approval.png)

A summary of the approvals will then be displayed in the set up's Take table:

![](/assets/images/takes-list-2.png)


