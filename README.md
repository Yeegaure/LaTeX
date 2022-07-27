## LaTeX
Here is my LaTeX summer internship project.

# Introduction
LaTeX is a document preparation system based on a typesetting system called “TeX”, developed by Donald Knuth (Professor Emeritus at Stanford University) in 1974. The word TeX finds its origins in the Greek word for art/skill/craft (and is pronounced “tech” as in “technology.”) Professor Knuth designed TeX to facilitate the creation of documents that incorporated complex mathematical text (Unwalla, 2006).
Nowadays, LaTeX is a powerful instrument to create documents. Unlike usual document (presentations and tables) editors like like Microsoft Word, LibreOffice 
Writer and Apple Pages, when are writing, the writer uses plain text as opposed to the formatted text found in "What You See Is What You Get" word 
processors. 

# The tools that I have used during the project creation
Actually LaTeX is a system which allows to the user to maximally customise his or her document by allowing to import different packages, 
which support a lot of different functions and add tremendous amount of functionality to the document editor.
As an example one could state:

1. Packages that I used:
*  1. *babel* - This package manages culturally-determined typographical (and other) rules for a wide range of languages. A document may select a single 
language to be supported, or it may select several, in which case the document may switch from one language to another in a variety of ways. Babel 
uses contributed configuration files that provide the detail of what has to be done for each language. Included is also a set of ini files for about 
250 languages. It has helped me to type some words in Russian

*  2. *graphicx* - The enxtended package of the package graphics, which aims to give a consistent interface to including the file types that are understood in your output, by use of ‘printer drivers’ 
(now known, simply, as ‘drivers’). The distribution of the package contains several drivers, but others (for example, pdfTEX) are distributed separately. 
The package also offers several means of manipulating graphics in the course of inserting them into a document (for example, rotation and scaling). I have
used this package to insert images in my doncuments: the pdf file and the preentation too.

 * 3. *xcolor* - The package starts from the basic facilities of the color package, and provides easy driver-independent access to several kinds of color 
tints, shades, tones, and mixes of arbitrary colors. It allows a user to select a document-wide target color model and offers complete tools for 
conversion between eight color models. Additionally, there is a command for alternating row colors plus repeated non-aligned material 
(like horizontal lines) in tables. Colors can be mixed like \color{red!30!green!40!blue}. - I used it to make specific specific coloring of my tables,
it has greatly helpoed me to write the coloring code for all the rows in 1 single line.

* 4. *mathtools* - package - provides a series of packages designed to enhance the appearance of documents containing a lot of mathematics. The main backbone is amsmath, 
so those unfamiliar with this required part of the LATEX system will probably not find the packages very useful.Mathtools provides many useful tools for mathematical 
typesetting. For me, it greatly helped when I had to deal with complicated formulae.

* 5. *derivative* - This package makes it easy to write derivatives and differentials consistently with its predefined commands. It also provides a set of 
commands that can define custom derivatives and differential operators. The options follow a consistent naming scheme making them easy to use and 
understand. - This package helped me, when I was typing my formulae, when I needed to type partial derivatives of the second order (in a fraction form).

* 6. amsmath - The principal package in the AMS-LATEX distribution. It adapts for use in LATEX most of the mathematical features found in AMS-TEX; 
it is highly recommended as an adjunct to serious mathematical typesetting in LATEX. - I used it to properly type my mathematical formulae, it was especially
helpful for typing single ares of definition under double integrals of different types.

* 7. esint - The esint package permits access to alternate integral symbols when you are using the Computer Modern fonts. In the original set, several integral 
symbols are missing, such as \oiint. Many of these symbols are available in other font sets (pxfonts, txfonts, etc.), but there is no good solution if you want 
to use Computer Modern. - It greatly helped me, when I was writing double integrals over closed lines.

* 8. esint - inputenc The package translates various standard and other input encodings into a ‘LATEX internal language’. The internal language is expressed entirely in 
TEX’s  base encoding (standard ASCII printable characters, carriage control tokens and TEX control sequences, the latter mostly defined by LATEX). - I have 
nothing to say about this package, it is the must have for all projects in Latex

* 9. *wrapfig* - Allows figures or tables to have text wrapped around them. Does not work in combination with list environments, but can be used in a parbox or minipage, and in twocolumn format. Supports the float package. - I used to make my presentation slides look better and to be able to put an image on a document, which has already much text on it.

