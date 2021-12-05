# Markdown-to-Pdf

I am trying to finding the best way possible to convert markdown to pdf.

I have explored and found that the first way is to using this site: 

[https://www.markdowntopdf.com/](https://www.markdowntopdf.com/)

But I have not found this site better as margin is very less and text size is very small in the pdf


Then I have found new site:
[https://dillinger.io/](https://dillinger.io/)

Everything is better but I need the pdf file having font-family of text is Times New Roman.\


Then, I have tried using pandoc.
```
>sudo apt install pandoc
>pandoc file_name.md -o filename.pdf
```
For changing the margin:
```
$pandoc input.md -V geometry:margin=1in -o output.pdf
```
It's working.

For changing the size of font:
```
$pandoc input.md -V fontsize=12pt -o output.pdf 
```
It's also working.

[Reference Site](https://stackoverflow.com/questions/23811002/from-markdown-to-pdf-how-to-change-the-font-size-with-pandoc)

And the way, now I am using according to my requirements: 
First convert markdown to pdf using this site:
[https://dillinger.io/](https://dillinger.io/)

Then convert pdf to doc file and then change its font style.
 # 5 Dec, 2021: 
 ## [https://md2pdf.netlify.app/](https://md2pdf.netlify.app/) best site 
 
 
 
 ## TYPORA Software
