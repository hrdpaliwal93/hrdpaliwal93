```latex
\documentclass[a4paper,11pt]{article}

\usepackage[margin=0.5in]{geometry}
\usepackage[dvipsnames]{xcolor}
\usepackage{tikz}
\usepackage{tcolorbox}
\usepackage{fontawesome5}
\usepackage{graphicx}
\usepackage{titlesec}
\usepackage{multicol}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{pagecolor}
\usepackage{tabularx}

% ================= COLORS =================

\definecolor{bg}{HTML}{0D1117}
\definecolor{card}{HTML}{161B22}
\definecolor{primary}{HTML}{00D9FF}
\definecolor{text}{HTML}{C9D1D9}
\definecolor{muted}{HTML}{8B949E}
\definecolor{accent}{HTML}{FF6B6B}

\pagecolor{bg}
\color{text}

\pagestyle{empty}

% ================= LINKS =================

\hypersetup{
    colorlinks=true,
    urlcolor=primary
}

% ================= SECTION STYLE =================

\titleformat{\section}
{\Large\bfseries\color{primary}}
{}
{0em}
{}

% ================= BOX STYLE =================

\tcbset{
    cardstyle/.style={
        colback=card,
        colframe=card,
        arc=6pt,
        boxrule=0pt,
        left=12pt,
        right=12pt,
        top=10pt,
        bottom=10pt
    }
}

\begin{document}

% =================================================
% HERO SECTION
% =================================================

\begin{center}

\vspace*{0.5cm}

{\Huge \textbf{\textcolor{primary}{Hardik Paliwal}}}

\vspace{0.2cm}

{\Large Full Stack Developer $\rightarrow$ Applied AI Engineer}

\vspace{0.5cm}

\textcolor{muted}{
Building systems that think, plan, and act autonomously.
}

\vspace{0.6cm}

\faGithub \hspace{0.2cm}
\href{https://github.com/hrdpaliwal93}{github.com/hrdpaliwal93}
\hspace{1cm}
\faLinkedin \hspace{0.2cm}
LinkedIn
\hspace{1cm}
\faEnvelope \hspace{0.2cm}
Email

\vspace{0.8cm}

\end{center}

% =================================================
% ABOUT
% =================================================

\begin{tcolorbox}[cardstyle]

{\Large \textbf{\textcolor{primary}{🧠 About Me}}}

\vspace{0.4cm}

I started as a Full Stack Developer building production-grade applications.

Now I’m deeply focused on:
\begin{itemize}[leftmargin=*]
    \item AI Agents
    \item LLM Engineering
    \item RAG Systems
    \item Agentic AI Workflows
    \item Autonomous Systems
\end{itemize}

\textcolor{accent}{
Ship fast. Learn faster. Let AI do the heavy lifting.
}

\end{tcolorbox}

\vspace{0.4cm}

% =================================================
% TWO COLUMN SECTION
% =================================================

\begin{multicols}{2}

% ================= LEFT =================

\begin{tcolorbox}[cardstyle]

{\large \textbf{\textcolor{primary}{🚀 Current Focus}}}

\vspace{0.3cm}

\textbf{AI Agents}

ReAct loops, memory systems, planning

\vspace{0.3cm}

\textbf{LLM Engineering}

Prompting, evals, structured outputs

\vspace{0.3cm}

\textbf{RAG}

Vector DBs, retrieval pipelines

\vspace{0.3cm}

\textbf{Agentic AI}

LangGraph, CrewAI, orchestration

\end{tcolorbox}

\vspace{0.4cm}

\begin{tcolorbox}[cardstyle]

{\large \textbf{\textcolor{primary}{📚 Learning}}}

\vspace{0.3cm}

• LangGraph memory architectures

• Multi-agent workflows

• Long horizon reasoning

• AI-native SaaS systems

\end{tcolorbox}

% ================= RIGHT =================

\columnbreak

\begin{tcolorbox}[cardstyle]

{\large \textbf{\textcolor{primary}{🛠 Tech Stack}}}

\vspace{0.3cm}

\textbf{Frontend}

React • Next.js • TypeScript

\vspace{0.3cm}

\textbf{Backend}

Node.js • Python • FastAPI

\vspace{0.3cm}

\textbf{AI Stack}

LangChain • LangGraph • OpenAI

\vspace{0.3cm}

\textbf{Infra}

Docker • AWS • GitHub Actions

\end{tcolorbox}

\vspace{0.4cm}

\begin{tcolorbox}[cardstyle]

{\large \textbf{\textcolor{primary}{🎯 2025 Goals}}}

\vspace{0.3cm}

✅ Build 3 AI-powered products

✅ Master agentic workflows

✅ Deploy production AI systems

⏳ Build AI-native SaaS

\end{tcolorbox}

\end{multicols}

\vspace{0.4cm}

% =================================================
% FOOTER
% =================================================

\begin{center}

\vspace{0.5cm}

\textcolor{muted}{
"The best engineers don't just write code —
they build systems that think."
}

\vspace{0.5cm}

⭐ If my work helps you, a GitHub star genuinely means a lot.

\end{center}

\end{document}
```
