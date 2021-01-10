This bot will be capable of giving you the right answers for your questions.

* Train the BERT Model on Squad V2 dataset so that it is able to understand, sometimes answer is not in the given dataset.

1. Read text from an image or pdf
2. Split the text into multiple passages
3. Pass the question and the passage to the BERT Model for question answering
4. Rank the highlighted answers
5. Display them to the users

* In the long run

** It will have multiple textbooks related to the subject in its database
** It will be able to filter out passages based on some heuristic method [Another AI]
** Pass the selected passage to BERT model for selecting answers

* Optimize

### Steps

#### Phase 1
1. Get Bert Model
2. Get SquadV2 Dataset
3. Understand BERT input for Squad Dataset
4. Prepare Squad Dataset
5. Fine Tune
#### Phase 1 Complete [Deploy]

#### Phase 2 
6. Run this model on a large dataset with unanswered questions and Get answers for those questions [Store data from in Production settings]
7. Build a dataset with the above approach
8. Train a new smaller and lighter model trained on this dataset
#### Deploy [Continue retraining the model on new dataset and making it better]

#### Phase 3 
* Search answers from entire textbook

#### Phase 4
* Search answers from multiple textbooks

#### Phase 5
* Deploy as a teaching assistant mechanism

#### Phase 6
* Deploy as a product, which parents can subscribe to, where students can ask their question on a particular subject and get the right answers along with where to go from here

