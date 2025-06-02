\documentclass[10pt,a4paper,ragged2e,withhyper]{altacv}

\geometry{left=1.25cm,right=1.25cm,top=1.5cm,bottom=1.5cm,columnsep=1.2cm}
\usepackage{paracol}

\iftutex 
  \setmainfont{Roboto Slab}
  \setsansfont{Lato}
  \renewcommand{\familydefault}{\sfdefault}
\else
  \usepackage[rm]{roboto}
  \usepackage[defaultsans]{lato}
  \renewcommand{\familydefault}{\sfdefault}
\fi

% Color scheme (Deep blue theme)
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\definecolor{DeepBlue}{HTML}{0E3E68}
\definecolor{AccentBlue}{HTML}{1567B1}
\definecolor{LightBlue}{HTML}{D5E4F2}

\colorlet{name}{DeepBlue}
\colorlet{tagline}{AccentBlue}
\colorlet{heading}{DeepBlue}
\colorlet{headingrule}{AccentBlue}
\colorlet{subheading}{AccentBlue}
\colorlet{accent}{AccentBlue}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}

\renewcommand{\namefont}{\Huge\rmfamily\bfseries}
\renewcommand{\personalinfofont}{\footnotesize}
\renewcommand{\cvsectionfont}{\LARGE\rmfamily\bfseries}
\renewcommand{\cvsubsectionfont}{\large\bfseries}

\renewcommand{\cvItemMarker}{{\small\textbullet}}
\renewcommand{\cvRatingMarker}{\faCircle}

\begin{document}
\name{Gusseppe Bravo}
\tagline{AI Research Engineer | ML Systems Expert | PhD(c) in AI}

% \photoR{2.8cm}{photo.jpg}

\personalinfo{
  \email{gusseppebravo@gmail.com}
  \homepage{scholar.google.com/citations?user=5JHTnBEAAAAJ}
  \linkedin{gusseppebravo}
  \github{gusseppe}
  \location{New York, USA · Open to relocation}
  \smallskip
  \quote{"If I can't draw it, I can't get it"}
}

\makecvheader

\columnratio{0.6}
\begin{paracol}{2}

\cvsection{Summary}
\begin{itemize}
\item \textbf{AI Research Engineer} at Barcelona Supercomputing Center with expertise in designing and deploying \textbf{production-grade AI systems}, specifically \textbf{AI-based agents} and \textbf{continual learning solutions}.
\item \textbf{PhD candidate in AI} at UPC BarcelonaTech with publications in top-tier conferences (AAMAS, ICPR, CVPR) focusing on making AI systems more \textbf{robust}, \textbf{adaptive}, and \textbf{trustworthy}
\item Delivered measurable business impact through AI innovation: \textbf{\$200K in research funding}, \textbf{\$100K in integration grants}, and \textbf{\$10M+ in increased tax revenue}
\item Specialized in bridging research-to-production gap with expertise in \textbf{MLOps}, \textbf{model monitoring}, and \textbf{AI system reliability} at scale
\item Good at hacking skills (code, linux, problem solving). I'm not afraid of \textbf{thinking big}, at the end, we were able \textbf{to create everything} right? So for sure we can \textbf{solve hard problems}.
\end{itemize}

\cvsection{Experience}

\cvevent{AI Research Engineer}{Barcelona Supercomputing Center \& Lenovo}{Apr 2020 -- Present}{Spain/USA}
\begin{itemize}
\item Architected cognitive frameworks for Language Agents that \textbf{autonomously monitor ML model health}, reducing degradation incidents and improving model reliability
\item Built TADIL algorithm for domain-agnostic continual learning, enabling \textbf{6\% performance improvement} across diverse domains without requiring task labels
\item Developed Scanflow, an MLOps platform for debugging ML workflows, \textbf{some projects were built on top of it}.
\item Developed a novel drift detection algorithm using autoencoder for drift detection on images. \textbf{Published in top-tier journal}.
\item \textbf{Led cross-functional team}, resulting in several publications in top-tier journals and conferences
\end{itemize}




\divider

