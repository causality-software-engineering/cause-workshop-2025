# Description

This workshop is organized in the context of the ACM International Conference on the Foundations of Software Engineering (FSE2025). Mon 23 - Fri 27 June 2025 Trondheim, Norway. https://conf.researchr.org/home/fse-2025

## Motivation

Despite their potential, causal methods have not yet been leveraged by the software engineering community. While preliminary studies demonstrated their benefit in specific areas, their broad and systematic exploitation for software engineering is still far from coming. The objective of this workshop is to provide the first platform for participants to share their research, experiences, and insights on causal inference methods and their applications in software engineering. The broader aim is to foster networking and open new collaboration opportunities, encouraging the development of a new strong community.

This workshop aims to bring together researchers, practitioners, and students to explore the growing field of causal inference and, more broadly, causal AI (including causal discovery, mediation analysis, counterfactual analysis, root-cause and causal attribution analysis) in software engineering. Causal inference methods allow the identification and estimation of causal effects from observational data, distinguishing between spurious correlations and causal effects. Despite a growing interest in the topic, the application of such methods in software engineering is not widespread, and there is a need to foster a community to exchange and promote scientific activities on the topic.

## Workshop goals
The workshop will provide a platform for participants to share their research, experiences, and insights on causal inference methods and their applications in software engineering. It will also facilitate networking and collaboration opportunities, encouraging the development of a strong community.

# Call for papers

## Topics of interest:
The workshop intends to keep the scope of the application use cases as broad as possible. We don't want to restrict the type of causal methods applied and want this workshop to be an open stage for SE researchers to discuss which causal approach fits best a given use case. The types of work expected include (but are not limited to) proof of concept, benchmarks, empirical studies, lessons learned reports, literature reviews, etc. 

Topics include the application of causal reasoning methods, such as causal discovery, causal inference, and the causal treatment of machine learning (Causal Machine Learning, Causal Reinforcement Learning), to: 
* Software engineering activities along the whole life cycle, from requirements analysis to design, development, testing and formal methods, verification and validation, maintenance and evolution
* Fault prevention, fault removal (fault localization, debugging, root cause analysis), fault tolerance, fault prediction
* Software Quality Assurance, assessment, and improvement of software quality attributes, e.g., security, privacy, safety, maintainability, resilience, robustness, usability, transparency, explainability, accountability, and fairness among others
* Empirical software engineering
* Software engineering within specific technological spaces (e.g., AI systems, Internet of Things, Cloud, Semantic Web/Web 3.0, Virtualization, Blockchain, networks softwarization, 5G/6G, edge-to-cloud computing)
* Normative/regulatory/ethical spaces about software engineering

## Manuscript information:

Submitted papers should present original, unpublished work, relevant to one of the topics above. CauSE 2025 will accept: 
* Full papers (max. 8 pages) describing original, complete, and validated research;
* Position/Short papers (max. 4 pages) that describe forward-looking, visionary ideas and/or in-progress works with emerging results, thought-provoking reflections, or that set potential new directions for the community; 
* Tool and artifacts papers (max. 4 pages) for researchers who want to present tools, extensions of tools or artifacts (e.g., datasets for benchmarks), relevant to the workshop. 

Submissions must be in English and in PDF format. At the time of submission, all papers must conform to the FSE 2025 format and submission guidelines. **The workshop will employ a double-anonymous review process**.
All submissions will be refereed by three members of the program committee. Accepted submissions will be published in FSE 2025 companion proceedings. 

## Important Dates:

- Workshop papers submission (~~Tuesday Feb 25th, 2025~~) **Extended: March 7th, 2025, AoE**
- Workshop papers notification (~~Tuesday Mar 25th, 2025~~) **Extended: April 8th, 2025, AoE**
- Workshop papers camera-ready (hard) **Thursday Apr 24th, 2025**

## Link to the submission system:

https://cause2025.hotcrp.com/

# Accepted papers:

## AmocRCA: At Most One Change Segmentation and Relative Correlation Ranking for Root Cause Analysis

### Abstract
In this paper, we present AmocRCA, a highly effective and efficient approach to Root Cause Analysis (RCA) using metric data only. A fast and reliable localization of root causes is decisive for self-stabilization of large systems in production and thus for continuous operation. Unlike many multi-modal approaches, we omit the necessity to create and maintain topology and interaction graphs as well as to collect and interpret semantically rich data such as logs and traces for the sake of quick localization/reaction and low computational overhead while achieving comparable results in terms of RCA precision. AmocRCA is based on a recent and promising approach for RCA named BARO. It leverages At Most One Change (AMOC) segmentation to make the scoring mechanism independent of anomaly detection, and employs a relative correlation ranking that enhances the scoring mechanism while reducing the need for a preselected set of metrics. The experimental results confirm the improvement in terms of effectiveness, while achieving comparable efficiency. The latter is an important requirement for deploying the method in productive large-scale, data-intensive applications, where fault localization has a limited time constraint.

