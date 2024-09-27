\documentclass[a4paper]{article}
    \usepackage{fullpage}
    \usepackage{amsmath}
    \usepackage{amssymb}
    \usepackage{textcomp}
    \usepackage[utf8]{inputenc}
    \usepackage[T1]{fontenc}
    \usepackage[hidelinks]{hyperref}
    \usepackage[left=2cm, right=2cm, top=2cm]{geometry}
    \usepackage{longtable}
    \textheight=10in
    \pagestyle{empty}
    \raggedright

    %\renewcommand{\encodingdefault}{cg}
%\renewcommand{\rmdefault}{lgrcmr}

\def\bull{\vrule height 0.8ex width .7ex depth -.1ex }

% DEFINITIONS FOR RESUME %%%%%%%%%%%%%%%%%%%%%%%

\newcommand{\area} [2] {
    \vspace*{-9pt}
    \begin{verse}
        \textbf{#1}   #2
    \end{verse}
}

\newcommand{\lineunder} {
    \vspace*{-8pt} \\
    \hspace*{-18pt} \hrulefill \\
}

\newcommand{\header} [1] {
    {\hspace*{-18pt}\vspace*{6pt} \textsc{#1}}
    \vspace*{-6pt} \lineunder
}

\newcommand{\employer} [3] {
    { \textbf{#1} (#2)\\ \underline{\textbf{\emph{#3}}}\\  }
}

\newcommand{\contact} [3] {
    \vspace*{-10pt}
    \begin{center}
        {\Huge \scshape {#1}}\\
        #2 \\ #3
    \end{center}
    \vspace*{-8pt}
}

\newenvironment{achievements}{
    \begin{list}
        {$\bullet$}{\topsep 0pt \itemsep -2pt}}{\vspace*{4pt}
    \end{list}
}

\newcommand{\schoolwithcourses} [4] {
    \textbf{#1} #2 $\bullet$ #3\\
    #4 \\
    \vspace*{5pt}
}

\newcommand{\school} [4] {
    \textbf{#1} #2 $\bullet$ #3\\
    #4 \\
}

% END RESUME DEFINITIONS %%%%%%%%%%%%%%%%%%%%%%%

    \begin{document}
    \vspace*{-40pt}

    

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     Profile
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
  \vspace*{-2pt}
  \begin{center}
    {\Huge \scshape {Afreen S}}\\
    \vspace*{2pt}
    
    \vspace*{2pt}
    \href{mailto:afreenshajahan23@gmail.com}{afreenshajahan23@gmail.com} | \href{tel:+91 7358747381}{+91 7358747381}\\
    \vspace*{2pt}
    \textbf{\href{https://www.linkedin.com/in/afreen-s-6b3882227/}{Linkedin | }}\textbf{\href{https://github.com/Afreen2302}{GitHub | }}\textbf{\href{https://www.hackerrank.com/profile/afreenshaja}{HackerRank}}\\
  \end{center}



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
    %
    %     Education
    %
    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
      \header{Education}
      \vspace{2mm}
      \textbf{Vellore Institute of Technology}\hfill Chennai\\
B. Tech in Electronics and Communication Engineering \hfill 2021 - 2025\\
{\sl CGPA: 9.27}\\
\vspace{2mm}
      \textbf{Bharathi Vidyalaya Senior Secondary School}\hfill Chennai\\
12th - CBSE \hfill 2020 - 2021\\
{\sl Percentage: 94.4}\%\\
\vspace{2mm}
      \textbf{Bharathi Vidyalaya Senior Secondary School}\hfill Chennai\\
Degree in 10th - CBSE \hfill 2018 - 2019\\
{\sl Percentage: 91.8}\%\\
\vspace{2mm}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
    %
    %     Experience
    %
    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
      \header{Experience}
      \vspace{2mm}

      \textbf{Maven Silicon}\textbf{ | Trainee} \hfill Remote | Aug 2023 - Oct 2023\\
          \vspace{-3mm}
\begin{itemize} \itemsep -3pt
\item[] During the training at Maven Silicon, key learnings included VLSI design methodologies covering digital electronics, logic circuits, Verilog HDL, and coding style. The training involved hands-on labs, including an Alarm Clock project, to gain proficiency in Verilog HDL. Additionally, the program covered RISC-V architecture, focusing on its instruction set, RTL design, and a project involving a multi-stage pipeline processor using Verilog HDL. The training was completed with an overall score of A+.
\end{itemize}
      \textbf{Moog India Technology Center (MITC)}\textbf{ | Intern} \hfill Bengaluru | Aug 2023 - Sept 2023\\
          \vspace{-3mm}
\begin{itemize} \itemsep -3pt
\item[] During the internship at Moog India Technology Center, the experience included designing circuits and conducting timing analysis in OrCAD PSpice, working on Op-Amps and a TI processor. The role also involved creating symbols in OrCAD PSpice, designing PCBs in Allegro, and working on schematic design. Additionally, there was exposure to component engineering, focusing on datasheets, obsolescence management, MSL, and RoHS. The internship also included digital design verification, involving code coverage, test case comparisons, and FPGA verification.
\end{itemize}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     Skills
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
  \header{Skills}
  \vspace{2mm}
  \begin{longtable}{p{4cm}p{12cm}}
  Programming Languages: & Python, C, Verilog, MATLAB \\
  Tools / Platforms: & OrCAD PSpice, Allegro PCB Design, Padstack Editor, Cadence, Proteus \\
  \end{longtable}
  \vspace{1mm}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
    %
    %     Projects
    %
    %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
      \header{Projects / Open-Source}
      \vspace{2mm}
      {\textbf{Password Operated Device Control}}\textbf{ | \href{https://github.com/Afreen2302/Password-Operated-Device-Control}{Link}}\hfill{\sl Embedded C, Keil Vision, Proteus}\\
          \vspace{-3mm}
\begin{itemize} \itemsep -3pt
\item[] This project evaluates the effectiveness of various input methods in controlling a device, aiming to enhance security systems.
\end{itemize}
          \vspace*{3mm}
      {\textbf{Voice-based Gender Classification using ML \& DL}}\textbf{ | \href{https://github.com/Afreen2302/Voice-based-Gender-Classification-Using-ML-and-DL}{Link}}\hfill{\sl Python, Machine Learning, Deep Learning}\\
          \vspace{-3mm}
\begin{itemize} \itemsep -3pt
\item[] This project evaluates the effectiveness of various models in classifying gender from voice signals, aiming to enhance gender classification systems.
\end{itemize}
          \vspace*{3mm}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
      %
      %     Certifications
      %
      %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
      \header{Certifications}
      \vspace{2mm}
      • 5G Introductory-Level Certificate recipient - \textbf{\href{https://drive.google.com/file/d/1UFq8ixpGM RptG6f7CIq0NWXlcjTxYYOV/view? usp=drive\_link}{Qualcomm}}\\
\vspace*{1mm}
      • Python Basics - \textbf{\href{https://drive.google.com/file/d/1fwlxIiM4vYfONhcEmabhJ0kxmWty85dS/view?usp=sharing}{authorized by University of Michigan and offered through Coursera}}\\
\vspace*{1mm}
      • Emotional Intelligence - \textbf{\href{https://drive.google.com/file/d/1wEJZySN3hOy\_HOBHU6UA6Kt-jUrR1VZp/view?usp=sharing}{NPTEL}}\\
\vspace*{1mm}
      \vspace{2mm}



    \ 
    \end{document}