2. Special 'Blocks that i have included in my works:
* 1. \begin{titlepage} ... \end{titlepage} - to create the page with data about my project and its author - me
* 2. \begin{abstract} ... \end{abstract} - to create a piece of text that serves as an some kind of an introduction for my paper
* 3. \tableofcontents ... \section{#1} ... \subsection{#1} ... \subsection{#2} ... \subsection{#3} ... \section{#2} ... \section{#3} ... I really liked this tool, it atomatically adds sections and subsections to the table of contents that is placed in the begnning of the paper. It also places the number of the page where these sections are located, really useful in my opinion

3. Different types of formatting:
* 1. \textit{}  - Used to produce text-mode material in italics within {}
* 2. \textbf{} - Used to produce text-mode material in bold within a {}
* 3. \LARGE{} - Used to produce text-mode material in large size within a {}
* 4. \little{} - Used to produce text-mode material in small size within a {}
* 5. \normalize{} - Used to produce text-mode material in normal size within a {}
* 6. \huge{} - Used to produce text-mode material in huge size within a {}
* 7. \underline{} - Used to produce text-mode material in underlined within a {}

4. Several ways of making lists:
* 1. ordered liists: 
  \begin{enumerate}
	                        
   \item 1
		                       
   \item 2
		   
   \item 3
		  
   \item 4
		  
   \item 5
		 
   \item 6
		    
   \end{enumerate}
     => it is a very helpful tool that makes possible to ennumerate items from the list
     
* 2. unordered lists: \begin{itemize}
	                        
  \item 1
		                       
  \item 2
		   
  \item 3
		  
  \item 4
		 
  \item 5
		 
  \item 6
		    
 \end{iteize}
     => it is a very helpful tool that makes possible just ot list items from the list
     
 * 3. nested lists: 
       \begin{enumerate}

	     \item #1
  
       \begin{itemize}[noitemsep]
        
	     \item #1
          
       \item #2
	        
       \item #3
	        
       \item #4
	        
       \item #5
	    
       \end{itemize}
	    
	
  
  
       \item #2
	    
       \begin{itemize}[noitemsep]
	    
       \item #1
	    
       \item #2
	    
       \item #3
	    
       \item #4
	    
       \item #5
	        
	     \end{itemize}
	    
	
        \end{enumerate}

      => this is a nested list, basically a list, which contains other lists in it, which can be either ordered and / or unordered
 
5. how to create tables
    * 1. here is an example of a table that I have created in my project:
   
    \begin{table}[h!]
   
   \centering
   
   \rowcolors{1}{yellow!20}{yellow!60}
   
   \begin{tabular}{ |c|c|c| }
   
   \hline
	 
   \rowcolor{gray!75} \textbf{name of the company} & \textbf{areas of application} & \textbf{number of employees}\\
	 
   \hline
	 
   Adobe & Databases, IoT devices, machine learning & 22 516\\
	 
   \hline
	 
   Apple & OS, databases, IoT devices, machine learning & 147 000\\
   
   \hline
	 
   Blizzard & Game dev, databases, IoT devices, machine learning & 9 800\\
   
   \hline
   
   Evernote & Databases, IoT devices, machine learning & 201 - 500\\
   
   \hline
   
   Meta & OS, databases, IoT devices, machine learning & 58 604\\
   
   \hline
	 
   Microsoft & OS, databases, IoT devices, machine learning & 181 000\\
	 
   \hline
	 
   Nasa & Databases, IoT devices, machine learning & 17 000\\
	 
   \hline
	 
   Netflix & Databases, IoT devices, machine learning & 9 400\\
   
   \hline
      
   Google & Machine learning, databases, IoT devices & 135 301\\
      
   \hline
    	
   LinkedIn & Databases, IoT devices, machine learning & 16 000\\
    	
   \hline
	
\end{tabular}
    \caption{areas of application of C++}
    \label{tab:my_label}
\end{table}

  => this table is a table, which contains 3 centered columns, every row of it is separated by a line and each column is separated by a vertical line,
  this makes it a table with regular cells, like in escel. Moreover, it is colored in a way, that 2 consecutive rows are of the same color - green but of different shadows of yellow to make the reading easier, here I have used the package *xcolor* to automise the process of coloring of consecutive rows. The tabular environment is the default LATEX method to create tables. You must specify a parameter to this environment; here we use {c c c} which tells LaTeX that there are three columns and the text inside each one of them must be centred. Or you can insted of c use r or l to indicate the alignment of the text in the cells to the right of to the left, respectively.
  
  
6. The citations and references - a way to make a reference o to cite an article that you have found on the internet
    * 1. .\cite{} - a snipped of code that allows to make a citation of a particular scource, it makes a symbol [1] or [any number] near the place where you want to insert the citation and on the last page of the document appears the corresponding number, after which come informatin about the text, so the date of publicatin, its name, the name of the author, the company of the institution, etc. 
     * 2. You can manage your references and bibliography in LaTex using the BibTex system. BibTex allows you to automatically generate and format a bibliography in a LaTeX document. You can do this by storing them in separate BibTeX database files (.bib extension). It cotains the data about the text, that is cited, like the date of publicatin, its name, the name of the author, the company of the institution, etc. For example: 
     
            @article{nah2017international,
     
            title={International organization for standardization (ISO) 15189},
     
            author={Nah, Eun-Hee and Cho, Seon and Kim, Suyoung and Cho, Han-Ik and Stingu, Catalina-Suzana and Eschrich, Klaus and Thiel, Juliane and    Borgmann,     Toralf and Schaumann, Reiner and Rodloff, Arne C and others},
  
            journal={Annals of laboratory medicine},
  
            volume={37},
  
            number={5},
  
            pages={365--370},
  
            year={2017},
  
            publisher={The Korean Society for Laboratory Medicine}
  
            }
            
=> The data is usually taken from the cite option in different articles, found in google scholar and in the main document - .tex you can create the references list on the last page by inserting the following lines: 
            
   \bibliographystyle{plain}
            
   \bibliography{references.bib}

=> Which define the type of the text of the references and the file, where these references will be taken from.


7. The images
    * 1. the insertion of the images is overleaf is a ssimple process - you just download it from your computer memory in a separate folder or as a separate file and you are ready to go. To place the file, you need to create a figure, which will contain your file(s), in this figure you will be able to indicate the path to your file or files, its size, the angle of rotation of it, its position in the document, the progrmm might automatically place the image if it is the oly image or if you have many of them, it might automatically find a way to put them in your document. Actually there is an option to include minipages in your figure, so that it will be easier to handle these images, ofr example I chose to put them in 2 rows, each row fof 3 images represents a so called minipage
    * 2. There is also a way to make the text wrap arounf your image, to do so you will need to include he package: wrapfig, 
    * 3. Here is my code for 6 images, that I have included in pmy presentation:
      
      \begin{figure}[ht]
   
   \centering
   
   \begin{minipage}{0.3 \textwidth}
   
   \includegraphics[width = 1\textwidth]{companies/apple.png}
   
   \caption{Apple}
   
   \label{fig:my_label}
   
   \end{minipage}
   
   \hfill
   
   \begin{minipage}{0.3 \textwidth}
   
   \includegraphics[width = 1\textwidth]{companies/google.png}
   
   \caption{Google}
   
   \label{fig:my_label}
   
   \end{minipage}
   
   \hfill
   
   \begin{minipage}{0.3 \textwidth}
   
   \includegraphics[width = 1\textwidth]{companies/meta.jpeg}
   
   \caption{Meta}
   
   \label{fig:my_label}
   
   \end{minipage}
    
    \\[1cm]
    
    \begin{minipage}{0.3 \textwidth}
   
   \includegraphics[width = 1 \textwidth]{companies/microsoft.png}
   
   \caption{Microsoft}
   
   \label{fig:my_label}
   
   \end{minipage}
   
   \hfill
   
   \begin{minipage}{0.3 \textwidth}
   
   \includegraphics[width = 1\textwidth]{companies/nasa.png}
   
   \caption{Nasa}
  
  \label{fig:my_label}
   
   \end{minipage}
 
 \hfill
  
  \begin{minipage}{0.3 \textwidth}
  
  \includegraphics[width = 1 \textwidth]{companies/roscosmos.jpeg}
  
  \caption{Roscosmos}
  
  \label{fig:my_label}
  
  \end{minipage}

\end{figure}

=> this code disposes 6 images in a matrix of 3 columns and 2 rows, making some additional space between the rows.

8. The equations
    * 1. One among the main advantages of LaTeX over other doc editors is its ability to deal with complicated formulae. It has many packages and allows to use many mathematical symbols to create formulae
    * 2. To demonstrate how does it work, as an example, I have taken the equation from quantum physics:
        
        \begin{equation}
        
        \hat{H} = -\frac{\hbar^2}{2}\sum_{n = 1}^N \frac{1}{m_n}\pdv{^2}{x_n^2}\psi + V\psi
        
        \end{equation}
  
  
  
 9. The Beamer presentation
  * 1. Beamer is a powerful and flexible LaTeX class to create great looking presentations. From my opinion, it is just a bit less user friendly version of Power Point from the Microsoft office. You can make a Beamer slideshow presentation by following these steps: creating the title page, which you can choose out of many template availabel on the internet or you can create one by  yourself, adding a logo, highlighting important points, making a table of contents and adding effects to the slideshow, which will make appear the corresponding slides with names of the section, when you will switch the slides, other sections from the table of contents will, however remain shaded.
  * 2. Here is a part of code that I use to define my presentation slides:
  
       \usetheme{Luebeck}

       \definecolor{burlywood}{rgb}{0.87, 0.72, 0.53}
                      
       \usecolortheme[named = burlywood]{structure}

       \title{LATEX presentation about Ducks}
                      
       \author{Smirnov Egor}
                      
       \date{July 2022}
                      
   * 3. Next the following code will create a table of content and then when you will switch the slides, the corresponding names of frames on a new page will appear before you will pass to the slide with information itself. Here is the code:
                       
        \begin{frame}

        \frametitle{Table of Contents}
                    
        \tableofcontents

        \end{frame}
                        
        => Each next frame will appear automatically.

   * 4. With Beamer it is possible to include \href{} {} provides LaTeX the ability to create hyperlinks within the document. It works with pdflatex and also with standard "latex" used with dvips and ghostscript or dvipdfm to build a PDF file. If you load it, you will have the possibility to include interactive external links and all your internal references will be turned to hyperlinks. The compiler pdflatex makes it possible to create PDF files directly from the LaTeX source, and PDF supports more features than DVI. Here is the code:
   
        \href{https://www.youtube.com/watch?v=8SIiGo3TVKE}{10 hours cartoon dancing duck}
  

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
