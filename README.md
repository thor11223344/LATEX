1)
\documentclass{article}
\usepackage{fancyhdr}% Header and Footer
\pagestyle{fancy}
\fancyhf{} % Clear default header and footer
\fancyhead[c]{My First Program}
\fancyfoot[L]{Global Academy of Technology} % Footer - Institute name and page number
\fancyfoot[R]{\thepage}
\begin{document}
\thispagestyle{fancy}
% Section 1
\begin{center}
\section*{Introduction}
\end{center}
\section{Computer}
A computer is an electronic machine that accepts data as input, processes it according to a set of
instructions, and produces meaningful information as output. It works based on programs that tell it
what tasks to perform. Computers are capable of performing calculations, storing large amounts of
data, and executing complex operations at very high speed and accuracy. They are widely used in
fields such as education, business, healthcare, entertainment, and communication. Because of their
speed, reliability, and versatility, computers have become an essential part of modern life.
% Section 2
\section{Parts of the computer}
The main parts of a computer are divided into hardware components that work together to perform
tasks. The central processing unit (CPU) is the brain of the computer, responsible for processing
instructions and controlling operations. The memory unit stores data and instructions temporarily
(RAM) or permanently (storage devices like hard disks or SSDs). Input devices such as the keyboard
and mouse are used to enter data, while output devices like the monitor and printer display or produce
results. All these parts work together to ensure that the computer functions efficiently and accurately.
\end{document}


2)
\documentclass{article}
\begin{document}
% Title and Author
\title{Sample Abstract}
\author{Thejeswini A M}
\date{\today} 
% Remove date
\maketitle
% Abstract Section
\section*{Abstract}
Computer Science is the study of computers and computational systems. It focuses on the design,
development, and analysis of software and hardware used to process information. The field includes
topics such as programming, data structures, algorithms, artificial intelligence, computer networks,
databases, and cybersecurity. Computer Science plays an important role in modern society by
enabling innovations in communication, healthcare, education, business, and entertainment. With
rapid technological advancements, it continues to evolve and provide solutions to complex real-world
problems. This discipline not only improves efficiency and automation but also contributes to
scientific research and digital transformation across various industries.
\end{document}


3)

\documentclass{report}
\usepackage{graphicx}
\usepackage{geometry}
\geometry{margin=1in}
\begin{document}
\centering
\vspace{1cm}
\textbf{ VISVESVARAYA TECHNOLOGICAL UNIVERSITY}\\
\vspace{0.3cm}
\textbf{ BELAGAVI – 590018}\\
\vspace{1cm}
% VTU Logo
\centering
\includegraphics[width=0.25\textwidth]{vtu_logo.png}\\
\vspace{1cm}
\textbf{PROJECT REPORT}\\
\vspace{0.3cm}
\textbf{ON}\\
\vspace{0.3cm}
\textbf{\textbf{"TITLE OF THE PROJECT''}}\\
\vspace{1cm}
\textbf{Submitted in partial fulfillment of the requirements for the award of the degree of}\\
\vspace{0.3cm}
\textbf{ BACHELOR OF ENGINEERING}\\
\vspace{0.3cm}
\textbf{IN}\\
\vspace{0.3cm}
\textbf{ COMPUTER SCIENCE AND ENGINEERING}\\
\vspace{1cm}
\textbf{Submitted by}\\
\vspace{0.3cm}
\centering\textbf{Student Name}\\
\textbf{USN: 1XX20CS000}
\vspace{0.5cm}
\textbf{Under the guidance of}\\
\vspace{0.3cm}
\textbf{Guide Name}\\
\textbf{Designation}
\vspace{0.5cm}
% VTU Logo
\includegraphics[width=0.25\textwidth]{clg_logo.png}
\vfill
\textbf{Department of Computer Science and Engineering}\\
\textbf{Name of the College}\\
\textbf{Academic Year 2024–2025}
\end{document}

4)
\documentclass{article}
\usepackage{graphicx}
%\usepackage{setspace}
\usepackage{geometry}
\usepackage{ragged2e}
\geometry{left=1.25in,right=1.25in,top=1in,bottom=1in}
\pagestyle{empty}
\begin{document}
\begin{center}
\textbf{\Large GLOBAL ACADEMY OF TECHNOLOGY}\\
\textit{(Autonomous Institute, Affiliated to VTU, Belagavi)}\\
Rajarajeshwarinagar, Bengaluru - 560 098\\[0.5cm]
\textbf{\Large Department of Computer Science and Engineering}\\
% ---- VTU LOGO INSERTED HERE ----
\centering
\vspace{1cm}
\includegraphics[width=3cm]{clg_logo.png}
\vspace{1cm}\\
\textbf{\Large CERTIFICATE}
\end{center}
\vspace{0.5cm}
\justifying
\noindent Certified that the Mini Project Entitled \textbf{``Mini Project Title''}
carried out by \textbf{STUDENT NAME 1}, bearing USN
\textbf{1GAXXCSXXX} and \textbf{STUDENT NAME 2}, bearing USN
\textbf{1GAXXCSXXX}, of Global Academy of Technology,
is a bonafide work submitted in partial fulfillment for the award of the
\textbf{BACHELOR OF ENGINEERING in Computer Science and Engineering}
from Visvesvaraya Technological University, Belagavi during the year
2025--2026. It is certified that all the corrections/suggestions indicated
for Internal Assessment have been incorporated in the Report submitted
to the department. The Project report has been approved as it satisfies
the academic requirements in respect of the project work prescribed for the said Degree.
\vspace{2cm}
\begin{center}
\begin{tabular}{p{6cm} p{6cm}}
Signature of the Guide & { \hspace {2cm} Signature of the HoD} \\
\end{tabular}
\end{center}
\end{document}

5)
\documentclass{article}
\usepackage[a4paper,margin=1in]{geometry}
\usepackage{multirow}
\usepackage{array}
\begin{document}
\begin{center}
\textbf{\Large Student Marks Table}
\end{center}
\vspace{0.5cm}
\begin{table}[h!]
\centering
\begin{tabular}{|c|c|c|c|c|c|}
\hline
\multirow{2}{*}{\textbf{Sl. No}} &
\multirow{2}{*}{\textbf{USN}} &
\multirow{2}{*}{\textbf{Student Name}} &
\multicolumn{3}{c|}{\textbf{Marks}} \\ \cline{4-6}
& & & \textbf{Subject1} & \textbf{Subject2} & \textbf{Subject3} \\
\hline
1 & 4XX22XX001 & Name 1 & 89 & 60 & 90 \\
\hline
2 & 4XX22XX002 & Name 2 & 78 & 45 & 98 \\
\hline
3 & 4XX22XX003 & Name 3 & 67 & 55 & 59 \\
\hline
\end{tabular}
\caption{Student Marks Details}
\end{table}
\end{document}

