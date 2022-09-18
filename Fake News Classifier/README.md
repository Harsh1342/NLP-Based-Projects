# Fake-News-Classifier


- train dataset = 'https://drive.google.com/file/d/1RKeGZxOSuajeBiRqUTCqlVjzu863jVCJ/view?usp=sharing'

## Dataset Discription

-train.csv: A full training dataset with the following attributes:

    id: unique id for a news article
    title: the title of a news article
    author: author of the news article
    text: the text of the article; could be incomplete
    label: a label that marks the article as potentially unreliable
        1: unreliable
        0: reliable

test.csv: A testing training dataset with all the same attributes at train.csv without the label.

- Here, I have used diffrent vectorizers to see the accuracy of the NLP model. 
- Due to lake of Computational power availability I implement individual column into consideration.

