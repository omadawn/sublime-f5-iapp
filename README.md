f5 iApp plugin for Sublime Text 2
================

## Description

Sublime Text 2 plugin for iApp syntax highlighting

## Installation

Open up a command line in the Packages/ folder of your Sublime user folder and execute the following:

```
# For MacOS
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
git clone https://github.com/bitwisecook/sublime-f5-iapp.git
```

Then modify the syntax specific preferences for this syntax.
First make sure you have an APL syntax file open and Go to:
Preferences -> Settings - More -> Syntax Specific - User
And make sure it looks like this:

```
{
	"extensions":
	[
		"iappp"
	],
	"color_scheme": "/Users/<Your User Name>/Library/Application Support/Sublime Text 2/Packages/<What you named this package>/iappPresentationColor.tmTheme"
}
```

If the file is empty you can simply add the color scheme line within curly braces.

## Known Issues
For Implementations section
Not all keywords included

For Presentation section
Almost all keywords have been accounted for (If you find anything other than group create an issue.)
Some crazy chioces for tokens which need to be cleaned up

Macro syntax isn't really developed
