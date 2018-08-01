# Changelog

All notable changes to this project will be documented in this file.

## 0.7.4

* Fixed localization of date formats, e.g., \svnToday.

## 0.7.3

* Fixed bug resulting in wrong date for maximal revision (\svnInfoMaxToday).

## 0.7.2

* Fixed documentation: the option for using scrpage2 package is called 
  scrpage. Fixed support for svk.

## 0.7.1

* Fixed \svnMaxToday and introduced \svnInfoMaxToday as an alternative
  name. Improved documentation

## 0.7 

* Added option margin for showing version info in the margins of the document
* Added option svk for supporting the keyword expansion of svk 
* Added new command \svnMaxToday
* fixed the use of fancyhdr for single-sided documents

## 0.6

* Added \svnInfoMinRevision and \svnInfoMaxRevision together with the  
  option "revrange". Also added support for \ in keywords.

## 0.5

* Removed support for LaTeX2HTML and added new command \svnKeyword
  for defining arbitrary svn keywords (e.g. $Author:$)

## 0.4

* Added new package options draft, final, eso-foot, and scrpage
* Fixed problem with `_` in file names

## 0.3  

* Added support for Id-keywords without owner information 
  (fixes a bug reported by Uwe Ziegenhagen)

## 0.2.1

* Added \svnId (suggested by Thomas Weber)

## 0.2

* Removed latex2html build-dependency 

## 0.1

* Initial Version, based on rcsinfo from Dr. Juergen Vollmer
