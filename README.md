## LaTeX
Here is my LaTeX summer internship project.

# Introduction
LaTeX is a powerful instrument to create documents. Unlike usual document (presentations and tables) editors like like Microsoft Word, LibreOffice 
Writer and Apple Pages, when are writing, the writer uses plain text as opposed to the formatted text found in "What You See Is What You Get" word 
processors. 

# The tools that I have used during the project creation
Actually LaTeX is a system which allows to the user to maximally customise his or her document by allowing to import different packages, 
which support a lot of different functions and add tremendous amount of functionality to the document editor.
As an example one could state:

1. Packages that I used:
> 1. *babel* - This package manages culturally-determined typographical (and other) rules for a wide range of languages. A document may select a single 
language to be supported, or it may select several, in which case the document may switch from one language to another in a variety of ways. Babel 
uses contributed configuration files that provide the detail of what has to be done for each language. Included is also a set of ini files for about 
250 languages. It has helped me to type some words in Russian

  2. *graphicx* - The enxtended package of the package graphics, which aims to give a consistent interface to including the file types that are understood in your output, by use of ‘printer drivers’ 
(now known, simply, as ‘drivers’). The distribution of the package contains several drivers, but others (for example, pdfTEX) are distributed separately. 
The package also offers several means of manipulating graphics in the course of inserting them into a document (for example, rotation and scaling). I have
used this package to insert images in my doncuments: the pdf file and the preentation too.

  3. *xcolor* - The package starts from the basic facilities of the color package, and provides easy driver-independent access to several kinds of color 
tints, shades, tones, and mixes of arbitrary colors. It allows a user to select a document-wide target color model and offers complete tools for 
conversion between eight color models. Additionally, there is a command for alternating row colors plus repeated non-aligned material 
(like horizontal lines) in tables. Colors can be mixed like \color{red!30!green!40!blue}. - I used it to make specific specific coloring of my tables,
it has greatly helpoed me to write the coloring code for all the rows in 1 single line.

> 4. *mathtools* - package - provides a series of packages designed to enhance the appearance of documents containing a lot of mathematics. The main backbone is amsmath, 
so those unfamiliar with this required part of the LATEX system will probably not find the packages very useful.Mathtools provides many useful tools for mathematical 
typesetting. For me, it greatly helped when I had to deal with complicated formulae.

> 5. *derivative* - This package makes it easy to write derivatives and differentials consistently with its predefined commands. It also provides a set of 
commands that can define custom derivatives and differential operators. The options follow a consistent naming scheme making them easy to use and 
understand. - This package helped me, when I was typing my formulae, when I needed to type partial derivatives of the second order (in a fraction form).

 > 6. amsmath - The principal package in the AMS-LATEX distribution. It adapts for use in LATEX most of the mathematical features found in AMS-TEX; 
it is highly recommended as an adjunct to serious mathematical typesetting in LATEX. - I used it to properly type my mathematical formulae, it was especially
helpful for typing single ares of definition under double integrals of different types.

> 7. esint - The esint package permits access to alternate integral symbols when you are using the Computer Modern fonts. In the original set, several integral 
symbols are missing, such as \oiint. Many of these symbols are available in other font sets (pxfonts, txfonts, etc.), but there is no good solution if you want 
to use Computer Modern. - It greatly helped me, when I was writing double integrals over closed lines.

> 8. inputenc The package translates various standard and other input encodings into a ‘LATEX internal language’. The internal language is expressed entirely in 
TEX’s  base encoding (standard ASCII printable characters, carriage control tokens and TEX control sequences, the latter mostly defined by LATEX). - I have 
nothing to say about this package, it is the must have for all projects in Latex

2. 


# Issues encountered during the learning process
During the learning process of the program I have encountered some issues related with the disposition of parts of text, images and other structures on the
page, however finally I understood how does the system of LaTeX work and got used to it. After all the procedures have become much easire and natural.

To edit my LaTeX document, I mostly used an online editor - overleaf. I found it very suitable in my taks, siince it works online, son you do not have to
install anything on your computer. It also provides, an online compiler with useful shortcuts. But I was using a free version of it, so its functionnality
was greatly limited, so to commit my project on Github I had to firstly download it and not to simply commit it from the site. And I di not really like
this part. But the interface of the programm is very uaser oriented, userfrienly and quite intuitive, it is easy to use it to produce great documents with
it. Other editors from the list of suggested editors are either not very beautiful in terms of design or with offlien editre I have encoutered issues with
its installation, since macOS system did not allow to run it, which was quite weird, tbh. I have also tried to create a configuration for latex editing in
Visual Studio Code editor, but it is really not easy to make it to compile pdf files without some 3rd party programms.

# Conclusion
I think that LaTeX is a geat tool for writing scientific texts, articles, reports. It allows great customisability, which makes it to stand out of other
redactors like word, where it is much less comfortable and much more difficult to type scientific texts and especially formulas, because graphycal interface
is much more time taking, compared to the latex "coding" interface, where you have a multitude of packages, which allow you to type basically any possible 
formula.

However, I find that for usual and fast text editing for such purposes as homework, quick notes during the lectures and seminars, LaTeX might not be 
the best choice, for these purposes I will still prefer tools like google docs. Also there are some issues related with the popularity of this method of
editing. It is not very popular, which makes it barely impossible to send texts of the .tex and .bib fromat to ordinary people, because it will barely 
impossible for them to understand and to make changes in the document fast enough to make it efficient. And again, the fact that it is not so popular is
reflected in the absence and / or a very low level of integration of latex in modern ecosystems like in Google, Microsoft and Yandex ecosystems. So for
the communication purposes with my friends and teachers I will still prefer to use more traditional text editors, rather than Latex. Aditionally, in large
ecosystems, companies are developping their products which in future might replace or (partially replace) Latex, so in my humble opinion it might loose
its actuality in the future. But for now it might be very useful to use it, when I will be wirting my term paper and / or some other scientific papers 
in the future.
