# NLP25-CommuNotes-TopicModel

This Repo is a topic modeling (BERTopic) part performed on community notes.
The other two part are
- NLP Preprocessing Pipeline (Community Notes) repo: https://github.com/kaikaila/info259_project
- Knowledge Graph repo: https://github.com/courtofdreams/llm-kag-communitynote

Folder 0.raw_data_samples contains raw community notes data from NLP Preprocessing Pipeline
1.BERTopic.ipynb contains code that performs the TopicModeling, andthe  results are in the folder 1.topic_model_results
We found that Politics is the main theme.
2A.Manual_Filter_Politics.xlsx is a manual selection of the highest topic level to be included as the Politics theme.
Then we filter further to 3 main topics with code in 2B.Filter_3MainTopics.ipynb.
The results files are in folder 2.politics_notes
