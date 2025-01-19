+++
title = 'How to Covert an Ebook with Calbre'
date = 2025-01-13T18:51:10-06:00
tags = ["guides","ntml","tools"]
categories = ["ebook"]
+++

# Instructions(Applies to LibreOffice Writer, so far)  

1. Open Calibre

2. Upload ebook ODT to Calibre

3. Click on odt

4. Click edit metadata

5. Edit with book details

6. Click okay

7. With book selected, click convert book

8. Go to epub output

9. Set the epub version to 2

10. Convert the book to epub.

------------------------------------------------------------ 

If any publishers give you a fight, do this:  

------------------------------------------------------------  

11. With book selected, click edit book

12. Upload your font to the book

13. Create a new font family with the font 
in mind, in stylesheets.css

14. Point all font family calls of the
font in stylesheets.css to the exact one
you just made

15. Delete the code "calibre," its callback and its 
quotation marks in each of your book's pages,
in the "xml" or "html" tag

16. Save the document

