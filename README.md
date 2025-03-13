# A dataset of questions asked to Authors vs a Chatbor

This is the accompanying dataset for the following research paper: 

Naimul Hoque, Ayman A Mahfuz, Mayukha Sridhatri Kindi, and Naeemul Hassan. 2024. 
Towards Designing a Question-Answering Chatbot for Online News: Understanding Questions and Perspectives. 
In Proceedings of the 2024 CHI Conference on Human Factors in Computing Systems (CHI '24). Association for Computing Machinery, New York, NY, USA, Article 154, 1–17. 
https://doi.org/10.1145/3613904.3642007

<b>If you use the dataset, please cite our paper.</b>

# Dataset Description

```user_id```: Unique identifier for a study participant (i.e., crowd worker).

```news```: Title of the anonymized news article that the participants read. You can find the articles in ```news.zip```.

```condition```: either ```authors``` or ```chatbot```. 
  
- ```Authors```: Participants were prompted to ask questions to
the authors of the article. Participants received the following
prompt:

> Consider you have the option to directly ask questions
to the authors of this article about the article and get answers
from them. Please list any questions you would ask the authors
if you had the opportunity to communicate with them online. You can ask for clarifications, followup information, opinions,
or any other questions that you think are relevant to the article.

- ```Chatbot```: Participants were prompted to ask questions to a
chatbot. Participants received the following prompt:

> Consider there is an automated chatbot that can answer your ques-
tions about this article. Please list any questions you would ask
the chatbot if you had the opportunity to communicate with
it online. You can ask for clarifications, followup information,
opinions, or any other questions that you think are relevant to
the article.

```line_number```: Line numbers in the article that are relevant to the question (Optional).

```question```: The actual question.

```Fact``` ```Details``` ```Evidence``` ```Close_ended``` ```Opinion``` ```Explanation``` ```Other```: The question can fall under one or more of these categories. 
Please see definition and examples of the categories below.

<p align="center">
<img width="719" alt="Screenshot 2025-03-13 at 12 40 52 PM" src="https://github.com/user-attachments/assets/f54c2519-c1e5-4b7c-903a-fd2913c975ad" />
</p>


```Journalism_Integrity```: Whether the question refers to a violation in journalistic integrity.

- ```1```: indicates violation of one or more of the core principles outlined by the Ethical Journalism Network. https://ethicaljournalismnetwork.org

- ```0```: No violation.

```Blooms_taxonomy```: A discrete scale (1-6) to indicate the complexity of the questions. https://en.wikipedia.org/wiki/Bloom%27s_taxonomy

## License
This dataset is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).



 