### Authors
1. Anton Altenbernd (Technische Universität Berlin)
2. Zhiyuan Wu (Huawei)
3. Odej Kao (Technische Universität Berlin)

## Evolving Estimation Models for Causal Testing

### Abstract
Causal reasoning is a promising and increasingly popular approach for testing complex software systems that cannot be tested using conventional approaches. This involves using a causal model and previous execution data to estimate and validate causal relationships between variables. To produce accurate causal estimates and reliable test outcomes, current approaches rely on users to specify the equational relationships between variables or sacrifice explainability for automation by using black-box estimation. In this paper, we present a hybrid between genetic programming and linear regression to automatically infer human-readable non-linear equations that can be used to evaluate causal test cases. Our results show that our technique tends to produce more accurate causal estimates and more reliable test outcomes than either technique used in isolation.

### Authors
1. Luca Devlin (University of Sheffield)
2. Michael Foster (University of Sheffield)

## Causal Models in Requirement Specifications for Machine Learning: A vision

### Abstract
Specifying data requirements for machine learning (ML) software systems remains a challenge in requirements engineering (RE). This vision paper explores causal modelling as an RE activity that allows the systematic integration of prior domain knowledge into the design of ML software systems. We propose a workflow to elicit low-level model and data requirements from high-level prior knowledge using causal models. The approach is demonstrated on an industrial fault detection system. This paper outlines future research needed to establish causal modelling as an RE practice.

### Authors
1. Hans-Martin Heyn (Chalmers University of Technology and University of Gothenburg)
2. Yufei Mao (Siemens AG)
3. Roland Weiß (Siemens AG)
4. Eric Knauss (Chalmers University of Technology and University of Gothenburg)

## Causality-Driven Neural Network Repair: Challenges and Opportunities

### Abstract
Deep Neural Networks (DNNs) often rely on statistical correlations rather than causal reasoning, limiting their robustness and
interpretability. While testing methods can identify failures, effective debugging and repair remain challenging. This paper explores
causal inference as an approach primarily for DNN repair, leveraging causal debugging, counterfactual analysis, and structural causal
models (SCMs) to identify and correct failures. We discuss in what
ways these techniques support fairness, adversarial robustness, and
backdoor mitigation by providing targeted interventions. Finally,
we discuss key challenges, including scalability, generalization, and
computational efficiency, and outline future directions for integrating causality-driven interventions to enhance DNN reliability.

### Authors
1. Fatemeh Vares (George Mason University)
2. Brittany Johnson (George Mason University)

## The Causality of Bug Resolution: A Tale of Two Systems

### Abstract
Timely and effective bug resolution is a central concern of software development; more so, for systems that serve needs of real-world users. A large body of software engineering research literature involves studies on bug resolution processes. Many of these studies are correlational in nature, as they analyze historical data to uncover factors influencing bug resolution times. Understanding what \textit{causes} software bugs to be resolved faster is of critical interests to developers, customers, and end users. Randomized controlled trials (RCT) -- widely used in establishing causal effects in other areas such as medical research -- are not feasible in a real-world software development scenario. Thus causal inference techniques are essential in such settings to isolate the influences on bug resolution times. In this paper we propose a model of factors affecting quick resolution of bugs. The model is validated on two real-world datasets, leading us to identify key determinants of bug resolution times. Our results offer valuable insights for individual developers, project managers, and development organizations.

### Authors
1. Reshmi Maulik (Meghnad Saha Institute of Technology)
2. Subhajit Datta (Heritage Institute of Technology)
3. Subhashis majumder (Heritage institute of Technology)

## Submission #14: Causal Detection in Linear Temporal Counterexamples

### Abstract
Model checking and verification play a crucial role in ensuring the correctness of software systems by systematically analyzing whether a system satisfies desired specifications. Diagnosing property violations in LTL counterexamples is essential for debugging and refining software, helping developers identify faults and ensure requirement compliance. Several approaches have considered the use of causal reasoning to aid in the identification and explanation of counterexamples. However, these methods are often limited in their expressivity, ability to recognize complex dependencies in system behaviors, or computational feasibility. This paper proposes a revised definition of causes for LTL violations in counterexamples, allowing for the identification of conjunctive causes. Additionally, we introduce a novel algorithm for computing such causes and compare it against a baseline causal computation algorithm using a benchmark of industrial specifications. In all comparisons, our algorithm either subsumes baseline causes, identifies stronger causes, or diverges from the baseline in explainable ways, demonstrating its effectiveness in enhancing counterexample analysis.

### Authors
1. Herong Meng (Imperial College London)
2. Dalal Alrajeh (Imperial College London)

## Authorship of Minor Contributors in Kubernetes Configuration Scripts: An Exploratory Study

