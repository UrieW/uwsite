+++
title = 'Ebook Fix Guide'
date = 2026-07-14T02:26:47-05:00
tags = ["guides","formats","fixes"]
categories = ["ebook"]
+++

# How to Fix Epubs in Calibre

# 1. To include fonts in an epub, by default:
--------------
1. Upload .odt into calibre
2. Select 'convert books'
3. Go to look and feel
4. Select 'embed associated fonts in file'
5. Pick 'ok' to convert

## 2. To use the correct anchor in an epub chapter:
----------------
1. Pick target book
2. Pick 'edit book'
3. Pick 'check file'
4. If anchor in toc file is missing in target file, open target file
5. Go to 'anchor#' section
6. Change anchor to correct anchor
7. Check file again

# 3. "stylesheets.css" is missing generic, knockoff standard font family type in target font family section:
-----------------------------------------
1. Pick 'edit book'
2. Pick 'check file'
3. If generic font family keyword type is not there, go to target section
in stylesheets.css
4. Go to 'font-family'
5. If the keyword is not there, leave as is, but put in a comma, a space 
and the keyword before the semicolon
6. Check file again

# 4. book publishers won't take epubs for "class="calibre" being in the html header of each of your epub's .xhtml files:
------------
1. Pick 'edit book'
2. Open target or random .xhtml file in book
3. Select [class="calibre"] entirely
4. Copy it
5. Got to search->find/replace
6. In code editor's resulting find tab, paste copy
7. In second mode tab, pick 'all text files'
8. Pick 'replace all'
9. Check file