\cvevent{AI Engineer Intern}{Emory Global Diabetes Research Center}{Jan 2024 -- Jul 2024}{USA}
\begin{itemize}
\item Developed resource-efficient \textbf{cognitive architecture} for LLM-agents, including \textbf{finetuning small language models} like llama, phi for specific uses \textbf{reducing API costs by 35\%} while maintaining reasoning capabilities. Using small LMs and memories.
\item Built an \textbf{algorithm} for healthcare \textbf{domain adaptation}, improving diabetic retinopathy detection \textbf{accuracy up to 3.1\%} on diverse patient populations (hard problem because of class-incremental learning)
\item Published 3 papers on continual learning for medical imaging, with one selected as \textbf{spotlight} presentation at VISAPP conference
\end{itemize}

\divider

\cvevent{AI Consultant}{SUNAT--Inter-American Development Bank}{Jan 2022 -- Dec 2025}{Peru}
\begin{itemize}
\item Built the \textbf{first agent-based system} for customs to monitor ML models in production, enabling \textbf{real-time detection of customs fraud patterns}
\item Built the first \textbf{"Improver" agent for automated ML model updates} that \textbf{reduced manual intervention by 65\%} while maintaining model performance
\item Created SmartDeploy, the first end-to-end MLOps system for SUNAT, enabling \textbf{continuous delivery of ML models} for tax evasion detection
\item Architected and deployed \textbf{enterprise-grade} infrastructure (MLFlow, JupyterHub, Minio, PostgreSQL, Ray) on Kubernetes
% \item Developed novel drift detection library using autoencoder-based anomaly detection, \textbf{increasing model robustness by 42\%} in production
\end{itemize}

% \cvevent{AI Consultant}{SUNAT--Inter-American Development Bank}{Nov 2024 -- Dec 2025}{Peru}
% \begin{itemize}
% \item Pioneered the first agent-based system for customs to monitor ML models in production, enabling \textbf{real-time detection of customs fraud patterns}
% \item Engineered an "Improver" agent for automated ML model updates that \textbf{reduced manual intervention by 65\%} while maintaining model performance
% \item Implemented adaptive prompt architecture reducing token usage by 40\% while maintaining agent reasoning capabilities
% \end{itemize}

% \divider

% \cvevent{Data Science Consultant}{SUNAT--Inter-American Development Bank}{Jan 2022 -- Jan 2024}{Peru}
% \begin{itemize}
% \item Created SmartDeploy, the first end-to-end MLOps system for SUNAT, enabling \textbf{continuous delivery of ML models} for tax evasion detection
% \item Architected and deployed enterprise-grade infrastructure (MLFlow, JupyterHub, Minio, PostgreSQL, Ray) on Kubernetes
% \item Developed novel drift detection library using autoencoder-based anomaly detection, \textbf{increasing model robustness by 42\%} in production
% \end{itemize}



\divider

\cvevent{Data Scientist}{SUNAT (Tax Administration)}{Nov 2017 -- Nov 2018}{Peru}
\begin{itemize}
\item Engineered ensemble-based fraud classifier algorithm with \textbf{92\% accuracy} for identifying unjustified patrimony
\item Developed graph analysis methods to uncover complex tax evasion networks, \textbf{processing 1TB+ of financial data} monthly
\item Built scalable analytical infrastructure processing millions of electronic invoices, directly contributing to \textbf{\$10M increase} in tax revenue
\end{itemize}

\cvsection{Key Projects \& Open Source}

\cvevent{Cognitive Architecture for ML Monitoring}{github.com/gusseppe/cognitive\_architecture\_checker}{}{}
\begin{itemize}
\item LLM-based agent framework that \textbf{autonomously monitors ML models} in production environments
\item Developed novel \textbf{decision procedure algorithm} and \textbf{structured memories} for interpretable model diagnosis
\item Featured in \textbf{AAMAS 2025 conference}; developed in collaboration with Lenovo AI Lab
\end{itemize}

\divider

\cvevent{Scanflow}{github.com/gusseppe/scanflow}{}{}
\begin{itemize}
\item \textbf{Production-grade MLOps} framework for ML workflow management, debugging, and reliability
\item Many projects were inspired by this framework, like Scanflow-k8s, CAMA, KC-Agent.
\item Published in top-tier journal "Expert Systems With Applications" (Impact Factor: 8.665)
\end{itemize}

\switchcolumn

\cvsection{Core Competencies}

