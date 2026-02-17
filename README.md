# A Survey on LLM-Based Conversational Job Recommendation Systems in HR Technology

---

## Authors

**Mr. S. Palanisamy, M.C.A., M.Phil**  
Assistant Professor  
Department of Computer Applications  
Bharathiar University, Coimbatore – 641046  
Email: palsmailid@gmail.com

**Rameesa M**  
Department of Computer Applications  
Bharathiar University, Coimbatore – 641046  
Email: ramiparveen.m@gmail.com

---

## Abstract

Recruitment has become a field of great development due to the development of Artificial Intelligence (AI) and Natural Language Processing (NLP). The conventional job portals depend on searching and filtering based on keywords and have weak job matching and personalization. The recent advances in Large Language Models (LLMs) make it possible to build intelligent and conversational systems of job recommendations that comprehend resumes, job descriptions, and user intent with the help of natural language.

The given survey aims to provide an in-depth overview of AI-based job recommendation methods, specifically, conversational recruitment systems based on LLM in the fields of Human Resources technology. The current studies about resume parsing, job matching algorithms, recommender systems, conversational AI, and explainable recommendations are examined systematically. Such issues as a lack of explainability, ethical use of data, scalability, and complete integration of conversational platforms are indicated. Moreover, the research directions in the future are described, including explainable AI, fairness-aware models, integrating HR-EdTech systems, and deploying systems at scale.

This survey can be taken to provide a baseline when developing ethical, intelligent, and user-centric recruitment systems with the help of LLMs.

---

## Keywords

Large Language Models, Conversational AI, Job Recommendation Systems, Resume Parsing, Skill Extraction, Human Resource Technology, Explainable AI, Intelligent Recruitment Systems, Personalized Job Matching, Natural Language Processing

---

## Table of Contents

