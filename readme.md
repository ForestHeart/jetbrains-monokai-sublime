## THIS IS CUSTOMIZED FORK FROM https://github.com/OtaK/jetbrains-monokai-sublime
#### This version has better PHP support (PhpStorm) for twig, symfony.

This is a port of the Monokai theme from Sublime Text 2 to IntelliJ IDEA-based IDEs. It looks a bit like this:

![Monokai_Sublime screenshot](https://raw.github.com/OtaK/jetbrains-monokai-sublime/master/screenshot.png)

Note: I have created an issue on the Jetbrain's bug-tracker.
The issue is related to selecting text that is highlighted after searching.
Link: http://youtrack.jetbrains.net/issue/WI-9576?projectKey=WI

# Installation

You can manually place the XML file in the correct location, or within PhpStorm go to File -> Import Settings and
locate the included .jar file. This will only import the colour scheme.

To manually install the colour theme, go to Preferences -> Editor -> Colors and Fonts. Create a new color
scheme called "Monokai Sublime".

Click Apply.

Search your hard drive for a file called "Monokai_Sublime.icls"

Replace that file with the one in this github repository.

On Linux the file is located at
`~/.PhpStorm2016.1/config/colors/`

