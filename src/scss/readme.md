# Use of Folders in SCSS

## 1. Main.scss folder
In this file all of the files from the scss folders are imported into this file all together. This is the file that gets translated to CSS.
## 2. Utilities folder
This folder contains the variable, mixins, and function files that are used for throughout the whole page.  This folder however are just meant to help you write the scss files, and are not meant to output any css.
### Variable file- Utilities folder
This file is located in the utilities folder and in this file all the variable of what you want to reuse is stored. For example font color, font stacks; this ranges from whatever you consider or want to reuse throughout the whole page.
### Function file- Utilities folder
This file contains functions you want to add and stores them so you can reuse them.
### Mixins file- Utilities folder
This file contains groups of css declarations that lets you establish them so you can reuse thorughout your page. For this file to make a mixin you have to use the @mixin before anything to establish that it is a mixin. For example a group would be @mixin container. With this you can establish the presetted rules that can be adjusted.
## 3. Base Folder
This folder contains the main styles for your code.For example the typography file and reset file.
### Typography file- Base folder
This file contains the styles for your font and rules to be used throughout your page.
### Reset file - Base folder
This file contains your default that it goesif anything happens with ay of the establish font or rules on your page. It would automatically refer to this and use these reset value in case anything happens.
## 4. Components folder
This folder contains widget like features that can be reused like button,navbars,header, carousels, footer, etc.
### Header file- Components folder
This file contains the header and its values.
## 5. Pages folder
The pages folder is for specific pages and their styles that it pertains to. This folder contains the home file, which would be that specific page that has different values then any other page.
### Home File- Pages folder
This home file is a specific file different from the other regular pages so it has different values than any other values.