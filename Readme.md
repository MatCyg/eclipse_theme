

1. Go to eclipse market place
Help -> Eclipse Marketplace -> Search for Color IDE Pack -> Install all (EditBox can be skipped) -> wait till eclipse install everything -> restart eclipse afterwards

2. Exit eclipse

3. Go to eclipse\plugins\org.eclipse.ui.themes_1.1.0.v20150511-0913\css and copy the content of the css folder (it is advised to make copy before replacing any files)

3. Star eclipse and go to Windows -> Preferences -> Appearance
Choose Windows XP Blue for Light Theme
Choose Dark theme for Dark Theme

Importing Theme
Go to General -> Appearance -> Color Theme -> Import Theme -> Choose tonicTm.theme file -> Choose tonicTheme on the list.

Replace folding icons
Go to eclipse\configuration\org.eclipse.osgi\250\0\.cp\org\eclipse\jface\text\source\projection\images
and replace the content of that folder with content from folding_icons folder 

For the Light Theme it is advised to change the following:

General -> Appearance -> Colors and Fonts -> Basic (in the list on the right) -> Content Assist background color -> Edit -> Use [240 240 240]
General -> Appearance -> Editors -> Click on Text Editors 
in the bottom window choose Background color and set to [240 240 240]

Run/Debug -> Console -> Background color -> choose [240 240 240]


There is also a way to make scrollbars in eclipse dark by using Windows high contrast theme. I cannot repeat a way of doing this now. Will try to update this in the future.