
\documentclass[letterpaper,11pt]{article}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}
\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}

\usepackage{tikz}


\usetikzlibrary{svg.path}
\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}
\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
     
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}


\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE %%%%%%%%

\begin{document}

%----------HEADING----------

\begin{center}
    {\Huge \scshape Chetan Chandrakant Biranje} \\ \vspace{1pt}
    Pune, Maharashtra, India \\ \vspace{1pt}
    \small \href{tel:+917070709694}{ \raisebox{-0.1\height}\faPhone\ \underline{+91-7070709694} ~} \href{mailto:chetanbiranje@proton.me}{\raisebox{-0.2\height}\faEnvelope\  \underline{Chetanbiranje@proton.me}}~
\href{https://linkedin.com/in/Chetanbiranje}{\raisebox{-0.2\height}\faLinkedinSquare\ \underline{Linkedin}} ~
 \href{https://github.com/Chetanbiranje}{\raisebox{-0.2\height}\faGithub\ \underline{Github}}~
\href{https://www.hackerrank.com/yourid}{\raisebox{-0.2\height}\faHackerrank\ \underline{HackTheBox}} ~
    \href{https://codeforces.com/profile/yourid}{\raisebox{-0.2\height}\faPoll\ \underline{Portfolio}}
    \vspace{-8pt}
\end{center}

%-----------EDUCATION-----------
\section{EDUCATION}
        \resumeSubHeadingListStart
 \resumeSubheading
             {D. Y. Patil University}{Jun 2025 -- Present (Expected May 2028)}
             {Bachelor of Computer Applications (BCA) } {Mumbai, Maharashtra}
 \resumeSubheading
             {Sant Gajanan Maharaj Rural Polytechnic College}{Jun 2020 -- April 2022}
             {Diploma - Electronics and Telecommunication \textbf{} - \textbf{61\%}} {Kolhapur, Maharashtra}
    \resumeSubHeadingListEnd
        \vspace{-12pt}

%-----------EXPERIENCE-----------
\section{EXPERIENCE}
    \resumeSubHeadingListStart
        \resumeSubheading
            {AI4See private ltd \href{https://drive.google.com/file/d/1qA4JAGjoC0chJ4w-Yw19E_Vuoe90Vvpp/view?usp=drive_link}{\raisebox{-0.1\height}\faExternalLink }}{Nov 2025 -- Present}
            {\underline{Full-Stack Developer (Security-Focused)}} {Remote, India}
    \resumeItemListStart
     
        \resumeItem{Designed web application architecture with OWASP-aligned security controls}
    \resumeItem{Built reusable secure REST API components, reducing vulnerability recurrence by \textbf{30\%}}
    \resumeItem{Integrated SAST/DAST into CI/CD, cutting security debt by \textbf{40\%}}
    \resumeItem{Implemented secure coding practices (input validation, output encoding, parameterized queries)}
    \resumeItem{Performed security code reviews focused on OWASP Top 10 and AuthN/AuthZ flaws}
  \resumeItemListEnd

    \resumeSubheading
            {Codec Technologies \href{https://drive.google.com/drive/folders/14SP84gWcgO-Bzul2uWFy4zqNFZVSkVwZ?usp=drive_link}{\raisebox{-0.1\height}\faExternalLink }}{Nov 2025 -- Dec 2025}
            {\underline{Cyber Security Intern (AppSec) | Python Automation}} {Remote, India}
   \resumeItemListStart
    \resumeItem{Performed manual pentesting of web apps and REST APIs}
    \resumeItem{Identified \textbf{15+ critical/high vulnerabilities} (IDOR, broken access control, JWT misconfig, SQLi, logic flaws)}
    \resumeItem{Executed multi-role authorization testing using \textbf{Burp Suite Pro}}
    \resumeItem{Delivered pentest reports with reproducible \textbf{PoCs} and \textbf{CVSS} scoring}
    \resumeItem{Drove \textbf{95\% remediation} via developer-focused guidance}
  \resumeItemListEnd
\resumeSubHeadingListEnd
\vspace{-12pt}

%-----------PROJECTS-----------
\section{PROJECTS}
    \vspace{-5pt}
        \resumeSubHeadingListStart
  \resumeProjectHeading
    {\href{<https://github.com/ChetanBiranje/<api-security-toolkit-repo>>}{\textbf{\large{\underline{API Security Automation Toolkit}}} \raisebox{-0.1\height}\faExternalLink} $|$ \large{\underline{Python, REST APIs, JWT, Burp Suite API}}}{Jan 2025}
    \resumeItemListStart
    \resumeItem{Built an automated REST API security testing framework (JWT analysis, IDOR detection, fuzzing)}
    \resumeItem{Automated AuthN/AuthZ testing, reducing manual effort by \textbf{30\%}}
    \resumeItem{Integrated API fuzzing into CI/CD with injection payload detection}
  \resumeItemListEnd
  \vspace{-16pt}

  \resumeProjectHeading
    {\href{<https://github.com/ChetanBiranje/<secure-rbac-api-repo>>}{\textbf{\large{\underline{Secure REST API with RBAC}}} \raisebox{-0.1\height}\faExternalLink} $|$ \large{\underline{Node.js, Express.js, MongoDB, JWT}}}{May 2025}
    \resumeItemListStart
    \resumeItem{Implemented JWT-based authentication with refresh tokens and RBAC}
    \resumeItem{Built resource-level authorization with role inheritance}
    \resumeItem{Applied security headers, CORS policies, and rate limiting}
  \resumeItemListEnd
  \vspace{-12pt}

  \resumeProjectHeading
    {\href{https://github.com/ChetanBiranje/365DaysOfApplicationSecurityRoadmap.git}{\textbf{\large{\underline{365 Days Application Security Roadmap}}}
    \raisebox{-0.1\height}\faExternalLink} $|$ \large{\underline{Open Source, Educational}}}{March 2026}
        \resumeItemListStart
    \resumeItem{Authored a 365-day roadmap from beginner to AppSec practitioner}
    \resumeItem{Curated \textbf{100+ free resources} (labs, courses, practice platforms)}
  \resumeItemListEnd
\resumeSubHeadingListEnd
\vspace{-12pt}


%-----------PROGRAMMING SKILLS-----------
\section{TECHNICAL SKILLS}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\normalsize{Security Testing:}}{\normalsize{ Web Application VAPT, API Security Testing, Authorization Testing, Threat Modeling (STRIDE), Security Code Review, Penetration Testing}} \\
     \textbf{\normalsize{Security Tools:}}{\normalsize{ Burp Suite Pro, OWASP ZAP, Postman, Nmap, Metasploit, SQLmap, Wireshark, Nikto}} \\
     \textbf{\normalsize{Programming Languages:}}{\normalsize{ Python, JavaScript, Bash, SQL, PowerShell}} \\
     \textbf{\normalsize{Security Frameworks:}}{\normalsize{ OWASP Top 10, OWASP API Security Top 10, OWASP ASVS, Secure SDLC}} \\
     \textbf{\normalsize{Web Technologies:}}{\normalsize{ Node.js, Express.js, React.js, MongoDB, REST APIs, JWT, OAuth 2.0, RBAC}} \\
     \textbf{\normalsize{DevSecOps:}}{\normalsize{ Docker, Git/GitHub, CI/CD Security Integration, SAST, DAST, Container Security}} \\
     \textbf{\normalsize{Cloud Security:}}{\normalsize{ AWS Security (IAM, S3, EC2), GCP IAM, Azure Security Basics}} \\
     \textbf{\normalsize{Vulnerability Types:}}{\normalsize{ SQL Injection, XSS, CSRF, SSRF, IDOR, XXE, RCE, Authentication Bypass, Authorization Bypass}}
    }}
 \end{itemize}
 \vspace{-15pt}

 %-----------CERTIFICATIONS---------------
\section{CERTIFICATIONS}


$\sbullet[.75] \hspace{0.1cm}$ {\href{https://academy.tcm-sec.com/courses/2631779/certificate?utm_source=student_mailer&utm_medium=email&utm_campaign=issued_certificate_notification}{Linux Fundamentals - TCM}} \hspace{1.6cm}
$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{Java}} \hspace{2.59cm}
$\sbullet[.75] \hspace{0.2cm}${\href{https://credsverse.com/credentials/ca976a28-ab95-4056-a139-72fd1144be7f?preview=1} {SOC Analysts - USLA}}\\


$\sbullet[.75] \hspace{0.2cm}${\href{https://credsverse.com/credentials/dd28ab16-820d-40df-95d5-e8517d872117?preview=1}{Dark Web - USLA}} \hspace{1cm}
$\sbullet[.75] \hspace{0.1cm}$ {\href{https://www.cert.devtown.in/verify/ewI7y}{Application Security Training - DevTown}} \hspace{2.6cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{Microsoft AI Classroom}} \\


$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{\textbf{5 Stars} in \textbf{C++} \& \textbf{SQL} \href{certificateLink.com}{\raisebox{-0.1\height}\faExternalLink }}}\hspace{1.45cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{MongoDB Basics}} \hspace{0.5cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{NodeJS with Express \& MongoDB - Udemy}} \\

\end{document}




%-------------------------
% Resume in Latex
% Author : Abey George
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------


\documentclass[letterpaper,11pt]{article}


\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{tikz}
\usetikzlibrary{svg.path}




\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}






%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}


% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}




% \pagestyle{fancy}
% \fancyhf{}  % clear all header and footer fields
% \fancyfoot{}
% \renewcommand{\headrulewidth}{0pt}
% \renewcommand{\footrulewidth}{0pt}


% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}


\urlstyle{same}


\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}


% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]


% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1


%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}


\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}


\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
     
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}




\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}


\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}


\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}




\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}


%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%




\begin{document}


%----------HEADING----------




\begin{center}
    {\Huge \scshape Your Name is here} \\ \vspace{1pt}
    city,state \\ \vspace{1pt}
    \small \href{tel:+xxxxxxxxxxxx}{ \raisebox{-0.1\height}\faPhone\ \underline{+xx-9999999999} ~} \href{mailto:yourname@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{yourname@gmail.com}} ~
    \href{https://linkedin.com/in/yourid}{\raisebox{-0.2\height}\faLinkedinSquare\ \underline{yourid}}  ~
    \href{https://github.com/yourid}{\raisebox{-0.2\height}\faGithub\ \underline{yourid}} ~
    \href{https://www.hackerrank.com/yourid}{\raisebox{-0.2\height}\faHackerrank\ \underline{yourid}} ~
    \href{https://codeforces.com/profile/yourid}{\raisebox{-0.2\height}\faPoll\ \underline{yourid}}
    \vspace{-8pt}
\end{center}




%-----------EDUCATION-----------
\section{EDUCATION}
  \resumeSubHeadingListStart
    \resumeSubheading
      {College Name}{MM YYYY -- MM YYYY}
      {Degree Name - \textbf{CGPA} - \textbf{xx}}{city, country}
  \resumeSubHeadingListEnd
 
  \resumeSubHeadingListStart
    \resumeSubheading
      {College Name}{MM YYYY -- MM YYYY}
      {Exam Name - Course Name  - \textbf{Percentage} - \textbf{xx\%}}{city, country}
  \resumeSubHeadingListEnd


%------RELEVANT COURSEWORK-------
\section{COURSEWORK / SKILLS}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-2pt, parsep=5pt]
                \item Data Structures \& Algorithms
                \item Operating Systems
                \item Network Security
                \item Database Management System (DBMS)
               \item Artificial Intelligence
                \item OOPS Concept
                \item Web Development
                \item Android Development
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd






%-----------PROJECTS-----------
\section{PROJECTS}
    \vspace{-5pt}
    \resumeSubHeadingListStart
       \resumeProjectHeading
          {\href{ProjectLink.com}{\textbf{\large{\underline{Project Name}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Technology Stack Used}}}{MM YYYY}
          \resumeItemListStart
            \resumeItem{\normalsize{About project \textbf{key points to highlight}.}}


            \resumeItem{\textcolor{accent} {\href{Live Project Link} {\underline{\normalsize{Live site here}}}}}
          \resumeItemListEnd
          \vspace{-13pt}
         
      \resumeProjectHeading
          {\href{ProjectLink.com}{\textbf{\large{\underline{Project Name}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Technology Stack Used}}}{MM YYYY}
          \resumeItemListStart
            \resumeItem{\normalsize{About project \textbf{highlight key points}.}}
            \resumeItem{\textcolor{accent} {\href{Project Link} {\underline{\normalsize{Download}}}}}
          \resumeItemListEnd
          \vspace{-13pt}
         
          \resumeProjectHeading
          {\href{ProjectLink.com}{\textbf{\large{\underline{Project Name}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Technology Stack Used}}}{MM YYYY}
          \resumeItemListStart
            \resumeItem{\normalsize{About Project \textbf{highlight key points} }}
           
          \resumeItemListEnd
         
    \resumeSubHeadingListEnd
\vspace{-12pt}


%




%-----------EXPERIENCE-----------
\section{INTERNSHIP}
  \resumeSubHeadingListStart


    \resumeSubheading
      {Company Name \href{certificate Link}{\raisebox{-0.1\height}\faExternalLink }}{MM YYYY -- MM YYYY}
      {\underline{Role Name}}{city, country}
      \resumeItemListStart
        \resumeItem{\normalsize{About the role \textbf{and responsibilities carried out.}}}
 
      \resumeItemListEnd  
  \resumeSubHeadingListEnd
\vspace{-12pt}
%-----------PROGRAMMING SKILLS-----------
\section{TECHNICAL SKILLS}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\normalsize{Languages:}}{ \normalsize{Python, Java, C, C++, Dart, JavaScript, SQL, NoSQL, R, XML, Go}} \\
     \textbf{\normalsize{Developer Tools:}}{ \normalsize{VS Code, Android Studio, DataGrip, Goland, Intellij Idea Ultimate}} \\
     \textbf{\normalsize{Technologies/Frameworks:}}{\normalsize{ Linux, GitHub, ReactJS, Redux, NextJS, NodeJS, ExpressJS, Git, Mongo, Flutter}} \\
    }}
 \end{itemize}
 \vspace{-15pt}




%-----------INVOLVEMENT---------------
\section{EXTRACURRICULAR}
    \resumeSubHeadingListStart
        \resumeSubheading{Organization Name \href{Certificate Proof link}{\raisebox{-0.1\height}\faExternalLink } }{MM YYYY -- MM YYYY}{\underline{Role}}{Location}
            \resumeItemListStart
                \resumeItem{\normalsize{About the role \textbf{and responsibilities carried out.}}}
                \resumeItem{\normalsize{Participation Certificate. \href{ParticipationCertificateLink.com}{\raisebox{-0.1\height}\faExternalLink }}}
            \resumeItemListEnd
    \resumeSubHeadingListEnd
 \vspace{-11pt}
 
 %-----------CERTIFICATIONS---------------
\section{CERTIFICATIONS}


$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{ReactJS \& Redux - Udemy}} \hspace{1.6cm}
$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{Java}} \hspace{2.59cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com} {Command Line in Linux - Coursera}}\\


$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{Python for Data Science - XIE}} \hspace{1cm}
$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{SQL}} \hspace{2.6cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{Microsoft AI Classroom - Microsoft}} \\


$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{\textbf{5 Stars} in \textbf{C++} \& \textbf{SQL} \href{cert
