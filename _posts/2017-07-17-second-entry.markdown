---
layout: post
title:  "Second Entry: Scripting"
date:   2017-07-17 12:45:31
categories: ["blog"]
author: "Lahari Pullakhandam"
---

Abstract: I used Pandoc, Bash scripts, and TeXLive to convert a markdown file of my original poem into multiple output formats (PDF, ODT, DOCX, TXT, HTML).

To get the markdown file into multiple formats I used the general command "pandoc -o $OUTPUTNAME.(file extension) $INPUTFILE", where $OUTPUTNAME and $INPUTFILE were saved as variables.  
I used this code, "$(echo -n $INPUTFILE | head -c -3)" in order to remove the file extension (.md) from the input file name to create the output file. 
The desired file extensions were coded manually for each conversion type. For example, "pandoc -o $OUTPUTNAME.html $INPUTFILE".
I then used echo commands that would tell the user (showing standard output in the terminal while the script ran) what is happening when the commands that converted the files in the script were executing.

This is a link to the repository page: 
[**Source Code, Script, Converted Files**](https://github.com/slahari1/slahari1-convert-documents)  

These are the links to individual files (html, pdf, odt, and docx are automatically downloaded):  
[*original writing*](https://github.com/slahari1/slahari1-convert-documents/blob/master/original_writing.md)  
[*script*](https://github.com/slahari1/slahari1-convert-documents/blob/master/convert_original_writing.sh)  
[*html file*](https://github.com/slahari1/slahari1-convert-documents/raw/master/original_writing.html)  
[*docx file*](https://github.com/slahari1/slahari1-convert-documents/raw/master/original_writing.docx)  
[*pdf file*](https://github.com/slahari1/slahari1-convert-documents/raw/master/original_writing.pdf)  
[*odt file*](https://github.com/slahari1/slahari1-convert-documents/raw/master/original_writing.odt)  
[*txt file*](https://github.com/slahari1/slahari1-convert-documents/blob/master/original_writing.txt)  


