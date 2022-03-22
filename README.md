# University-of-Electronic-Science-and-Technology-of-China-Doctoral-Dissertation-Overleaf
Well detailed Overleaf Latex version of University of Electronic Science and Technology of China (UESTC) Doctoral Dissertation for International postgraduate students who wish to format their final year thesis using overleaf latex template rather than the traditional methods which can be stressful and challenging.

# Description
The UESTC Thesis overleaf version available to postgraduate International Students has been repeatedly reported to have some bugs by the students and which makes it difficult for international postgraduate students to cope with all the necessary formats. Some of the issues faced are wrong page numbering, interference between roman and arabic numbering, inconsistent page header and unnecessary blank pages. In this repository, I have addressed all those bugs, and re-organized the UESTC Thesis overleaf latex version to suit the requirement for master's thesis format.

# Disclaimer!
This is an independent task and the author of this repository has no cooperation with the authorities of the University of Electronic Science and Technology of China. You are freely permitted to use this for your document formatting.

# Addition
You can always use the following links for any extra formatting:

a) for table generation: https://www.tablesgenerator.com/

b) for equation geeneration: https://latexeditor.lagrida.com/


![Doctoral Cover](https://user-images.githubusercontent.com/61402731/151170321-5f1cd105-82db-4a54-8a92-2d8fbbba9444.png)

Front view of the Master's Thesis

# Structural display of the thesis contents
On opening the 'chapter' folder, each chapter is organized in a file called .tex (eg c2.tex).

On opening the 'pic' folder, each chapter folder has its own folder wherein are attached images/diagrams in any extension format (.png/.jpg).

![environment](https://user-images.githubusercontent.com/61402731/151170750-b7b00c09-d77c-4606-91c4-2cf5bdd3fcff.png)


An image showing how the contents are organized

# Remember:
Kindly note that for the compilation of your work, always run from the 'main_file.tex and click on "Recompile' on a green background located on the right hand side.

New Addition, 2022
2022 UESTC Thesis/Dissertation New Format
In 2022, UESTC made few changes to the Thesis/Dissertation format. These changes are mainly on the style of the 'Table and the Reference style'. I have provided the code to correctly effect the new style of the Table and I have also included a new source file named "thesis-uestc.bst" to handle the new changes to the reference format.

Example 1 of the new Table style
%%%%%%%%%%%%%%%%%%%%%%%%%% TABLE 2 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%% \begin{table}[h!]

\scriptsize

\centering

\caption{The Distribution of Relabeled Data}

\begin{tabular}{cccl}

\toprule

\textbf{Label} & \textbf{Class} & \textbf{Number} & \textbf{Percentage} \

\midrule

0 & No RDR & 548 & 45.6% \

1 & RDR & 652 & 54.4% \

\bottomrule

\end{tabular}

\label{tab3-1-2}

\end{table} %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


![UESTC_Table](https://user-images.githubusercontent.com/61402731/159481332-e51d47b4-0029-426f-afb0-2ffc3bf932cc.png)

