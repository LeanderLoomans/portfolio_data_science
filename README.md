# Portfolio Minor Applied Data Science THUAS
Name: Olaf Bolleurs  <br />
Studentnumber: 18115853 <br />
Course: Applied Data Science Minor <br />
Lecturers: Jeroen Vuurens, Tony Andrioli, Ruud Vermeij

## DataCamp
The DataCamp courses where very informative, I learnd a lot form the courses. Before this minor i had a bit of Python programming experience but it was still nice to do all the courses from DataCamp. Below the evidence of completing all the DataCamp courses can be found.
<details> <summary>Evidence of completing DataCamp</summary>

![Images](/Evidence/datacamp_proof.png)
![Images](/Evidence/datacamp_proof_2.png)
</details>

## Research project Dialogue detection
Besides the DataCamp courses and the lectures there was also a project to work on during this minor. The project i worked on was form the Smart Teddy project of THUAS. The goal of the project was to detect dialogues so that it can be used as a quality of life indicator for dementia patients. In the Task definiton a more extensive explanation will be given about the reason and context of the project. 

### Task definition
The problem owner of the project is the Smart Teddy project of THUAS. The Smart Teddy project aims to give insights for healthcare professionals in patients with early stage dementia. This is done by putting sensors in a Teddy Bear so it becomes "Smart". This Smart Teddy Bear will then bet put in to the home of the patient so insights in to the patiens quality of life can be given. With the sensor data, Data Science techniques can be applied to make quality of life indicators. These indicators could be eating patterns, emotions or in our case social interaction.

The problem that the smart teddy bear project aims to tackle is to find the best moment for a patient with dementia to move from there own home in to a assisted living facility. Because assisted living facility's become more full and waiting lists are getting longer the healthcare for dementia patients worsen. An other problem is that healthcare professionals can not be see the patient every time and so the meeting with the dementia patient is just a snapshot of there health at that given moment. while using the smart teddy bear could give a more broader view on the patient health. One of the important indiciator that a patient dementia is worsening is if the amount of social interaction is declining. Thats why our research question is "How can data science techniques detect if there is a conversation between at least two people by analyzing audio files?".

### Evaluation
<details> <summary>Evaluation</summary>
 For as good as we did, there is still room for improvement. So for future work i recommend to look more into improving the filtering model, we have found some      papers that made a voice detection model with better accuracy scores then ours did. I think the main reason why our model does not score aswell as other models is that we needed to put some more time in to developing that model. We hade a first draft that worked great, we thought, but i made an programming error that we overlooked in evaluating and found out at a later stage of the project. So that would be the main focus for future work in my opion. 

 For the voice comparison model improvements could allwasy be made to add more speakers to the dataset so we than know for sure it is not overfitting on the   speakers we put in now. This could also be check to make a test dataset with different speakers than in the training en validiation dataset. 

 It would also be good to look more into the combining of the two models. At the moment of writing we do not have a good way of evaluating the combined model. A way of improving could be to make a dataset with more labels so an accuracy score of the two combined models can be made.
</details>

### Conclusions
<details> <summary>Conclusion</summary>
  The resutls of our study are very promising. We made two models with both good resutls. The results are shown bellow in two models.
  
  Resutls of the first model
  
|          | Accuracy | Precision | Recall | f1   |
|----------|----------|-----------|--------|------|
| Voice    | -        | 0.85      | 0.94   | 0.89 |
| No Voice | -        | 0.94      | 0.84   | 0.88 |
| Total    | 0.89     |           |        |      |
  
  Resutls of the second model
  
|          | Accuracy | Precision | Recall | f1   |
|----------|----------|-----------|--------|------|
| Voice    | -        | 0.96      | 0.92   | 0.94 |
| No Voice | -        | 0.93      | 0.96   | 0.94 |
| Total    | 0.94     |           |        |      |
  
  As seen in the tabels the models have good results that we as a project group are happy with. These results were gotten on a test set.
  Now the research question "How can data science techniques detect if there is a conversation between at least two people by analyzing audio files?" can be answered. We did this by making two Convolutional Neural Nerworks (CNN) with Mel Frequency Cepstral Coefficients (MFCC) as input data. The two models are combined so the first model acts as a filter for the second model. The first model filters the audio sampels that have no speech in them and feeds the sampels with speech to the second model. The second model then compares two sampels with each other to see if the sampels are form the same speaker or from a different speaker. 
  
</details>

### Planning
<details> <summary>Planning</summary>
  For this project we used Scrum for the planning of this project. We had 2 week sprints and changed every sprint form scrum master. So everyone got to be scrum master in this project group. We used the website taiga as scrumboard. [Moet ff plaatje van taiga dingen invoegen]
</details>

## Predictive analysis

### Selecting a Model

### Configuring a Model

### Training a Model

### Evaluating a Model

### Visualizing the outcome of a Model

## Domain knowledge

### Introduction of the subject field

### Literature research

### Explanation of Terminology, jargon and definition

## Data preprocessing

### Data exploration

### Data cleansing

### Data preparation

### Data explanation

### Data visualization

## Communication

### Presentations
- First Internal presentation
- Forth Internal presentation
- Last Internal presentation
- 
- First External presentation

### Writing paper
The writing of the paper was a group effort where some did more then others. I worte the parts following parts in the method section: Neural Networks, Model Architecture. I also worte the following parts in the result section: Introduction, Results for speech detection, results for speaker differentiation. I also gave feedback on the paper and changed some parts in other sections. 

## Reflection and Evaluation 

### Reflection on contriubtion to the project

### Reflection on own learning objectives

### Evaluation on the group project
