# Selenium IDE Extension: CAT Format 

This is a Firefox plugin that adds formatters to Selenium IDE so that scripts can be exported as CAT sripts.

## Installation

* Open the Selenium IDE (install Selenium ide first, it is a firefox extension)
* Go to Options → Options… → Formats
* Add a new format definition with the name “CAT”
* Copy and paste the contents of the file “catformatter.js” here


## Usage
* Open the Selenium IDE
* Go to Options → Options… → General, check on "Enable experimental features". 
* Choose Options → Format → CAT, Options → Clipboard Format → CAT
* Open cjkweb in firefox browser 
* open Selenium IDE and click record button.
* CAT script will be created according to your operations.


## Useful Ressources
[Blog about this Plugin](http://blog.codecentric.de/en/2012/02/recording-robot-framework-keywords-with-selenium-ide/)


## Supported CAT Setps:
DoLogin
TypeValue
ClickTarget
(to be continue..)



## Some useful resource

* firefox extenstion development: 
** http://kb.mozillazine.org/Getting_started_with_extension_development

* selenium-ide plugin api: 
** http://adam.goucher.ca/?s=The+Selenium-IDE+1.x+plugin+API
** http://www.ministryoftesting.com/2011/09/an-introduction-to-selenium-ide-plugins-2/

* Some formatters sample:
**  There are two ways to add formatter in selenium ide,
***  1) develop a plugin based on  selenium ide, sample:
*** 	https://github.com/brokenthumbs/php-formatter

***  2) use selenium ide's add format function, sample:
***        https://github.com/denschu/selenium-ide-format-robotframework
  
**(here I choose the 2nd way since it's easier)      


* How to debug firefox extension:

** One way is use firefox built-in debugger.

** You need to enable (or create) 2 particular options in about:config for extension debugging to work

***  devtools.chrome.enabled: true
***  devtools.debugger.remote-enabled: true



