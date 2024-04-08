---
content_type: page
description: This section contains help for using different tools required for the
  course - GAMS and Matlab.
draft: false
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: 4ca6007d-93b1-02b1-f1a5-4ff62e698c5a
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
## GAMS Help

There are many useful GAMS resources available to you both on-line and as hard copy. The following links summarize GAMS documentation to get you started.

- {{% resource_link "45365dc7-229d-47af-bff4-b8c2a0ba46f3" "GAMS support" %}}: This is the official GAMS Web site. It provides downloadable documentation, technical information, and a number of useful links. Of particular interest is the {{% resource_link "18d4685c-d7f8-4f88-a6cb-6cb281064ddd" "sample problem" %}}. You can also download .pdf versions of a detailed users manual ({{% resource_link "f869d052-3704-4597-b057-cef4627e1dea" "PDF - 3.1MB" %}}) and a tutorial ({{% resource_link "a3e7b838-c804-42fe-904d-e8a5f9be0bdb" "PDF" %}}). For more extensive documentation see the {{% resource_link "0335eab5-c3a1-45f0-8449-39823c9867c3" "list" %}} provided in the GAMS Web site.
- Obtaining a free demonstration version of GAMS for your PC:

You can obtain a free demonstration (downsized) version of GAMS from the {{% resource_link "a3f969ad-609a-4fc4-98c7-a0d05635cde9" "GAMS download site" %}}. If you go to this site you will be asked to fill out a brief form. After submitting this form you will be sent login information and a password that will enable you to download the demo version. Links to installation notes are provided on the GAMS download site. Additional information about GAMS as well as on-line documentation can be found on the {{% resource_link "45365dc7-229d-47af-bff4-b8c2a0ba46f3" "GAMS home page" %}} or through the GAMS support line support@gams.com.

## MATLAB® Help

### Using MATLAB®

To run MATLAB® from a Windows® PC:

MATLAB® may be started from a shortcut or from the Windows® Start button. This will bring up the MATLAB® **command/desktop window** with the MATLAB® prompt >>.

You can specify the path name that MATLAB® uses to search for program or data files in the **current directory** text box near the top of the command window. You can also save a set of path names that are routinely searched by selecting the `Set Path…` and then `Add Folder…` from the `File` pulldown menu.

Entering MATLAB® commands:

**Interactive mode** - Run individual MATLAB® commands directly from the command window.

**Batch mode** - Run a series of commands (a **program**) all at once. These commands are stored in a text file identified with a .m suffix.

To create or modify program files for batch mode use the MATLAB® **editor**. To start the MATLAB® **editor window** from the main MATLAB® window select `New` and then `M-file` from the `File` pulldown menu in the desktop window or enter the command `edit` from the command line. To edit an existing file select `open` and select the appropriate file or enter `edit` followed by the file name.

A batch mode MATLAB® program can take the form of a **script** or a **function**:

A **script** runs much as if you were typing the program statements in the command window. In particular, the values of all variables are retained in memory and are accessible even after the program has run.

A **function** is similar, except that only designated variables are available outside the function.

You can run a script or function by typing the name of its file (without the .m suffix) in the MATLAB® command window. For example, if your program is stored in the file `myprogram.m` then you run it by entering:

```c
>> myprogram
```

Depending on the display options you chose the results of the computations will be shown in the main MATLAB® window, plotted in a separate **plot window**, or written to another file.

### MATLAB® Resources

Help within MATLAB®:

Typing **helpdesk** at the MATLAB® prompt will bring up the MATLAB® Helpdesk. This is a Web page based version of the MATLAB® documentation/manuals.

Typing **help \[command\]** at the MATLAB® prompt will give you a brief explanation of **\[command\]**.

If you **don't** know what command you are confused about, typing **help** at the MATLAB® prompt will give you a list of categories. Then typing **help \[category\]** will produce a list of commands in **\[category\]**. For example, one of the categories is **graphics**. Typing **help graphics** produces a list of the MATLAB® graphics commands.

{{% resource_link "58315300-c036-43e7-9dc7-bc6f59630143" "MathWorks Homepage" %}}: The makers of MATLAB®. Information on acquiring MathWorks products plus links to documentation, etc.

{{% resource_link "f737914a-3454-413d-8902-d1cc7eabc648" "MathWorks Support" %}}: This is a useful site that has technical information, Web version of Helpdesk, and a downloadable user-library of scripts. Everything you ever dreamed of knowing about MATLAB®, plus you can always email MathWorks.