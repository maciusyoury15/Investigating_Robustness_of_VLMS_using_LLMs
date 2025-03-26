# Investigating Robustness of VLMS using LLMs
-  We address the challenge of out-of-distribution (OOD) robustness in vision-language models (VLMs) for visual question-answering (VQA) tasks.

-  Current state-of-the-art VLMs demonstrate remarkable capabilities in answering visual questions, nearly matching human performance on benchmark datasets.
-  However, these models exhibit significant weaknesses when encountering questions beyond their training distribution, often producing incorrect answers by leveraging spurious statistical correlations present in the training data.

-  Our study aims to elucidate the failure modes of VLMs by establishing a two-agent chat framework involving a VLM and a large language model (LLM).
-  Within this framework, we employ the LLM to generate OOD questions that the VLM fails to answer correctly.

-  To facilitate this, we utilize few-shot prompting and proximal policy optimization techniques with the LLM.
-  Furthermore, to systematically identify the failure modes of VLMs, we perform clustering on the incorrectly answered questions.

-  This analysis allows us to categorize and understand the types of errors VLMs make.
-  We present both quantitative and qualitative comparisons to underscore the effectiveness of our approach.

-  Here is the report [Final Report](https://github.com/maciusyoury15/Investigating_Robustness_of_VLMS_using_LLMs/blob/main/IFT6289_H24_Final_Report.pdf)
