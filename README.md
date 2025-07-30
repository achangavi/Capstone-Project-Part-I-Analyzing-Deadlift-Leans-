### Summary:
**Overview**: In this Capstone Project, my goal is to develop a baseline model for a dataset containing spatial coordinates of various people doing deadlifts over time. The original idea was to build the data myself using pre-made videos of people doing squats and/or deadlifts, but due to time constraints, I used an existing dataset from Kaggle.  
### Data:

Our dataset comes from Kaggle [link](https://www.kaggle.com/datasets/venkatagandreti/deadlift-proper-lean-positions?resource=download).  

This dataset captures the biomechanical variations in lean positions during a deadlift, categorized into right lean, neutral position, and left lean. It provides a structured set of coordinates to facilitate detailed analysis of body posture and motion dynamics during this exercise.

Dataset Highlights:
Type: Numerical data of coordinates representing different lean positions.
Categories:
Right Lean: Body tilted to the right during the deadlift.
Neutral: Symmetrical and balanced posture.
Left Lean: Body tilted to the left during the deadlift.
Applications:
Biomechanical and ergonomic studies
Assessment of lifting techniques and postural imbalances
Development of machine learning models for posture detection
Injury prevention and fitness optimization
Target Audience:
This dataset is a valuable resource for researchers, fitness professionals, and data scientists interested in:

Analyzing postural variations during deadlifts.
Identifying potential risks or inefficiencies in lifting techniques.
Training AI models for posture classification.
File Format:
Provided in an easy-to-use Excel file (.xlsx), the dataset includes clear labels and coordinate data for each lean category, ensuring compatibility with analytical tools like Python, R, and Excel.

### Summary and Path Forward:
We have established a baseline model to predict the output (class) for deadlift variations (left leaning, neutral position, and right leaning). We can use this information to compare against different models, and use feature selection to identify the most
important features that contribute to deadlift leans. 