\cvskill{Production AI Systems}{5}
\divider
\cvskill{Python/Linux/MLOps}{5}
\divider
\cvskill{Continual Learning}{5}
\divider
\cvskill{Problem solving}{5}
% \divider
% \cvskill{AI Research \& Implementation}{5}

\medskip

\cvsection{Stack software}
{\LaTeXraggedright
\cvtag{Linux}
\cvtag{Python}
\cvtag{PyTorch}
\cvtag{Numba}
\cvtag{TensorFlow}
\cvtag{LangGraph}
\cvtag{AutoGen}
\cvtag{Langchain}
\cvtag{HuggingFace}
\cvtag{MLflow}
\cvtag{Ray}
\cvtag{Docker}
\cvtag{Kubernetes}
\cvtag{RAG}
\cvtag{Airflow}
\cvtag{Spark}
\cvtag{MongoDB}
\cvtag{LLMs}
\par}

% % \smallskip
% {\LaTeXraggedright

% \par}

% % \smallskip
% {\LaTeXraggedright
% \cvtag{MLflow}
% \cvtag{Ray/RayServe}
% \cvtag{Docker}
% \cvtag{Kubernetes}
% \par}

% \smallskip
% {\LaTeXraggedright
% % \cvtag{Prometheus}
% % \cvtag{Distributed Systems}
% % \cvtag{Model Monitoring}
% \cvtag{RAG}
% \par}

\cvsection{Impact Metrics}
\cvachievement{\faChartLine}{\$250K+ Research Funding}{Secured from Lenovo and Intel for AI research initiatives}

\divider

\cvachievement{\faRocket}{\$10M+ Revenue Impact}{Generated for Peruvian Tax Administration through AI fraud detection}

\divider

\cvachievement{\faCode}{40+ GitHub repos}{For open-source ML/MLOps projects and libraries}

\divider

\cvachievement{\faFile}{10+ Publications}{In top-tier AI journals and conferences (AAMAS, ICPR, CVPR)}

\cvsection{Education}

\cvevent{PhD in Artificial Intelligence}{UPC BarcelonaTech}{2021 -- 2025}{}
Research focus: Human-on-the-loop Continual Learning: Data, Knowledge and Agents for Model Adaptation
\textbf{Dissertation submitted, defense pending}

\divider

\cvevent{MSc in Artificial Intelligence}{UPC BarcelonaTech}{2019 -- 2021}{}
Thesis: "Scanflow: A Learning-symbolic Framework for ML Workflow Debugging"
\textbf{Published in Expert Systems With Applications (IF: 8.665)}

\divider

\cvevent{BSc in Computer Science, Magna Cum Laude}{National University of Engineering}{2011 -- 2016}{}
\textbf{Top 5\% of graduating class}

\cvsection{Awards}

\cvachievement{\faTrophy}{Intel-Lenovo AI Innovators Award (2023)}{Selected for innovation in continual learning and cognitive architectures research}

\divider

\cvachievement{\faTrophy}{Scanflow Integration Grant (2020)}{Project selected for integration into Lenovo's enterprise AI platform}

\divider

\cvachievement{\faMedal}{María Rostworowski I Researcher (2020)}{National recognition for excellence in AI research}

\cvsection{Some publications}

\cvevent{Feature Engineering for Agents}{AAMAS 2025}{}{}
% \textbf{Bravo-Rocca, G.,} et al. An Adaptive Cognitive Architecture for Interpretable ML Monitoring.

% \divider

\cvevent{Experience Replay and Zero-shot Clustering}{VISAPP 2025}{}{}
% \textbf{Bravo-Rocca, G.,} et al. Continual Learning in Diabetic Retinopathy Detection.

% \divider

\cvevent{TADIL: Task-Agnostic Domain Incremental Learning}{ICPR 2024}{}{}
% \textbf{Bravo-Rocca, G.,} et al. Task-ID Inference using Transformer Nearest-Centroid Embeddings.

% \divider

\cvevent{Scanflow: Multi-graph framework}{Expert Systems With Applications}{}{}
% \textbf{Bravo-Rocca, G.,} et al. Machine Learning workflow management, supervision, and debugging.

\cvsection{Languages}

\cvskill{English}{5}
\divider
\cvskill{Spanish}{5}

\end{paracol}
\end{document}