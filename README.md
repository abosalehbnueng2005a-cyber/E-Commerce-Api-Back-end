

\documentclass[10pt, letterpaper]{article}

\usepackage[top=0.55in, bottom=0.55in, left=0.65in, right=0.65in]{geometry}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{fontenc}
\usepackage{titlesec}
\usepackage{multicol}
\usepackage{xcolor}
\usepackage{array}
\usepackage{tabularx}

\hypersetup{
  colorlinks=true,
  urlcolor=black,
  linkcolor=black
}

% No page numbers
\pagestyle{empty}

% Section formatting — bold, small caps, with a rule underneath
\titleformat{\section}
  {\bfseries\large}
  {}
  {0em}
  {}
  [\vspace{-6pt}\rule{\linewidth}{0.5pt}\vspace{-4pt}]

\titlespacing{\section}{0pt}{5pt}{2pt}

% Bullet list settings
\setlist[itemize]{
  leftmargin=1.5em,
  itemsep=0.5pt,
  parsep=0pt,
  topsep=1pt,
  label={\textendash}
}

% No paragraph indent
\setlength{\parindent}{0pt}

% Helper: right-aligned date on same line as title
\newcommand{\cventry}[3]{%
  \textbf{#1} \hfill #3 \\
  \textit{#2} \vspace{2pt}
}

\newcommand{\cventrytwo}[2]{%
  \textbf{#1} \hfill #2 \\
}

\begin{document}

%--- HEADER ------------------------------------------------------------------
\begin{center}
  {\LARGE\bfseries Mohamed Tareq Azmi} \\[4pt]
  +20 112 127 3690 \;|\;
  \href{mailto:mohamed.tareq.azmi.ali@gmail.com}{mohamed.tareq.azmi.ali@gmail.com} \;|\;
  \href{https://linkedin.com/in/mohamed-tareq}{linkedin.com/in/mohamed-tareq} \;|\;
  \href{https://github.com/MohamedTareq918}{github.com/MohamedTareq918}
\end{center}

\vspace{4pt}

%--- EDUCATION ---------------------------------------------------------------
\section{Education}

\cventrytwo{Benha National University}{Cairo, Egypt}
B.Sc.\ in Computer Science \hfill Expected Jun 2027 \\
GPA: 3.18/4.0 \quad \textit{Relevant Coursework: Data Structures \& Algorithms, OOP, Operating Systems, Databases, Networks}

\vspace{4pt}

\cventrytwo{Route Academy}{Cairo, Egypt}
Back-End Web Development (ASP.NET Core) --- Intensive Bootcamp \hfill Dec 2025 -- Present

\vspace{1pt}

%--- EXPERIENCE --------------------------------------------------------------
\section{Experience}

\cventry{Head of Back-End Track}{Google Developer Groups (GDG) on Campus --- Benha National University}{Oct 2025 -- May 2026}
\begin{itemize}
  \item Directed the Back-End track end-to-end for a cohort of \textbf{30+ students} across \textbf{12 sessions} --- overseeing curriculum design, session delivery, and individual progress tracking from onboarding through completion
  \item Instructed 30+ students in ASP.NET Core, RESTful API design, and Clean Architecture; maintained \textbf{88\%+ session completion} and consistently positive engagement scores across all modules
  \item Mentored students individually through backend project milestones; multiple students shipped personal backend projects by track completion, demonstrating real applied learning outcomes
  \item Owned all track operations --- content creation, scheduling, mentorship, and performance evaluation --- enabling a smooth, structured learning journey for every participant
\end{itemize}

\vspace{3pt}

\cventry{Frontend Instructor}{Google Developer Groups (GDG) on Campus --- Benha National University}{Oct 2024 -- May 2025}
\begin{itemize}
  \item Taught HTML, CSS \& JavaScript to \textbf{35+ students} across \textbf{10+ structured workshops}; achieved \textbf{90\%+ session attendance} and hands-on project completion by all participants
  \item Built a reusable curriculum of exercises and annotated code examples deployed across all sessions, ensuring consistent instruction quality and reducing per-session prep time by $\sim$40\%
  \item Co-organized community tech events with the GDG technical team, collectively reaching \textbf{100+ attendees} and growing campus tech community engagement
\end{itemize}

\vspace{2pt}

%--- PROJECTS ----------------------------------------------------------------
\section{Projects}

\textbf{E-Commerce API Backend} \;|\; \textit{ASP.NET Core, C\#, EF Core, Redis, JWT, Clean Architecture} \;|\; \href{https://github.com/MohamedTareq918/ECommerce-API-Backend}{GitHub} \quad \textit{(In Progress)}

\begin{itemize}
  \item Designed a RESTful API following Clean Architecture with four strict layers (Domain, Application, Infrastructure, API); implemented modules for Products, Categories, Cart, Orders, Payments, Delivery, Reviews, and Admin Dashboard
  \item Built JWT and Google OAuth2 authentication with role-based access control; applied Repository, Unit of Work, Specification, Singleton, and Factory patterns for a scalable, maintainable codebase
  \item Integrated Redis caching on high-frequency read endpoints, cutting average query response time by $\sim$60\% under simulated load via EF Core + LINQ optimization
  \item Implemented pagination, filtering, sorting, search, input validation, global exception handling, and structured logging; tested all endpoints via Postman
\end{itemize}

\vspace{2pt}

%--- TECHNICAL SKILLS --------------------------------------------------------
\section{Technical Skills}

\begin{tabular}{@{}p{3.2cm} l}
  \textbf{Languages}       & C\#, JavaScript, HTML, CSS, SQL, C++ \\[2pt]
  \textbf{Back-End}        & ASP.NET Core, Entity Framework Core \\[2pt]
  \textbf{Arch \& Patterns} & Clean Architecture, Repository Pattern, Unit of Work, CQRS \\[2pt]
  \textbf{Databases}       & SQL Server \\[2pt]
  \textbf{DevOps \& Tools} & GitHub, Docker \\[2pt]
  \textbf{AI Tools}        & GitHub Copilot, Cursor \\
\end{tabular}

\end{document}