6)
\documentclass{article}
\usepackage[a4paper,margin=1in]{geometry}
\usepackage{graphicx}
\usepackage{subcaption} % For subfigure environment
\begin{document}
\title{Side-by-Side Figures Example}
\author{}
\date{}
\maketitle
\begin{figure}[h]
\centering
% First Subfigure
\begin{subfigure}{0.45\textwidth}
\centering
\includegraphics[width=\linewidth]{clg_logo.png}
\caption{First Image}
\label{fig:first}
\end{subfigure}
\hfill
% Second Subfigure
\begin{subfigure}{0.45\textwidth}
\centering
\includegraphics[width=\linewidth]{clg_logo.png}
\caption{Second Image}
\label{fig:second}
\end{subfigure}
\caption{Side-by-Side Graphics Using Subfigure Concept}
\label{fig:combined}
\end{figure}
\end{document}

7)
\documentclass{article}
\usepackage{amsmath}
\usepackage{amssymb}
\usepackage[a4paper,margin=1in]{geometry}
\begin{document}
\title{Mathematical Equations}
\author{}
\date{}
\maketitle
\begin{center}
% Left Side Equations (Quadratic Formula Steps)
\begin{minipage}{0.45\textwidth}
\begin{align*}
x &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} \\[6pt]
&= \frac{-2 \pm \sqrt{2^2 - 4(1)(-8)}}{2 \cdot 1} \\[6pt]
&= \frac{-2 \pm \sqrt{4 + 32}}{2}
\end{align*}
\end{minipage}
\hfill
% Right Side Equations (Summation Expressions)
\begin{minipage}{0.45\textwidth}
\begin{align*}
\varphi_0^{\lambda} A_t
&= \sum_{\pi \in C_t} \operatorname{sgn}(\pi)\,
\varphi_0^{\lambda}\varphi_{\pi}^{\lambda} \\[8pt]
&= \sum_{\tau \in C_{\sigma t}}
\operatorname{sgn}(\sigma^{-1}\tau\sigma)\,
\varphi_0^{\lambda}\varphi_{\sigma^{-1}\tau\sigma}^{\lambda} \\[8pt]
&= A_{\sigma t}\varphi_0^{\lambda}
\end{align*}
\end{minipage}
\end{center}
\end{document}

