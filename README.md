﻿[![HTL-Grieskirchen](http://www.htl-grieskirchen.net/fileadmin/bilder/logo.png)](http://htl-grieskirchen.net)
# Showcase 2024-25


Click here to open the projects:

====================
# [**List of projects**](https://AlfredDoppler.github.io/HTLGrieskirchenShowcase2024-25/)
====================


The projects in this repository are for demonstration purposes only. 
All copyrights and trademarks belong to their rightful owner.
If there is any problem with any demo just leave a short message.

Many thanks to my student Elias Lexl for the creation of this site.
Additional thanks go to Rene Buchmayr and Alexander Melem for providing the
first solutions of how to run the GIT-repository Web GL games directly in the browser.

@students:
You must enable the Decompression Fallback in the Unity Player settings before creating the WebGL Build:

![CompressionFormat](https://github.com/AlfredDoppler/HTLGrieskirchenShowcase2023-24/assets/19311233/4a6dc6a7-e8ab-48a9-b2dc-d7f980fe5e9c)


After uploading your project to the `projects-folder` update the `projects.json`.

## `projects.json` properties
```
[
    {  
        "title": "project title",
        "folder": "name of the folder",
        "author": "my name",
        "year": "folder name of the year",
        "info": "info about your project",
        "status": "0"
    },
    ...
]
```
### title
Project title

### folder
Name of your project folder

### author
Author(s) of the project

### year
Name of the year (must be the same as the year folder directly in the `projects` folder)

### info
(optional) e.g. your project works in specific versions of a browser
### status
| status  | description        |
| ------: | ------------------ |
| -1      | not working        |
| 0       | partly working     |
| 1       | completly working |

## Create new repository (@AlfredDoppler)
Just copy the `index.html`, `app.json` and `projects.json` to the new repository. There create a new folder called `projects` with subfolders named by year (e.g. 2017_SS) and update the `app.json` with the new values.
### That´s it :)

