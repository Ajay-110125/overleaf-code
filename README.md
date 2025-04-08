# overleaf-code


\documentclass{resume} % Use the custom resume.cls style

\usepackage[left=0.4in,top=-0.1in,right=0.4in,bottom=0.4in]{geometry} % Document margins
\usepackage{hyperref} % For hyperlinks
\usepackage{fontawesome} % For icons
\usepackage{xcolor} % For color customization

% Define color for contact information
\definecolor{contactcolor}{HTML}{0000ff} % Blue color for phone number and email

\begin{document}

% Contact information
\noindent
\begin{minipage}[c]{\textwidth}
    \centering
    {\huge \scshape AJAY VATUPALLI} \\ % Name without \vspace{}
    \vspace{3pt} % Adjust the spacing here as needed
    \textcolor{contactcolor}{\raisebox{-0.1\height}{\faPhone\ 9392355921}} \hspace{10pt}
    \textcolor{contactcolor}{\href{mailto:ajayvatupalli7@gmail.com}{\faEnvelope\  ajayvatupalli7@gmail.com}} \hspace{10pt}
    \textcolor{contactcolor}{\href{https://www.linkedin.com/in/ajayvatupalli}{\faLinkedin\  LinkedIn}} \hspace{10pt}
    \textcolor{contactcolor}{\href{https://github.com/Ajay-110125}{\faGithub\  GitHub}} \hspace{10pt}
    \textcolor{contactcolor}{\href{https://ajay-110125.github.io/personal_portfolio/}{\faPaperclip\  Portfolio}}
\end{minipage}

% OBJECTIVE
\begin{rSection}{Summary}
I am a technology enthusiast pursuing a B.Tech in Artificial Intelligence and Machine Learning. With a strong foundation in programming and data analytics, I have successfully completed projects focused on sales analysis and web development. I am eager to apply my skills in a challenging position to contribute to organizational success and to further develop my expertise in the field.
\end{rSection}

% EDUCATION SECTION
\begin{rSection}{Education}
{\bf B.Tech in Artificial intelligence and machine learning} \hfill{\bf 2020 - 2024} \\ Pace institute of technology and sciences\\ 
CGPA: 7.5/10

{\bf Intermediate in MPC}\hfill {\bf 2018 - 2020} \\ Sri Saraswathi junior college\\ 
MARKS: 927/1000
\end{rSection}
% SKILLS SECTION
\begin{rSection}{Skills}

\begin{tabular}{ @{} >{\bfseries}l @{\hspace{5ex}} p{0.7\textwidth} }
Programming &: Python, SQL.\\
Data Analytics &: Excel, Microsoft SQL Server.\\
Data Visualization &: Excel, Microsoft PowerBI.\\
Frontend Web Technology &: HTML, CSS, JavaScript.\\
Version Control &: Git, GitHub.\\


\end{tabular}

\end{rSection}
 % Reduces space by one line
% INternship SECTION
\begin{rSection}{EXPERIENCE}
\textbf{Intern - Web Development by Code Tantra}\hfill {\bf Jul 2022 - Aug 2022}
\begin{itemize}
    \itemsep -7pt
    \item Developed fundamental skills in web development using HTML5, CSS, JavaScript
    \item Built small-scale projects and contributed to open-source repositories demonstrating coding skills and problem-solving abilities
\end{itemize}

\end{rSection}
% PROJECTS SECTION
\begin{rSection}{Projects}
\textbf{Pizza Sales Report}
\begin{itemize}
    \itemsep -9pt
    \item Project to analyze pizza sales and improve sales strategies
    \item Analyzed performance of different pizza types, peak sales times, and customer preferences
\item Collected and analyzed sales data from the restuarants POS system over a specific period.
\item Created visual reports (charts, tables) to highlight trends and patterns
\item Identified that the Thai Chicken pizza was the best-seller and peak sales occurred on weekends
  \href{https://github.com/Ajay-110125/PIZZA-SALES-REPORT/blob/main/README.md}{(Project Link)}
  
\end{itemize}

\textbf{Electronics Furniture Store Sales Report}
\begin{itemize}
    \itemsep -9pt
    \item Project to analyze sales data for an electronics furniture store
    \item Analyzed data to find the most selling products and frequency of sales locations
    \item Created visual reports (charts, tables) to highlight trends in sales data
    \item Identified that laptops and 4K LED TVs contribute most to revenue, with specific sales trends
  \href{https://github.com/Ajay-110125/ELECTRONICS-FURNITURE-STORE-SALES-REPORT/blob/main/README.md}{(Project Link)}
  
\end{itemize}

\textbf{Sports Website}
\begin{itemize}
    \itemsep -9pt
    \item A simple sports website delivering sports information and updates
    \item Developed a basic sports website providing detailed information on teams and players
    \item Provided latest sports news, match updates, player statistics, and event schedules
  \href{https://github.com/Ajay-110125/SPORTS-WEBSITE/blob/main/README.md}{(Project Link)}
  
\end{itemize}


\end{rSection}

% CERTIFICATIONS SECTION
\begin{rSection}{Certification}

\begin{itemize}
    \itemsep -9pt
    \item Python fundamentals part 1 \& part 2 course offered by Infosys Spring Board
    \item Certification for completion of HTML Training provided by Spoken Tutorials project at IIT Bombay


\end{itemize}

\end{rSection}

\end{document}