### Abstract
Kubernetes is a popular open source software (OSS) tool to manage containers at scale. Despite being beneficial for rapid deployment, Kubernetes-based software deployments are susceptible to defects that can lead to serious consequences. A systematic analysis of development-related factors that cause defects can aid practitioners on how to mitigate these defects. We conduct an exploratory empirical study where we use causal analysis to quantify the impact of one development factor called minor contributors, which refers to practitioners who author <5% of the total code. By analyzing 29,028 commits from 157 OSS repositories, we observe (i) 5.6% of the 29,028 commits to be authored by minor contributors; and (ii) authorship of minor contributors to impact defects in configuration scripts. Based on our findings, we recommend researchers to (1) further investigate the characteristics of minor contributors; and (2) identify other development-related factors that may have a causal impact on defects in Kubernetes configuration scripts.

### Authors
1. Akond Rahman (Auburn University)
2. Gerry Dozier (Auburn University)
3. Yue Zhang (Auburn University)

## Causal Inference Needs More Than Analysis: The Role of Study Design

### Abstract
In a variety of research fields, causal inference methods have demonstrated potential benefits in identifying and estimating causal relationships from observational data. These methods have started to receive increasing attention in software engineering as well. However, the investigation of causal relationships can be challenging when dealing with observational data. In this paper, we uphold the position that data analysis alone is not enough and a proper design is always needed to detect reliable causal relationships. To this end, we describe the fundamental conditions needed to reveal causal relationships, the challenges of observational studies in satisfying them, and the mechanisms to overcome those challenges.

### Authors
1. Sabato Nocera (University of Salerno)
2. Sira Vegas (Universidad Politécnica de Madrid)
3. Giuseppe Scanniello (University of Salerno)
4. Natalia Juristo (Universidad Politécnica de Madrid)

# Workshop agenda 




# Program Committee

- Prof. Alexander Pretschner. Technical University of Munich, Munich, Germany.
- Prof. Andrea Alexander Janes. Free University of Bozen/Bolzano, Bozen/Bolzano, Italy. 
- Prof. Carlo A. Furia. Università della Svizzera italiana, Lugano, Switzerland.
- Dr. Carlos Paradis. KBR Inc. CA, United States.
- Dr. Hans-Martin Heyn. Department of Computer Science and Engineering, Chalmers and University of Gothenburg, Göteborg, Sweden.
- Prof. Jacopo Soldani. University of Pisa, Pisa, Italy.
- Julian Frattini. Blekinge Institute of Technology, Karlskrona, Sweden.
- Prof. Jürgen Mottok. Software Engineering Laboratory for Safe and Secure Systems (LaS³), OTH Regensburg, Regensburg, Germany.
- Prof. Martin Shepperd. College of Engineering, Design and Physical Sciences, Brunel University of London, London, UK.
- Dr. Mike Konrad. Software Engineering Institute, Carnegie Mellon University, Pittsburgh, PA, United States.
- Prof. Mohammad Reza Mousavi. Department of Informatics, King's College London, London, UK.
- Dr. Mirko Perkusich. VIRTUS/UFCG, Campina Grande, Brazil.
- Dr. Rayven Plaza. Google Inc. New York, NY, USA.
- Prof. Richard Torkar. Department of Computer Science and Engineering, Chalmers and University of Gothenburg, Göteborg, Sweden.
- Prof. Robert Feldt. Department of Computer Science and Engineering, Chalmers University of Technology Göteborg, Sweden
- Dr. Seongmin Lee. Max Planck Institute for Security and Privacy, Bochum, Germany.
- Prof. Stefano Russo. DIETI, Universit`a degli Studi di Napoli Federico II, Napoli, Italy.
- Dr. Subhajit Datta. Department of Computer Science and Engineering, Heritage Institute of Technology, Kolkata, India.
- Prof. Subhashis Majumder. Department of Computer Science and Engineering, Heritage Institute of Technology, Kolkata, India.
- Dr. Tim A. D. Henderson. Google Inc. Mountain View, CA, USA.


# Organizers and contacts

**Dr. Julien Siebert** is a Senior Expert in Artificial Intelligence at the Fraunhofer Institute for Experimental Software Engineering, Kaiserslautern, Germany. He is guest editor of the special issue on Causal Modeling and Inference in Software Engineering (Information and Software Technology). His research interests include software engineering methods for artificial intelligence and complex systems.

**Prof. Roberto Pietrantuono** is an Associate Professor at the Federico II University of Naples, working in the Dependable Systems and Software Engineering Research Team (DESSERT). He is associate editor of Transactions on Services Computing and Software Quality Journal. He is co-founder of Critiware s.r.l., a company working on critical systems engineering. He currently coordinates an EU MSCA Project (uDEVOPS) on SQA for microservice systems. His research interests include software engineering, software reliability, software testing and AI systems engineering. 

**Dr. Neil Walkinshaw** is a Senior Lecturer at the University of Sheffield. His research focuses on software quality assurance, particularly "black-box" components, and he specializes in applying Machine Learning and data analysis algorithms to testing, reverse-engineering, and safety-case assessment. He received a grant from CITCoM (2021-2024) for the project "Causal Inference for Testing of Computational Models."

**Luca Giamattei** is researcher at the Federico II University of Naples, working in the Dependable Systems and Software Engineering Research Team (DESSERT). His research interests encompass the use of causal reasoning in software testing.
