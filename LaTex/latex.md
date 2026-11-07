LaTeX Documentation




1\. Introduction



LaTeX is a document preparation system commonly used for creating professional and well-structured documents. It is especially useful for technical and scientific writing because it provides good support for mathematical equations, references, tables, figures, and structured documents.



2\. Basic LaTeX Document



A simple LaTeX document can be written as:



\\documentclass{article}



\\begin{document}



Hello World!



\\end{document}



The "\\documentclass" command specifies the type of document. The content of the document is written between "\\begin{document}" and "\\end{document}".



3\. Document Structure



LaTeX documents can be organized using sections and subsections.



\\section{Introduction}

\\subsection{Background}

\\subsection{Objectives}



\\section{Conclusion}



This helps create a clear hierarchy in the document.



4\. Text Formatting



Common commands can be used to format text.



\\textbf{Bold text}



\\textit{Italic text}



\\underline{Underlined text}



These commands change the appearance of selected text.



5\. Lists



Unordered List --> bullet point



\\begin{itemize}

&#x20;   \\item First point

&#x20;   \\item Second point

&#x20;   \\item Third point

\\end{itemize}



Ordered List --> numbered list



\\begin{enumerate}

&#x20;   \\item First point

&#x20;   \\item Second point

&#x20;   \\item Third point

\\end{enumerate}



Lists are useful for presenting information clearly.



6\. Mathematical Equations



One of the major advantages of LaTeX is its ability to typeset mathematical expressions.



For example: $ a + b = c$ -> it is inline equation.



\\\[

a^2 + b^2 = c^2   -> block of equation print eq. in the center by default.

\\]

Also we can use equation environment for eq. -> \\begin(equation) ..... \\end(equation).



Fractions can be written as:



\\\[

\\frac{a}{b}

\\]



LaTeX can also be used for more complex mathematical expressions.



7\. Tables



Tables can be created using the "tabular" environment.



\\begin{tabular}{|c|c|}

\\hline

Name \& Marks \\\\

\\hline

A \& 90 \\\\

B \& 85 \\\\

\\hline

\\end{tabular}



Tables are useful for presenting structured information.



8\. Figures and Images



Images can be included using the "graphicx" package.



\\usepackage{graphicx}



An image can then be inserted using:



\\begin{figure}

&#x20;   \\centering

&#x20;   \\includegraphics\[width=0.5\\textwidth]{image.png}

&#x20;   \\caption{Sample Image}

\\end{figure}



9\. Packages



Packages provide additional functionality in LaTeX.



For example:



\\usepackage{graphicx}



is used for including images.



Packages are normally included in the preamble, before "\\begin{document}".



10\. Advantages of LaTeX



\- Produces professionally formatted documents.

\- Provides excellent support for mathematical equations.

\- Makes large documents easier to organize.

\- Supports figures and tables.

\- Provides consistent formatting.

\- Is widely used for technical and scientific documents.



11\. What I Learned



Through LaTeX, I learned how to create structured technical documents using commands and environments. I learned about document classes, sections, formatting, lists, equations, tables, figures, and packages.



LaTeX also helped me understand how technical documents can be created systematically instead of manually formatting every element.



12\. Conclusion



LaTeX is a powerful tool for technical and scientific documentation. Its command-based approach provides consistent formatting and makes it particularly useful for academic reports, research papers, mathematical documents, and other technical work.

