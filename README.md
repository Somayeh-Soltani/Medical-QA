# Medical-QA
***************************************************************************************************************
Hello

"TREC Test questions.txt" is the extracted questions from https://github.com/abachaa/LiveQA_MedicalTask_TREC2017

I choose 16386 questions from https://github.com/abachaa/MedQuAD as the reference questions.

For each of the questions in "TREC Test questions.txt" (which are 104), I have selected the top 10 similar questions from these 16386 questions, using the TF-IDF. 

"only_TFIDF_top 10.txt" contains these top 10 similar questions.

"only_TFIDF_top 10_answers.txt" contains the answers of these top 10 questions.

I know "only_TFIDF_top 10_answers.txt" is not user friendly! I will work on it!

I ask you if you can find some one who can score each of these 10 answers as: 

 Correct and Complete Answer (3)

 Correct but Incomplete (2)

 Incorrect but Related (1)

 Incorrect (0)

Besides TFIDF, I can find the top 10 similar questions using different methods such as word2vec and doc2vec (with different arguments).

I think if we can give score each of these methods, we can write a good paper.
