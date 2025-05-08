# LLM-based Response Generation for Korean Adolescents A Study Using NAVER Knowledge-iN Q&A Dataset with RAG

This is an adolescent Q&A dataset in Korean, with questions and answers scraped from the NAVER Knowledge iN platform.
All answers are from "여성가족부 한국청소년상담복지개발원 청소년사이버상담센터". 
We do not own any of the data included in this dataset. Non-commercial, research-only use is permitted. Please cite appropriately.

### Data files
Korean-Adolescent-QA-Dataset-ko.xlsx

### Data description
1. **Title**  
   - The title of the entire question.
2. **Question**  
   - The actual question. Some escape sequences, such as `\n\n\n`, have been removed.
3. **Answer**  
   - The answer provided by the "여성가족부 한국청소년상담복지개발원 청소년사이버상담센터," which responded to the question.
4. **Year**  
   - The year the question was posted.
5. **Emotion**  
   - The emotion(s) classified by an algorithm based on the question. Multiple emotions may be assigned.
6. **Emotional cause**  
   - The reason why the algorithm classified the question with these emotions.
7. **General cause**  
   - The general cause classified by the algorithm.
8. **Detailed cause**  
   - A more specific cause derived from the general cause.

### Prompt files
1. Relevance 
2. Empathy
3. Comprehensibility
4. Practicality

Each prompt has two files: one in Korean and one in English.

## Reference 
Link to the article: [URL](https://e-hir.org/journal/view.php?number=1245)
```
@article{Junseo2025LLM,
  title = {LLM-Based Response Generation for Korean Adolescents: A Study Using the NAVER Knowledge iN Q&A Dataset with RAG},
  author = {Junseo Kim and {Seok Jun} Kim and Junseok Ahn and Suehyun Lee},
  journal = {Healthcare Informatics Research},
  year = {2025}
}
```
