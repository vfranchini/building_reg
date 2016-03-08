# Report Instructions

Last Updated: Jan 21, 2015

Repository for _Another Nargis Strikes Every Day – Post-Nargis Social Impacts Monitoring Five Years On_

Copyrighted Content ©

##Table of Contents

1.  [Summary](#summary)
2.  [Folder Structure](#folder-structure)
3.  [Making Edits](#edits)
4.  [Markdown Format](#markdown)
5.  [Managing Figures, Images & Tables](#figures)
6.  [Committing Changes](#commit)
7.  [Issues & Requests](#issues)
8.  [Notes & Comments](#notes)
9.  [Further Information](#further)


## <a name="summary"><a/>Summary

The purpose of this document is to provide instruction and information into the structure and management of the GAR Reports formatted documents.

## <a name="folder-structure"><a/>Folder Structure

The folders in this repository are structured in a way to make merging documents with the final Indesign file as simple as possible. Each text item is separated into sections so they can be linked and placed within the Indesign file and allow for a consistent structure that will allow you to continue editing the files, and allow us to typeset without needing to worry about any edits or changes you need to make to the text. This will also ensure we all have the latest version of the document for typesetting and editing. 

<img src="/_assets/readme/readme_figure_01.png" title="Folder Structure" />

## <a name="edits"><a/>Making Edits

To make edits to the documents, navigate through the repository above and click through the chapter name and to the document that needs editing. Once you click on the document you would like to edit you will see on the top right hand corner a panel of options where one reads "Edit." Click on "Edit" to make modifications to the document.

<img src="/_assets/readme/readme_figure_02.png" title="Edit" width="350px" />

You can work in full screen mode to make editing clearer and using bigger fonts. 

<img src="/_assets/readme/readme_figure_03.png" title="Full Screen" width="250px" />

To exit out of the full screen mode, click the *Exit Zen Mode* button on the top right hand corner.

<img src="/_assets/readme/readme_figure_04.png" title="Exit Full Screen" width="150px" />

Within the black code window, you can use the **CTRL+F** command for Windows or **⌘+F** command for Windows to Search within the document.

<img src="/_assets/readme/readme_figure_05.png" title="Search" width="450px" />

## <a name="markdown"><a/>Markdown Format

In order to make the files editable through Indesign, the text had to be stripped out of MS Word's stylistic additions and formatting. Indesign assigns styles to text based on utility which is what this format does. Any formatting of text that is not included below will need to be requested.

###Headings

All headings must be separated and removed from the body text in all situations. This will allow for dynamic cross linking, consistent styling of all headings and a clear hierarchy. Under no circumstances can a Heading be simply bolded or underlined, this will mean the Heading will not show up on the Table of Contents.

At this time, only three heading levels are selected to appear in the Table of Contents. Headings are denoted by placing "#" before the heading title. The more "#", the less important the heading:

```
#Heading Level 1    = Title of the Chapter
##Heading Level 2   = Major Chapter Section
###Heading Level 3  = Sub Heading
####Heading Level 4 = Minor Heading not in TOC

And so forth through Level 6
```

###Stylistic Elements (Body text ONLY)

Some items in the text will need to be bolded and italicised. In order to **BOLD** or _Italicise_ and item, you will need to wrap the text that requires this treatment as follows:

```
**BOLD**
_Italicise_
```

###Lists (Ordered & Unordered)

Listed elements will can be denoted as follows:

####Unordered Lists
```
+   Item 1
+   Item 2
+   Item 3
```
Will return:

+   Item 1
+   Item 2
+   Item 3

####Ordered Lists
```
1.  Item 1
2.  Item 2
3.  Item 3
```
Will return:

1.  Item 1
2.  Item 2
3.  Item 3

###Superscripts & Subscripts
Wrap all superscripts as follows:
```
<sup>Superscripted</sup>
```

Wrap all subscripts as follows:
```
<sub>Subscripted</sub>
```
_Take note of the "/" in the second item_

###Additional Reading
Additional information can be found at [http://daringfireball.net/projects/markdown/basics](http://daringfireball.net/projects/markdown/basics)

## <a name="figures"><a/>Managing Figures, Images & Tables

Figures, Images & Tables will be managed through the Shared Dropbox folder. When an image is ready for inclusion into the document it will be removed from the Dropbox folder and into the repository. You can notify us when a figure is ready (meaning that no more changes are expected, and all licenses and authorizations are acquired) using the <a name="issues">Issues & Requests</a> button described below. 

Precedents -- <!ADD INFORMATION>

## <a name="commit"><a/>Committing Changes

Once you are finished with your changes, at the bottom of the page you will see a box that says *Commit Changes*. Type in your update and and additional information you would like to make and then click on the green *Commit Changes* button. Committing the file will update the site, the changes will be saved immediately.

<img src="/_assets/readme/readme_figure_06.png" alt="Github Commit" />

If there is an error, Github will inform you via email of through a pop up when you try to commit. Instructions to fix the error will be included in this message.

## <a name="issues"><a/>Issues & Requests

When requiring an update, change or notification for some aspect of the document, it will be best to use the _Issue_ function. Found on the top right hand corner of the repository page.

<img src="/_assets/readme/readme_figure_07.png" alt="Issue Submit" />

Once on the issue page, all pending issues and requests will be noted. You can add an issue or request by clicking on *"Create a new issue."*

<img src="/_assets/readme/readme_figure_08.png" alt="Create a New Issue" />

A pop up will show where you can write a short description of the issue and a more detailed description. It would be best to assign the Issue to who would be in charge of carrying out the request. You can also attach images, files or objects to the issue by dragging and dropping those attachments into the description field.

<img src="/_assets/readme/readme_figure_09.png" alt="Submit Issue" />

Once you are done, submit the issue and you will be notified when the issue or reuqestis completed.

## <a name="notes"><a/>Notes & Comments

There may be times when there are certain notes and comments that need to be shared with the typesetter. A separate file in each chapter labelled "_notes_" is where all the typesetting notes and placements should be made. The file contains an outline of approximately where the document lays out specific elements including boxes and figures. All Headings, regardless if they appear in the TOC or now will appear there.

When leaving a comment for typesetting, find the closest title area in the notes document and then underneath that section title enter the following to leave a note:
```
<comment>Your Comment Appears Here<comment>
```

In some cases, it might be better to leave comments for typesetting as an issue request (see above) if the comment is broad spanning for the entire document, or if the issue might be hard to describe without referencing the original text. In this case, a screenshot and page number of the original document might be helpful. Please do not leave any comments in the body text file.

## <a name="further"><a/>Further Information

Any questions or general queries / issues with the process not to do with the document itself should be directed to the project administrator. A training session is available at request.
