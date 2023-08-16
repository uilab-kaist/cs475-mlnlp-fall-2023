# ML for NLP / CS475 / Fall 2023 KAIST

**All contents in this document are tentative.**

## Teaching Staff

Alice Oh (Professor), Haneul Yoo (TA), Jiho Jin (TA), Junho Myung (TA)

<details>
<summary><strong>When you send emails, please email to all TAs and prof. Oh. [Click me to see our emails.]</strong></summary>

<p><code>alice.oh@kaist.edu, haneul.yoo@kaist.ac.kr, jinjh0123@kaist.ac.kr, junho00211@kaist.ac.kr</code></p>

<p><i>And put "CS475" to the title. (e.g., [CS475] Do we have a class on thanksgiving day?)</i></p>

</details>

## Course Description

This course will cover advanced and state-of-the-art machine learning for text data. ML methods covered will include graphical models, Bayesian inference, nonparametric models, and deep learning. By the end of the course, students will be able to

- Understand important concepts in NLP
- Read current research papers in NLP
- Implement some of the basic ML models for NLP
- Conduct replication studies based on a recent NLP+ML paper
- Communicate in written and spoken English about NLP+ML research

## Time and Classroom
- E3-1 2443 (some classes may be held virtually)
- Tue/Thurs 10:30 - 11:45 

## Course Addition
We decided not to approve requests for course addition. We ask for your kind understanding regarding this matter.

## Prerequisites  

- You need to have good programming skills in Python for replication/modification of recent NLP research.
- You need to have a basic understanding of ML concepts. You do not need to have taken CS376 or any other undergraduate ML course, but you need to know concepts such as supervised vs unsupervised learning, train vs test data, clustering vs classification, accuracy/precision/recall, overfitting, and basic classification models such as SVM, random forest, etc. You can learn these concepts as we go along, but you may find some lectures and papers difficult to understand if you do not put in extra time to learn these concepts.
- We will use well-known frameworks for machine learning. You may start with little prior experience and learn these libraries during this semester, but that will require extra time and effort. Note that we do not provide any lectures about learning them.
- The topic of the course includes Korean NLP. You do not need to be fluent in Korean, but you need to know what the Korean alphabet (Hangeul) is and how they combine to form syllables and words.

## Materials

- Recent NLP papers (especially from ACL, EMNLP, NAACL)
- Recent ML papers (AAAI, ICML, IJCAI, NeurIPS, etc)
- [Dan Jurafsky & James H. Martin, Speech and Language Processing (3rd ed. draft)](https://web.stanford.edu/~jurafsky/slp3/)

## Schedule (Subject to Change)

All deadlines are 23:59:59 unless specified.

| Week | Date       | Topic                                 | Notes                    | Homework             |
|------|------------|---------------------------------------|--------------------------|----------------------|
|    1 | 2023.08.29 | Introduction to CS475                 |                          |                      |
|    1 | 2023.08.31 | Introduction to NLP                   |                          |                      |
|    2 | 2023.09.05 | Language Models                       | Ch 3 of SLP book         |                      |
|    2 | 2023.09.07 | Language Models & Word Vectors        | Ch 6 of SLP book         | HW 1 Out             |
|    3 | 2023.09.12 | Word Vectors                               |                  |                      |
|    3 | 2023.09.14 | Text Classification                          | Deadline to Submit Teams | HW 1 Due             |
|    4 | 2023.09.19 | Neural Networks                   |                          | HW 2 Out             |
|    4 | 2023.09.21 | Project Proposal                   |                          |                      |
|    5 | 2023.09.26 | Project Proposal                      |                          | HW 2 Due             |
|    5 | 2023.09.28 | Holiday                      |      No Class                    |                      |
|    6 | 2023.10.03 | Holiday                               | No Class                 |                      |
|    6 | 2023.10.05 | Wrap-up NN and RNN                    |                          | HW 3 Out             |
|    7 | 2023.10.10 | Transformers and BERT, GPT                               | No Class                 |                      |
|    7 | 2023.10.12 | Guest Lecture                 |                          | HW 3 Due             |
|    8 | 2023.10.17 | Midterm                               | No Class                 |                      |
|    8 | 2023.10.19 | Midterm                               | No Class                 |                      |
|    9 | 2023.10.24 | Datasets and Evaluation               |                          | HW 4 Out             |
|    9 | 2023.10.26 | Ethics and Social Impact of NLP       |                          |                      |
|   10 | 2023.10.31 | Sentiment & Emotions                  |                          | HW 4 Due             |
|   10 | 2023.11.02 | Question Answering                    |                          |                      |
|   11 | 2023.11.07 | Project Progress                      | Record & Upload          |                      |
|   11 | 2023.11.09 | Project Progress                      | Record & Upload          |                      |
|   12 | 2023.11.14 | Machine Translation & Multilinguality |                          |                      |
|   12 | 2023.11.16 | Generative Models                     |                          |                      |
|   13 | 2023.11.21 | Generative Models & Applications                      |                          |                      |
|   13 | 2023.11.23 | Generative Models & Society                   |                          |                      |
|   14 | 2023.11.28 | Wrap-up                               | Recorded Class           |                      |
|   14 | 2023.11.30 | Undergraduate Admissions              | No Class                 |                      |
|   15 | 2023.12.05 | Final Presentation                    | Record & Upload          |                      |
|   15 | 2023.12.07 | Final Presentation                    | Record & Upload          |                      |
|   16 | 2023.12.12 | Final Exam (Final Report Due)         | No Class                 |                      |
|   16 | 2023.12.14 | Final Exam                            | No Class                 |                      |

## Homework Assignments (Subject to Change)
1. RNN Family
2. BERT
3. Ethics & Social Impact of NLP

## Attendance and Participation
Sometimes (expect about 10 times during the semester), we will have a "quiz" in class. The grade will be 0 or 1, so if you turn in an answer, you will get credit. The format will be different for each class. If you miss up to 2 classes, there will be no penalty. After 2, points will be taken off. Because you can miss up to 2 for free, we will not take any excuses for missing the class (unless you have a special case, such as prolonged sickness, in which case you should email the teaching staff).

## Team Projects

- You will form teams of *three or four*, and as a team, pick one NLP paper from ACL, EMNLP, NAACL, TACL, NeurIPS, ICML, and ICLR, published in 2021 to 2023, and replicate it. You will be required to change at least one thing -- dataset, model, or research question. More details will be given out during the first week of class.
- [Link to project description](https://uilab-kaist.github.io/cs475-mlnlp-fall-2022/project)

## Evaluation
Your grade will be a combination of the following:

- Homework 20%
- Attendance/Quiz & Participation 20%
- Team Project 50% 
  - Proposal 5%
  - Paper (replication) presentation 10%
  - Final presentation 20%
  - Written report 10%
  - Teamwork 5% (Note that any team may get up to -25% if there is a serious problem with teamwork)
- Peer Review Participation 10%
  
## LLM Policy
We allow and encourage students to use AI-based tools, including large language models, but we require that students list the tools used and describe in detail how the tools are used. A more specific explanation of the policy will be given in class. Anyone not following this policy will be penalized, up to and including an F in the class.

## Late Policy
Unless otherwise specified, we will not accept late homework assignments, quizzes, peer evaluations, or project submissions. For exceptional individual circumstances, please contact the teaching staff.
