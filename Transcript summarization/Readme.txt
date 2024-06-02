Steps to run the code:

1. Installation Requirements:

pip install pyspark
pip install spacy
pip install plotly
pip install pandas
pip install transformers
!pip install rouge

2. Download the Spacy model:

import spacy
spacy.cli.download('en_core_web_sm')

3. Import all the required libraries

4. Execute "1. Custom Summarization (using Word Frequency technique) of lecture trancript file using Dataframes" to generate summary file

5. Execute the "2. Word Frequency Distribution for Summary generated using Dataframes"

6. Execute the "3. Evaluating the accuracy using ROUGE metric" code - while executing the code for ROUGE metric, the below reference summary can be used which is a reference summarized output of the input transcript file, which we got from a online summarizing website "https://quillbot.com/summarize"

Reference Summary - "This week's discussion focuses on probability, introducing the mathematical background to probability and discussing its axioms. The building blocks of probability include conditional probability, independence, and random variables. Sample space, often denoted by omega, is the set of all possible outcomes of a random experiment. Experiments can be experimental designs or observations in the real world, such as stock markets. An event is a set of outcomes to which we can assign a probability, and this can be done using simple examples like throwing a die or collecting two coins. For example, if a coin throws a head, there are four possible outcomes. If a coin tosses a coin until a head appears, there are infinitely many possibilities. In mathematics, we can count these outcomes, and we can easily enumerate them. Uncountable outcomes, such as the time until a volcano next erupts, can also be used to understand probability distributions. In this case, the state space sample space is the time until something occurs, which can be positive or uncountable. The speaker emphasizes the importance of considering what is important to us when looking at random variables, such as how many heads there are. The set of possible outcomes has to be finite, and the speaker uses examples of uncountable events to illustrate the concept of probability. In conclusion, this week's discussion focuses on probability, sample space, and probability distributions. By understanding the mathematical foundations of probability and the importance of considering individual outcomes, we can better understand the complexity of probability and its applications in various fields."

7. Execute the "4. ROGUE Scores Visualization for generated summary using Dataframes"

8. Execute the "5. Custom Summarization (by Word Frequency technique) of lecture trancript file using RDD" to generate summary file

9. Execute the "6. Word Frequency Distribution for Summary generated using RDDs"

10. Execute the "7. Evaluating the accuracy using ROUGE metric for summary generated using RDDs"

11. Execute the "8. ROUGE Score Visualisation for summary generated using RDD"

12. Execute the "9. Orginal Text length vs Summarized text length generated using Dataframes and RDDs"

13. Execute the "10. Comparison of ROUGE Scores between DataFrame and RDD Summarization"

14. Execute the "11. Custom summarization using Named Entity Recognition (NER) technique" to generate summary file

15. Execute the "12. Evaluating the accuracy using ROUGE metric for summary generated using NER technique"
16. Execute the

17. Execute the "13. Comparison of ROUGE Scores of custom summarization generated using RDD by Word Frequency technique and RDD by NER technique"