8)
\documentclass{article}
\usepackage[a4paper,margin=1in]{geometry}
\usepackage{amsmath, amsthm}
% Theorem Environments
\newtheorem{theorem}{Theorem}
\newtheorem{lemma}{Lemma}
\newtheorem{corollary}{Corollary}
\theoremstyle{definition}
\newtheorem{definition}{Definition}
\begin{document}
\title{Example of Numbered Theorems, Definitions, Lemmas and Corollaries}
\author{}
\date{}
\maketitle
\section{Basic Number Theory}
\begin{definition}
An integer is called an even number if it is divisible by 2.
\end{definition}
\begin{theorem}
The sum of two even numbers is even.
\end{theorem}
\begin{proof}
Let the two even numbers be $2a$ and $2b$, where $a$ and $b$ are integers.
Their sum is:
\[
2a + 2b = 2(a + b)
\]
Since $2(a+b)$ is divisible by 2, the sum is even.
\end{proof}
\begin{lemma}
If a number is divisible by 4, then it is even.
\end{lemma}
\begin{proof}Let the number be $4k$, where $k$ is an integer.
Then,
\[
4k = 2(2k)
\]
Since it is divisible by 2, the number is even.
\end{proof}
\begin{corollary}
The sum of two numbers divisible by 4 is also even.
\end{corollary}
\end{document}

9)
\documentclass{article}
\usepackage[a4paper,margin=1in]{geometry}
\begin{document}
\section{Introduction}
Artificial Intelligence (AI) has become one of the most important
technologies in modern computing \cite{r1}. Machine learning
techniques are widely used in data analysis and prediction tasks
\cite{r2}. Deep learning models have significantly improved image
and speech recognition systems \cite{r3}. The development of neural
networks has transformed pattern recognition research \cite{r4}.
Many industries now depend on AI-driven automation systems
\cite{r5}.
In addition, AI applications are widely used in healthcare and
education \cite{r6}. Big data analytics plays a crucial role in
training intelligent systems \cite{r7}. Cloud computing supports
large-scale AI deployment \cite{r8}. Cybersecurity systems also use
machine learning algorithms for threat detection \cite{r9}.
Recent research continues to improve algorithm efficiency and
accuracy \cite{r10}.
\section{References}
\begin{thebibliography}{99}
\bibitem{r1} Russell, S. and Norvig, P., Artificial Intelligence: A Modern Approach, 2010.
\bibitem{r2} Mitchell, T., Machine Learning, 1997.
\bibitem{r3} Goodfellow, I., Deep Learning, 2016.
\bibitem{r4} Haykin, S., Neural Networks and Learning Machines, 2009.
\bibitem{r5} Ng, A., Machine Learning Yearning, 2018.
\bibitem{r6} Topol, E., Deep Medicine, 2019.
\bibitem{r7} Mayer-Schönberger, V., Big Data, 2013.
\bibitem{r8} Buyya, R., Cloud Computing, 2011.
\bibitem{r9} Stallings, W., Cryptography and Network Security, 2017.
\bibitem{r10} Murphy, K., Machine Learning: A Probabilistic Perspective, 2012.
\end{thebibliography}\end{document}

10)
\documentclass{article}
\usepackage[a4paper,margin=1in]{geometry}
\usepackage{tikz}
\usetikzlibrary{trees}
\begin{document}
\title{Simple Tree Diagram Using TikZ}
\author{}
\date{}
\maketitle
\begin{center}
\begin{tikzpicture}[
level 1/.style={sibling distance=60mm},
level 2/.style={sibling distance=30mm},
every node/.style={draw, rectangle, rounded corners, align=center}]
\node {University}
child { node {Engineering}
child { node {Computer Science} }
child { node {Mechanical} }
}
child { node {Management}
child { node {MBA} }
child { node {BBA} }
};
\end{tikzpicture}
\end{center}
\end{document}

11)
\documentclass{article}
\usepackage[a4paper,margin=1in]{geometry}
\usepackage{algorithm}
\usepackage{algorithmic}
\begin{document}
\title{Linear Search Algorithm}
\author{}
\date{}
\maketitle
\section{Algorithm Example}
\begin{algorithm}
\caption{Linear Search}\begin{algorithmic}[1]
\REQUIRE Array A of size n, Key element x
\ENSURE Position of x if found
\STATE Set position $\leftarrow -1$
\FOR{$i = 1$ to $n$}
\IF{$A[i] = x$}
\STATE position $\leftarrow i$
\STATE \textbf{break}
\ENDIF
\ENDFOR
\IF{position $\neq -1$}
\STATE Print ``Element found at position'', position
\ELSE
\STATE Print ``Element not found''
\ENDIF
\end{algorithmic}
\end{algorithm}
\end{document}

12)
\documentclass{article}
\usepackage[a4paper,margin=1in]{geometry}
\title{Simple Article Example}
\author{Student Name}
\date{\today}
\begin{document}
\maketitle
\begin{abstract}
This is a simple article document created using LaTeX.
It demonstrates sections, subsections, and basic formatting.
\end{abstract}
\section{Introduction}
LaTeX is widely used for preparing academic documents.
It provides professional formatting for articles and research papers.
\section{Main Content}
\subsection{Advantages of LaTeX}
LaTeX automatically handles numbering, references,
and formatting of mathematical equations.
\subsection{Applications}
LaTeX is used in research papers, reports, books, and theses.
\section{Conclusion}
This is a simple example of an article format in LaTeX.
\end{document}
