# Multi-Model-NLP-Framework-for-Unstructured-Text-Analysis
Analyzing pipeline incident reports is vital for enhancing safety in the pipeline industry, yet the unstructured nature of these reports poses analytical challenges. This study evaluates 4 topic modeling techniques— NMF, LDA, BERTopic, and Top2Vec—to figure out their effectiveness in extracting meaningful themes.



# Pipeline Incident Topic Modeling

Analyzing pipeline incident reports is essential for improving safety in the pipeline industry, but the unstructured nature of these reports makes automated analysis challenging. This repository evaluates four topic modeling techniques—Non-Negative Matrix Factorization (NMF), Latent Dirichlet Allocation (LDA), BERTopic, and Top2Vec—on the PHMSA incident database to compare their effectiveness in extracting meaningful themes.  

- **NMF (15 topics):** Provides precise, interpretable topics suited for detailed incident analysis, though it may miss broader patterns.  
- **LDA (30 topics):** Captures more topics, including geographical and regulatory nuances, but yields broader, less cohesive themes.  
- **BERTopic (50 topics):** Delivers granular, incident-specific insights but can produce overlapping topics that require careful interpretation.  
- **Top2Vec (12 topics):** Offers macro-level thematic exploration focused on regulatory compliance and safety, but with fewer topics that may overlook nuanced details and require iterative tuning.  

Our results show that combining NMF’s and BERTopic’s detailed operational topics with LDA’s and Top2Vec’s broader thematic views creates a hybrid framework that both captures granular incident details and reveals overarching safety patterns. This integrated approach can inform maintenance planning, regulatory policy development, and proactive safety management.

## Highlights

- Each model extracts unique patterns from pipeline incident narratives.  
- NMF (15 topics) and BERTopic (50 topics) excel at uncovering technical details and incident specifics.  
- LDA (30 topics) and Top2Vec (12 topics) better capture broader regulatory and systemic themes.  
- A hybrid approach leverages granular insights (NMF, BERTopic) alongside overarching patterns (LDA, Top2Vec).  
- The combined framework enhances maintenance planning, regulatory decision-making, and proactive safety improvements.

