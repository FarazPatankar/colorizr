# Colorizr
A simple gem to colorize your terminal output.

## Features Overview
This gem allows you to colorize your terminal output. The colors available are :
- red
- green
- yellow
- blue
- pink
- light_blue
- white
- light_grey
- black

## Usage Instructions
The first step to use the gem is to require it in your ruby file.
`require 'colorizr'`

You can colorize your output using any of the colors available. Example :
`"This is an example output".red`

Other class methods that are available to the user are :
```
String.colors 	#Returns an array of all the available colors
String.sample_colors 	#Prints out examples with all the available colors
```

## Installation Instructions
You can download and unzip this file or you can clone this repo using :
`git clone https://github.com/FarazPatankar/colorizr.git`

Then, change directory into the folder by typing :
`cd colorizr`

Run the following commands :
```
$ gem build colorizr.gemspec
$ gem install colorizr-0.0.2.gem
```