1. [Introduction](#1-introduction)
2. [Scope and Research Questions](#2-scope-and-research-questions)
3. [Literature Review Methodology](#3-literature-review-methodology)
4. [Evolution of Job Recommendation Systems](#4-evolution-of-job-recommendation-systems)
5. [LLM-Based Conversational Recruitment Systems](#5-llm-based-conversational-recruitment-systems)
6. [Difficulties in Current Systems](#6-difficulties-in-current-systems)
7. [Research Gaps and Open Issues](#7-research-gaps-and-open-issues)
8. [Future Directions](#8-future-directions)
9. [Conclusion](#9-conclusion)
10. [References](#10-references)

---

## 1. Introduction

The search and recruitment of a job have moved to the online platform as online job portals and professional networking sites have grown. Though the systems have increased the number of people who can access employment opportunities, they are usually overwhelmed with information, irrelevant suggestions and less personalization [3].

The conventional recruitment media majorly depend on the contextual matching of resumes and job descriptions and this does not reflect semantic information, contextuality and subtle skill associations. The implementation of Artificial intelligence (AI) and Natural Language Processing (NLP) has allowed more sophisticated recruiting solutions such as automated resume screening and recommendation models developed using machine learning [4]. Though these methods enhanced the accuracy of matching, they are generally structured and offer a little to no interactive feedback.

Recent developments in Large Language Models (LLMs) have also changed the recruitment systems as they can now support natural language interactions at a deeper semantic level and can process unstructured text. Conversational interfaces built on LLM enable end users to set preferences dynamically and give them personalized, explainable job suggestions.

Notwithstanding these advantages, the issues that are associated with bias, ethics, and scalability as well as system integration persist [7]. This survey provides a review of prior research to analyze how the system of job recommendation based on LLM has evolved and can evolve in the future.

---

## 2. Scope and Research Questions

### 2.1 Scope of the Survey

This survey is dedicated to the topic of AI-based job recommendation systems in the sphere of Human Resources (HR Tech), with specific attention to the Large Language Model (LLM)-based conversational job recruitment services. The coverage consists of systems that help job seekers with the analysis of their resumes, interpretation of the intent of the user in a natural language, and proposal of relevant job opportunities. The survey has been conducted on techniques that extend to Natural Language Processing (NLP), machine learning, deep learning, semantic search, and conversational artificial intelligence [6].

The focus of the literature used is mainly in the past ten years, but with more focus on the current developments of LLM and transformer-based models. Some of the core elements considered are resume parsing and skill extraction, job description understanding, job matching and ranking, conversational interfaces, and explainable recommendations.

The scope also includes ethical factors like privacy of data, fairness, and legal limitations of acquisition of job data as these factors have serious implication in actual implementation. This survey does not include automated hiring decisions by the employer, scoring of the candidates to select them, or the use of entirely independent recruitment pipelines, as these create more ethical and regulatory issues than can be handled by job recommendation. Rather, attention is paid to the decision-support systems that improve the user experience, transparency, and personalization of job seekers.

### 2.2 Research Questions

In order to conduct the systematic and informative analysis, the following research questions guide this survey:

- **Q1:** What are the most popular AI, NLP, and machine learning algorithms in the current job recommendation system?

- **RQ2:** How do Large Language Models enhance understanding of resumes, job description analysis and conversational job searching?

- **RQ3:** Which architectural patterns and methodologies are utilized to make conversational AI to work with job recommendation engines?

- **RQ4:** What are the most significant challenges and restrictions of the current AI-based recruitment systems regarding personalization, explainability, scalability and ethics?

- **RQ5:** What are the gaps and opportunities in research addressing transparent, user-centric, and scalable systems of recruitment based on the use of the LLM?

---

## 3. Literature Review Methodology

A methodology of a systematic and guided literature review was implemented in order to guarantee the coverage, objectivity, and academic rigor. The major objective was to locate, review, and generalize the available literature on AI-based job recommendation systems, where a strong focus is on platforms based on Large Language Models (LLM) and conversational recruitment. A thematic synthesis approach was applied in place of summarizing individual studies in sequential order, as the most common trends, challenges, and gaps in the field of research were identified.

### 3.1 Strategy and Selection of Literature Search

The academic databases such as IEEE Xplore, SpringerLink, ACM Digital Library, ScienceDirect, and Google Scholar were used to search the literature. The sources were chosen due to their comprehensive review of peer reviewed journals and high impact conference proceedings in the field of artificial intelligence, natural language processing and information systems.

The queries were relevant keywords used to search job recommendation systems, resume parsing, conversational AI, large language models, and semantic job matching narrowed down to using Boolean operators. The search was limited to those studies that were published in the past decade, and few seminal works have been incorporated that would provide historical context.

### 3.2 Inclusion Requirements and Screening

The studies were included when they covered AI- or NLP-based job recommendation systems, resume analysis, conversational recruitment interfaces, or other ethical or explainable issues of AI related to HR. There were no non-technical discussions, non-peer-reviewed sources, or hiring systems of employers only.

Relevancy and quality were ensured by a multi-stage screening procedure consisting of title, abstract and full-text screening and elimination of duplicated studies.

### 3.3 Thematic Analysis and Synthesis

The chosen literature was divided into thematic groups that included resume parsing, job matching algorithms, conversational AI, and ethical AI in recruitment. The comparison in each of the themes facilitated the establishment of the strengths, limitations, and changing trends of the methods used, and a logical and objective synthesis was done based on the goals of the survey.

---

## 4. Evolution of Job Recommendation Systems

The history of job recommendation systems indicates ever-changing developments in information retrieval, machine learning, and artificial intelligence. In the course of time, these systems have evolved to be no longer basic systems, which rely on the use of a keyword, but are nowadays intelligent, context-sensitive, and conversation systems, which can comprehend complex job requirements and user intent. This development underscores the increasing need to have precise, customized, and people-focused recruitment technologies.

### 4.1 Rule-Driven and Early Keyword-Based Systems

The early job portals were majorly based on keyword matching with resumes and job descriptions being abstracted in the form of sets of terms matched with Boolean query and rule of thumb filters. Despite being computationally efficient, such systems did not have semantic understanding and tended to give incorrect results because of terminology variations.

To enhance accuracy, rule-based and expert systems came up with pre-defined menaces like minimum experience or certifications. But, they were not easily scalable, were rudimentary to keep updated by hand, and did not work with unstructured and dynamic job market data.

### 4.2 Systems Based on Machine Learning and Natural Language Processing

The field of machine learning became a significant change in job recommendation technologies. The Supervised and unsupervised learning methods allowed classifying and clustering candidates and jobs, whereas collaborative and content-based filtering enhanced personalization with the help of user behavior and profile information.

General progress in Natural Language Processing also increased semantic matching with word embeddings and entity recognition. Although the accuracy was better, these systems tended to rely on structured inputs and massive feature engineering.

### 4.3 Conversational Systems Based on Deep Learning and LLM

The recent advances in deep learning and Large Language Models opened the way to conversational recruitment systems, which can make sense of unstructured information and interact with the user in a natural language. These systems enable contextual reasoning, progressive preference refinement and intelligible job recommendations, a change to intelligent, adaptive, and human-centered recruitment platforms.

---

## 5. LLM-Based Conversational Recruitment Systems

The emergence of conversational recruitment systems built with Large Language Model (LLM) has greatly changed the recruitment platforms as traditional job search platforms offered simpler and often contextualized job search experiences.

In contrast to traditional recruitment portals, which are based on fixed formatted pages, keyword search and filtering rules, LLM-based systems can facilitate natural language conversation, where applicants can intuitively outline their preferences and career objectives.

The systems are able to provide analysis of unstructured data, including resumes, job descriptions, and identify relevant skills, interpret user intent and dynamically refine recommendations based on multi-turn conversations. LLM helps to better the precision of the matching and individualization through the semantic gap between the candidate language and recruiter language.

Combination with various sources of job data also increases the quality of the recommendations by organizing, summarizing, and ranking opportunities and also minimizing the amount of information that overwhelms the user.

Moreover, the systems on the basis of LLM give explainable recommendations as it clearly explains the reason why certain roles fit a profile of a candidate, thus enhancing transparency and trust.

Although there are issues associated with data privacy, bias, and reliability of responses, when deployed responsibly and ethically, LLMs can help build scalable and user-friendly recruitment models that are more useful than traditional job portals [8].

---

## 6. Difficulties in Current Systems

The existing online recruitment systems (with numerous examples of their usage) are still plagued by a number of structural and functional flaws of the current system that adversely impact matching accuracy, personalization, transparency, and general user satisfaction.

The majority of the conventional systems largely depend on matching keywords between resumes and job description, which lacks semantics and contextual relevance. This means that the candidates would have missed out on their opportunities and not utilised transferable or interdisciplinary competencies as those with the right skills and but differently stated are usually ignored.

Moreover, current systems have issues with imprecise resume parsing since unstructured resumes written as PDFs, tables, and graphical data are challenging to extract and therefore key information like certifications, project-related experience, and soft skills is overlooked or wrongly picked.

Personalization is also minimal and most of the platforms rely on fixed filters (location or experience level, etc.) and are not aware of user tastes, career ambitions and changing interests. The outcome is that this leads to generic recommendations that are not aligned with career paths.

Moreover, job discovery can be lengthy and often the information is overloaded with the rankings of the job listings being ineffective as well as the interfaces displayed in a form where manual filtering is required repeatedly so that only fresh graduates and those who are not technical can use it.

Lastly, the majority of systems are black box which does not have much to explain behind the recommendation hence decreasing user confidence and strict rule-based architecture prevents scalability and flexibility to changing job markets.

---

## 7. Research Gaps and Open Issues

Despite the significant advancements achieved in terms of job recommendation and conversational hiring technology, there are still a number of research gaps and unsolved challenges in the context of the creation of intelligent, reliable, and scalable LLM-based recruitment tools.

A significant weakness is that current systems have a poor semantic and career level notion that treats skills in isolation, as opposed to a networked and developing skill set that interacts with knowledge and experience. The absence of longitudinal career modeling makes it difficult to offer holistic and growth-focused job suggestions that can consider the experience of the past, ongoing learning, and the future goals.

Moreover, the existing conversational recruitment systems are somewhat lacklustre in contextual intelligence, and little work has been done in multi-turn, multi-memory dialogue management that can handle ambiguity in the input and narrow down suggestions as a result of natural interaction.

The other gap is the disjointed employment of job market information with majority of the studies utilizing single platform datasets without taking into consideration the structural and terminological heterogeneity between job portals. The completeness and reliability of the recommendations are constrained by the lack of standardized job representations and intelligent methods of data fusion.

Lastly, explainability is a significant unresolved problem since most systems focus on accuracy and not transparency giving little information on why a job is suggested. This is a poor explanation, which decreases user trust, adoption, and real-world effect of automated recruitment systems.

---

## 8. Future Directions

The emergence of Artificial Intelligence and especially Large Language Models (LLMs) is radically changing the recruitment and job recommendation systems. The future studies must be based on the development of such platforms into dynamic job-matching tools into smart, user-centered career-advising systems.

The future of career intelligence is one of these opportunities: the establishment of a holistic model of career intelligence where long-term career paths, lifelong skill building, and current trends in the labor market are taken into account. These systems may also suggest not only the appropriate job but also the appropriate upskilling pathway that will be based on future demand.

Incremental innovations such as conversational intelligence with memory-conscious and emotionally responsive dialogue systems can further promote personalization and user interaction. Explainable AI will become important and allow providing transparent job suggestions, that is, it will be possible to explain the matching in terms of skills, experience, and growth prospects.

It is also important to address ethical issues by alleviating bias, implementing training that is aware of fairness, and human control. Moreover, scalability, regulatory compliance, and trust in the system will be supported by cross-platform job data integration and privacy-preserving system designs in the real-world deployment.

---

## 9. Conclusion

It was a survey of job recommendation and recruitment systems that focuses on the increasing importance of Large Language Models (LLMs) in conversational recruitment models. It discussed the development of traditional job portals, limitations of the keyword-based and rule-driven methods, and the discussion of the latest developments in AI-based resume parsing, skill extraction, and job matching methods.

The paper identified some of the major issues associated with personalization, explainability, fragmentation, bias, and user experience. It also showed how conversational systems based on LLM can help solve these problems with the help of semantic interpretation, context-driven interactions, and clear suggestions.

In general, the results suggest that the thoughtful implementation of the LLM-based recruitment systems can substantially change the traditional job portals into smart and user-driven career guidance systems.

---

## 10. References

[1] A. V. Chandak et al., "Resume Parser and Job Recommendation System Using Machine Learning," in *Proc. IEEE ESIC*, 2024, pp. 157–162.

[2] S. Tanberk et al., "Resume Matching Framework via Ranking and Sorting Using NLP and Deep Learning," in *Proc. IEEE UBMK*, 2023, pp. 453–458.

[3] R. Jain et al., "Job Recommendation System Based on Machine Learning," in *Proc. IEEE ICCUBEA*, 2019, pp. 1–6.

[4] A. Mishra and P. Singh, "Smart Recruitment System Using Artificial Intelligence," in *Proc. IEEE ICACCM*, 2020, pp. 312–317.

[5] J. Jiang et al., "Learning Effective Representations for Person–Job Fit," in *Proc. IEEE ICDMW*, 2019, pp. 240–247.

[6] S. Bian et al., "Learning to Match Jobs with Resumes from Sparse Interaction Data," in *Proc. IEEE ICDM*, 2020.

[7] Y. Zhang et al., "A Survey on Recommender Systems for Human Resource Management," *IEEE Access*, vol. 8, pp. 197964–197978, 2020.

[8] M. B. Patil and R. S. Bichkar, "Resume Classification Using Natural Language Processing," in *Proc. IEEE ICCIC*, 2018.

[9] A. Upadhyay and S. Khandelwal, "Artificial Intelligence in Talent Acquisition," in *Proc. IEEE STPEC*, 2021.

[10] A. Abdollahi and O. Nasraoui, "Explainable Matrix Factorization for Collaborative Filtering," *IEEE Trans. Knowl. Data Eng.*, vol. 31, no. 10, pp. 1853–1866, 2019.

---

## Contact Information

**Department of Computer Applications**  
Bharathiar University  
Coimbatore – 641046  
Tamil Nadu, India

**Corresponding Authors:**
- Mr. S. Palanisamy: palsmailid@gmail.com
- Rameesa M: ramiparveen.m@gmail.com

---

*This survey paper is part of ongoing research at Bharathiar University's Department of Computer Applications, focusing on the application of Large Language Models in Human Resource Technology.*
